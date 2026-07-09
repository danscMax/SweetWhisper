<div align="center">

<img src="assets/hero-cat.png" alt="SweetWhisper" width="160">

# SweetWhisper

**Voice typing for Windows. Fully offline — your audio never leaves your computer.**

[🌐 Website](https://sweetwhisper.app/en) · [⬇️ Download](https://sweetwhisper.app/en#download) · [🐛 Report a bug](../../issues/new/choose) · [Русский](README.md)

![Windows 10/11](https://img.shields.io/badge/Windows-10%2F11-0078D6?logo=windows&logoColor=white)
![Offline](https://img.shields.io/badge/recognition-100%25%20on--device-2ea44f)
![90+ languages](https://img.shields.io/badge/languages-90%2B-blue)

<img src="assets/demo.gif" alt="Demo: dictate into any app" width="640">

</div>

---

Hold a hotkey — speak — release. The text lands in whatever app has focus: messenger, email, IDE, browser. No internet required, no subscriptions, no voice sent to the cloud.

## Features

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

## Download

Downloads live at [sweetwhisper.app](https://sweetwhisper.app/en#download) (installer and portable). Releases will also be mirrored here under [Releases](../../releases).

The **free version** includes the full local recognition stack with no limits — every engine, every model, dictation, history. **Pro** (one-time purchase, not a subscription) adds live preview, LLM cleanup, profiles and other superpowers — details [on the website](https://sweetwhisper.app/en#pricing).

## Requirements

- Windows 10/11 x64
- For GPU acceleration: any Vulkan-capable GPU (NVIDIA / AMD / Intel); CPU-only works with the lighter models
- ~2–4 GB of disk space for models (downloaded on first launch, your choice)

## Found a bug? Have an idea?

Open an [Issue](../../issues/new/choose) — the templates will tell you what to attach. The app has a "Copy diagnostics" button (Settings → Help); paste its output into your report to speed up the fix. We respond fast: the product is under active development and early users get fixes within days, not months.

## Privacy

Audio and recognized text **never leave your computer**. The network is used only for: model downloads you request, update checks, and error reports — only when you press the send button yourself. Details: [privacy policy](https://sweetwhisper.app/en/privacy).

## License

SweetWhisper is proprietary software (© Roger, all rights reserved); this repository hosts distribution materials, not the source code. The app is built on open engines — [whisper.cpp](https://github.com/ggml-org/whisper.cpp), [ONNX Runtime](https://github.com/microsoft/onnxruntime) — and open models: Whisper © OpenAI (MIT), GigaAM © SberDevices (MIT), Parakeet © NVIDIA (CC-BY-4.0), Silero VAD. Full list in the app: Settings → About → "Models & licenses".
