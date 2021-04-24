# Real-time Noise Suppression Loader for PulseAudio

Helper script to easily load or unload the
[Real-time Noise Suppression Plugin](https://github.com/werman/noise-suppression-for-voice/)
by [@werman](https://github.com/werman) for PulseAudio, written in bash.

## Dependencies

Needs PulseAudio and the
[Real-time Noise Suppression Plugin](https://github.com/werman/noise-suppression-for-voice/),
see `rnnoise_loader -h` for more information. If you are using ArchLinux,
have a look at [this AUR package](https://aur.archlinux.org/packages/noise-suppression-for-voice/)

If you want to check the plugin you also need the ladspa development suite
(Arch Linux package `ladspa`, Ubuntu package `ladspa-sdk`).

## Usage

Basic usage is `rnnoise_loader` to load the plugin for your default source and
`rnnoise_loader -u` to unload it. Noise reduction for sinks is also supported.

## Alternatives

- [NoiseTorch](https://github.com/lawl/NoiseTorch): If you need a GUI or auto updater
- Directly load the plugin in `default.pa` (note that the plugin uses the CPU even if not used)
