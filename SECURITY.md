# Политика безопасности / Security Policy

[Русский](#русский) · [English](#english)

## Русский

Нашли уязвимость — пожалуйста, **не публикуйте её в открытых issue**. Сообщите о ней приватно, одним из двух способов:

- **Прямо на GitHub** — [Security → Report a vulnerability](../../security/advisories/new). Приватный канал, видим только нам, ничего заводить не нужно.
- **Письмом** на **hello@sweetwhisper.app** с пометкой «security» в теме.

Приложите описание, шаги воспроизведения и версию приложения. Отвечаем в течение 72 часов; исправления уязвимостей выходят вне очереди, не дожидаясь ближайшего релиза. После того как починим, с удовольствием укажем вас в благодарностях — если захотите.

**Что относится к делу**

- Приложение SweetWhisper для Windows
- Приложение Sweet Whisper для Android
- Сайт sweetwhisper.app и сервис relay, который принимает отчёты об ошибках

**Что не относится**

- Уязвимости в самих движках и моделях — [whisper.cpp](https://github.com/ggml-org/whisper.cpp), ONNX Runtime, Whisper, GigaAM, Parakeet, Silero VAD. Их чинят авторы, сообщать нужно им. Мы всё равно будем благодарны, если предупредите и нас.
- Файлы моделей, которые вы скачали сами из сторонних источников.

## English

Found a vulnerability? Please **do not open a public issue**. Report it privately, either way:

- **On GitHub** — [Security → Report a vulnerability](../../security/advisories/new). A private channel, visible only to us, nothing to set up.
- **By email** to **hello@sweetwhisper.app**, with "security" in the subject line.

Include a description, reproduction steps and the app version. We reply within 72 hours; security fixes ship out of band rather than waiting for the next release. Once it is fixed we will gladly credit you — if you want us to.

**In scope**

- SweetWhisper for Windows
- Sweet Whisper for Android
- The sweetwhisper.app website and the relay service that receives error reports

**Out of scope**

- Vulnerabilities in the engines and models themselves — [whisper.cpp](https://github.com/ggml-org/whisper.cpp), ONNX Runtime, Whisper, GigaAM, Parakeet, Silero VAD. Their authors fix those, so report there. We will still appreciate a heads-up.
- Model files you downloaded yourself from third-party sources.
