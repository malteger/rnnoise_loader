# RNNoise based voice suppression loader for Pulseaudio

Helper script to easily load or unload the
[voice suppression plugin by werman](https://github.com/werman/noise-suppression-for-voice/),
written in bash.

## Usage

Needs the
[voice suppression plugin by werman](https://github.com/werman/noise-suppression-for-voice/),
see `rnnoise_loader -h` for more information. If you are using ArchLinux,
see [here](https://aur.archlinux.org/packages/noise-suppression-for-voice/)

Basic usage is `rnnoise_loader` to load the plugin for your default source and
`rnnoise_loader -u` to unload it. Supports also sink mode.

## Alternatives

- [NoiseTorch](https://github.com/lawl/NoiseTorch): If you need a GUI or auto updater
- Use the plugin directly
