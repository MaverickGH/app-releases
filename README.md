# App Releases

Публичные установщики наших десктоп-приложений. Исходный код живёт в отдельных (как правило приватных) репозиториях — здесь только готовые сборки для скачивания.

Public installers for our desktop apps. Source code lives in separate (usually private) repositories; this repo hosts the downloadable builds only.

**Схема тегов / tag scheme:** `<app>-vX.Y.Z` — у каждого приложения свои релизы.

## Приложения / Apps

### VideoText — видео → текст, субтитры и перевод
Десктоп-приложение (macOS + Windows): распознаёт речь из видео и делает редактируемый текст, субтитры (TXT/SRT/WebVTT) и перевод. / Desktop app (macOS + Windows): transcribe video speech into editable text, subtitles and translation.

- **macOS (DMG)** и **Windows x64 (ZIP)** → [релиз / release `videotext-v0.1.0`](../../releases/tag/videotext-v0.1.0)
- Windows пока содержит основной сценарий; плеер, OCR, очередь и история — только в macOS-версии.

### MoCapGate — мокап из видео / motion capture from video
Снимите человека на телефон или веб-камеру — анимация скелета BVH/FBX для Blender, Maya и движков. / Film a person with a phone or webcam — get a BVH/FBX skeleton animation for Blender, Maya and game engines.

- **macOS Apple Silicon и Intel (DMG или быстрый старт ZIP)**, **Windows 10/11 (быстрый старт ZIP)**, **Linux / любая ОС (переносной ZIP)** → [релиз / release `mocapgate-v0.3.1`](../../releases/tag/mocapgate-v0.3.1)
- Исходники открыты / open source (MIT): [MaverickGH/mocapgate](https://github.com/MaverickGH/mocapgate). Сборки без подписи; GVHMR и SMPL-X — только некоммерческое использование / non-commercial only.

### SkillGuard — досмотр расширений AI-агента / vet AI-agent extensions
Проверка скиллов, MCP-серверов и плагинов для Claude Code, Codex, Cursor и Claude Desktop до установки: инъекции агенту, отравление инструментов MCP, увод ключей, опасные команды, уязвимые зависимости. Статический анализ — код не запускается. / Check skills, MCP servers and plugins for Claude Code, Codex, Cursor and Claude Desktop before installing: agent injection, MCP tool poisoning, key exfiltration, dangerous commands, vulnerable dependencies. Static analysis — code is never run.

- **macOS Apple Silicon (DMG)** → [релиз / release `skillguard-v1.0.0`](../../releases/tag/skillguard-v1.0.0)
- Подпись ad-hoc без нотаризации: первый запуск — правый клик → «Открыть». / Ad-hoc signature, not notarized: right-click → Open on first launch.

---

Все релизы: вкладка **[Releases](../../releases)**. / All releases: the **[Releases](../../releases)** tab.
