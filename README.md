# Awesome Voice Typing

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

A curated list of open-source speech-to-text tools for voice typing and dictation — desktop, mobile, and CLI.

These tools let you speak and have text appear wherever you're typing. Some run speech-to-text entirely offline on your own hardware, others use cloud APIs, and many support both. All are open source.

---

## Contents

- [By Platform](#by-platform)
- [All Tools](#all-tools)
- [Contributing](#contributing)
- [License](#license)

## By Platform

**Linux** — Buzz, Elograf, Epicenter Whispering, Handy, HNS, hyprwhspr, nerd-dictation, OpenWhispr, Speak to AI, Vocalinux, Voquill, VOXD, whisper_dictation, whisper-writer

**macOS** — Amical, Buzz, Epicenter Whispering, FluidVoice, Handy, HNS, OpenSuperWhisper, OpenWhispr, Pindrop, Tambourine Voice, TypeWhisper, VoiceInk, VoiceTypr, Voquill, whisper-writer

**Windows** — Amical, Buzz, Chirp, Epicenter Whispering, Handy, HNS, OmniDictate, OpenWhispr, Tambourine Voice, VoiceTypr, Voquill, whisper-writer

**Android** — Offline Voice Input, Whisper IME

**iOS** — WhisperBoard

Most tools on this list support offline speech recognition — see the Transcription column below for details.

## All Tools

| Name | Stars | Description | Platforms | Transcription | Engine | Languages | Notes |
|------|-------|-------------|-----------|---------------|--------|-----------|-------|
| [Amical](https://github.com/amicalhq/amical) | ![](https://img.shields.io/github/stars/amicalhq/amical?style=flat-square) | Context-aware dictation utility that adapts formatting to the specific app you are using | macOS, Windows | Local | Whisper | | |
| [Buzz](https://github.com/chidiwilliams/buzz) | ![](https://img.shields.io/github/stars/chidiwilliams/buzz?style=flat-square) | Desktop app for transcribing audio via mic or files using multiple Whisper backends | Linux, macOS, Windows | Local | Whisper, Whisper.cpp, Faster Whisper | | to own UI, not directly into other apps |
| [Chirp](https://github.com/Whamp/chirp) | ![](https://img.shields.io/github/stars/Whamp/chirp?style=flat-square) | Dictates text anywhere on Windows using NVIDIA Parakeet, runs on CPU only | Windows | Local | Parakeet TDT | Multilingual | Corporate environment friendly - no new executables (.exe) required |
| [Elograf](https://github.com/papoteur-mga/elograf) | ![](https://img.shields.io/github/stars/papoteur-mga/elograf?style=flat-square) | GUI system tray frontend for nerd-dictation with model switching and timeout settings | Linux | Local | Vosk (via nerd-dictation) | Multilingual | Requires nerd-dictation installed separately |
| [Epicenter Whispering](https://github.com/EpicenterHQ/epicenter/tree/main/apps/whispering) | ![](https://img.shields.io/github/stars/EpicenterHQ/epicenter?style=flat-square) | Local-first dictation with global shortcut and multiple Whisper providers | Linux, macOS, Windows, Web | Hybrid | Whisper | Multilingual | Also available as Chrome extension and web app |
| [FluidVoice](https://github.com/altic-dev/FluidVoice) | ![](https://img.shields.io/github/stars/altic-dev/FluidVoice?style=flat-square) | macOS dictation app that can type into any app and supports multiple local speech engines | macOS | Hybrid | Parakeet, Apple Speech, Whisper | Multilingual | |
| [Handy](https://github.com/cjpais/Handy) | ![](https://img.shields.io/github/stars/cjpais/Handy?style=flat-square) | Press a shortcut, speak, and text appears in any text field. Fully offline | Linux, macOS, Windows | Local | Whisper.cpp, Parakeet TDT | Multilingual | Built with Tauri; supports six ASR model families |
| [HNS](https://github.com/primaprashant/hns) | ![](https://img.shields.io/github/stars/primaprashant/hns?style=flat-square) | CLI tool that records from your mic, transcribes locally, and copies the result to your clipboard | Linux, macOS, Windows | Local | Faster Whisper | Multilingual | Unix-composable design; integrates with Claude Code and LLM CLI tools |
| [hyprwhspr](https://github.com/goodroot/hyprwhspr) | ![](https://img.shields.io/github/stars/goodroot/hyprwhspr?style=flat-square) | Linux push-to-talk dictation with themed visualizer and multiple STT backends | Linux | Hybrid | Whisper.cpp, Parakeet, REST API | Multilingual | AUR package available; systemd and Waybar integration |
| [nerd-dictation](https://github.com/ideasman42/nerd-dictation) | ![](https://img.shields.io/github/stars/ideasman42/nerd-dictation?style=flat-square) | Hackable offline dictation that types into any window via simulated keystrokes | Linux | Local | Vosk | Multilingual | Single-file Python script; supports xdotool, ydotool, wtype, dotool |
| [Offline Voice Input (Android)](https://github.com/notune/android_transcribe_app) | ![](https://img.shields.io/github/stars/notune/android_transcribe_app?style=flat-square) | Offline Android voice input keyboard plus live subtitles | Android | Local | Parakeet TDT | Multilingual | Focused on on-device transcription and privacy |
| [OmniDictate](https://github.com/gurjar1/OmniDictate) | ![](https://img.shields.io/github/stars/gurjar1/OmniDictate?style=flat-square) | Desktop dictation tool aimed at type anywhere workflows | Windows | Local | Whisper | | |
| [OpenSuperWhisper](https://github.com/Starmel/OpenSuperWhisper) | ![](https://img.shields.io/github/stars/Starmel/OpenSuperWhisper?style=flat-square) | macOS menu bar dictation app with global shortcuts and transcription running directly on Apple Silicon | macOS | Local | Whisper, Parakeet | Multilingual | Built natively with Swift for optimized neural engine execution; Asian language auto-correction |
| [OpenWhispr](https://github.com/OpenWhispr/openwhispr) | ![](https://img.shields.io/github/stars/OpenWhispr/openwhispr?style=flat-square) | Cross-platform dictation with local models and optional BYO cloud providers | Linux, macOS, Windows | Hybrid | Whisper.cpp, Parakeet, BYOK cloud | Multilingual | Electron-based; Wayland support via D-Bus; custom dictionary |
| [Pindrop](https://github.com/watzon/pindrop) | ![](https://img.shields.io/github/stars/watzon/pindrop?style=flat-square) | macOS menu-bar dictation app that runs fully offline | macOS | Local | WhisperKit | Multilingual | Optional AI enhancement to clean up transcriptions |
| [Speak to AI](https://github.com/AshBuk/speak-to-ai) | ![](https://img.shields.io/github/stars/AshBuk/speak-to-ai?style=flat-square) | Minimal Linux desktop dictation that inserts text into the active window | Linux | Local | Whisper.cpp | Multilingual | Can also be invoked as a CLI tool |
| [Tambourine Voice](https://github.com/kstonekuan/tambourine-voice) | ![](https://img.shields.io/github/stars/kstonekuan/tambourine-voice?style=flat-square) | Voice interface for any app supporting multiple STT and LLM providers | macOS, Windows | Hybrid | Multiple (configurable) | Multilingual | |
| [TypeWhisper](https://github.com/TypeWhisper/typewhisper-mac) | ![](https://img.shields.io/github/stars/TypeWhisper/typewhisper-mac?style=flat-square) | Voice typing app with local and cloud engine options | macOS | Hybrid | Whisper (local and/or cloud) | Multilingual | |
| [Vocalinux](https://github.com/jatinkrmalik/vocalinux) | ![](https://img.shields.io/github/stars/jatinkrmalik/vocalinux?style=flat-square) | Linux dictation supporting whisper.cpp, Whisper, and Vosk with distro-specific guides | Linux | Local | Whisper.cpp, Whisper, Vosk | Multilingual | Vulkan acceleration for AMD, Intel, and NVIDIA |
| [VoiceInk](https://github.com/Beingpax/VoiceInk) | ![](https://img.shields.io/github/stars/Beingpax/VoiceInk?style=flat-square) | Native macOS dictation with per-app Power Mode settings | macOS | Hybrid | WhisperKit, BYOK | Multilingual | Also sold commercially; supports personal dictionary for custom words and industry terms |
| [VoiceTypr](https://github.com/moinulmoin/voicetypr) | ![](https://img.shields.io/github/stars/moinulmoin/voicetypr?style=flat-square) | Voice-to-text dictation built with Tauri | macOS, Windows | Local | Whisper-based | Multilingual | Requires one-time license purchase |
| [Voquill](https://github.com/josiahsrc/voquill) | ![](https://img.shields.io/github/stars/josiahsrc/voquill?style=flat-square) | Cross-platform voice typing with personal glossary and AI text cleanup | Linux, macOS, Windows | Hybrid | Whisper.cpp, BYOK cloud | Multilingual | |
| [VOXD](https://github.com/jakovius/voxd) | ![](https://img.shields.io/github/stars/jakovius/voxd?style=flat-square) | Linux dictation with GUI, tray, and CLI modes plus optional LLM post-processing | Linux | Local | Whisper.cpp | Multilingual | Supports all major linux distros |
| [WhisperBoard](https://github.com/Saik0s/Whisperboard) | ![](https://img.shields.io/github/stars/Saik0s/Whisperboard?style=flat-square) | Open-source iOS app for recording speech and producing text using downloadable Whisper models | iOS | Local | Whisper.cpp | Multilingual | |
| [Whisper IME](https://github.com/woheller69/whisperIME) | ![](https://img.shields.io/github/stars/woheller69/whisperIME?style=flat-square) | Android keyboard and standalone app powered by Whisper, fully offline | Android | Local | Whisper.cpp | Multilingual | Available on F-Droid; can also translate to English |
| [whisper-writer](https://github.com/savbell/whisper-writer) | ![](https://img.shields.io/github/stars/savbell/whisper-writer?style=flat-square) | Records via hotkey and auto-types the transcription into the active window | Linux, macOS, Windows | Hybrid | Faster Whisper, OpenAI API | Multilingual | Continuous, voice-activity, hold-to-record, and toggle modes |
| [whisper_dictation](https://github.com/themanyone/whisper_dictation) | ![](https://img.shields.io/github/stars/themanyone/whisper_dictation?style=flat-square) | Feature-rich Linux voice keyboard with dictation, voice commands, and webcam integration | Linux | Local | Whisper.cpp | Multilingual | Includes voice commands for pause/resume; requires ≥4 GiB VRAM |

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding, updating, or removing entries.

## License

[MIT](LICENSE)
