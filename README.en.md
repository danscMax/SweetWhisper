<div align="center">

<img src="assets/hero-cat.png" alt="SweetWhisper" width="160">

# SweetWhisper

**Voice typing for Windows and Android. Speech is recognized on your own device — audio never leaves it.**

[🌐 Website](https://sweetwhisper.app/en/) · [⬇️ Download](#download) · [🤖 Android app](https://sweetwhisper.app/en/android/) · [🐛 Report a bug](../../issues/new/choose) · [Русский](README.md)

<!-- Badge versions are edited by hand on each release. -->
![Windows 0.11.4](https://img.shields.io/badge/Windows_10%2F11-0.11.4-0078D6?logo=windows&logoColor=white)
![Android 3.6](https://img.shields.io/badge/Android_9%2B-3.6-3DDC84?logo=android&logoColor=white)
![Offline](https://img.shields.io/badge/recognition-100%25%20on--device-2ea44f)
![90+ languages](https://img.shields.io/badge/languages-90%2B-blue)

<img src="assets/demo.gif" alt="Demo: dictate into any app" width="640">

**It's out.** The Windows build and the Android app are available to download right now — see below.

</div>

---

Hold a hotkey — speak — release. The text lands in whatever app has focus: messenger, email, IDE, browser. Same thing on the phone, except the hotkey is the microphone on your keyboard. No internet required, no subscriptions, no voice sent to the cloud.

## Download

| Platform | File | Size | From the site | From GitHub |
|---|---|---|---|---|
| **Windows 10/11** · installer | `SweetWhisper-Setup.exe` | 17.5 MB | [download](https://sweetwhisper.app/dl/SweetWhisper-Setup.exe) | [v0.11.4](../../releases/latest) |
| **Windows 10/11** · portable | `SweetWhisper-Portable.zip` | 33.6 MB | [download](https://sweetwhisper.app/dl/SweetWhisper-Portable.zip) | [v0.11.4](../../releases/latest) |
| **Android 9+** · APK | `SweetWhisper.apk` | 47.9 MB | [download](https://sweetwhisper.app/dl/SweetWhisper.apk) | [android-v3.6](../../releases/tag/android-v3.6) |

The site and Releases serve the very same bytes — take whichever is convenient. The site links always point at the newest build; [Releases](../../releases) keep the older versions and the checksums. What changed from version to version — [full changelog](https://sweetwhisper.app/en/changelog/).

On first launch Windows may show a SmartScreen warning — the app is young and has not built up "reputation" with Microsoft yet. [What that means and why it is fine](https://sweetwhisper.app/en/#download). Android will ask once whether you trust the source you are installing from — [step by step with pictures](https://sweetwhisper.app/en/android/).

The **free Windows version** includes the full local recognition stack with no limits — every engine, every model, dictation, history. **Pro** (one-time purchase, not a subscription) adds live preview, LLM cleanup, profiles and other superpowers — [details and price](https://sweetwhisper.app/en/#pricing). **The Android app is entirely free.**

## What it does on Windows

|  |  |
|---|---|
| 🎙️ **Dictate into any window** | Push-to-talk or toggle; text is inserted straight into the active app |
| 🌍 **90+ languages** | Whisper and NVIDIA Parakeet for English and beyond; GigaAM for best-in-class Russian |
| 🔒 **100% offline** | Recognition runs entirely on your GPU/CPU (Vulkan, DirectML). Network is used only for model downloads and update checks |
| ⚡ **Live preview** | See the text appear while you are still speaking |
| 🗣️ **Voice commands** | "Kitty, undo", "Kitty, open notepad" — hands-free control |
| 🤖 **LLM cleanup** | A local language model removes filler words, fixes punctuation, translates — offline too |
| 👤 **Per-app profiles** | Different settings for your IDE, messenger and docs — switched automatically |
| 📜 **Dictation history** | Full-text search across everything you have dictated |

<div align="center">
<img src="assets/bar.png" alt="Floating bar" width="360">
</div>

## Sweet Whisper for Android

It is a voice keyboard: you dictate right where you normally type. Open a chat, tap the microphone on the keyboard, speak — the words land straight in the message. Nothing to copy, nowhere to switch.

<div align="center">
<img src="assets/android-main-en.png" alt="Main screen" width="230">
</div>

- Dictate in any app — straight from the keyboard
- Everything runs on the phone; recordings never leave the device
- GigaAM hears Russian with commas and capitals
- The model is matched to your phone on first launch
- Searchable history, your own term dictionary, spoken punctuation
- Quick-settings tile, home-screen widget and system voice input
- Free, no ads, no account

[How to install the APK and enable the keyboard →](https://sweetwhisper.app/en/android/)

## Requirements

**Windows**

- Windows 10/11 x64
- For GPU acceleration: any Vulkan-capable GPU (NVIDIA / AMD / Intel); CPU-only works with the lighter models
- ~2–4 GB of disk space for models (downloaded on first launch, your choice)

**Android**

- Android 9 or newer
- 0.2–1 GB for the model — depends on which one you pick

## Found a bug? Have an idea?

Open an [Issue](../../issues/new/choose) — the templates will tell you what to attach. The app has a "Copy diagnostics" button (Settings → Help); paste its output into your report to speed up the fix. We respond fast: the product is under active development and early users get fixes within days, not months.

Questions, impressions and wishes go to [Discussions](../../discussions).

## Privacy

Audio and recognized text **never leave your device**. The network is used only for: model downloads you request, update checks, and error reports — only when you press the send button yourself. Details: [privacy policy](https://sweetwhisper.app/en/privacy/).

## License

SweetWhisper is proprietary software (© Roger, all rights reserved); this repository hosts distribution materials, not the source code. The app is built on open engines — [whisper.cpp](https://github.com/ggml-org/whisper.cpp), [ONNX Runtime](https://github.com/microsoft/onnxruntime) — and open models: Whisper © OpenAI (MIT), GigaAM © SberDevices (MIT), Parakeet © NVIDIA (CC-BY-4.0), Silero VAD. The Android app is a fork of [whisperIME](https://github.com/woheller69/whisperIME) © woheller69 (MIT). Full list in the app: Settings → About → "Models & licenses".
