# Schedule Agent downloads

A desktop calendar with optional AI, for Windows x64 and Linux x86_64.

[Download the latest release](https://github.com/Veershah611/ScheduleAgent-releases/releases/latest)

- **Windows:** run ScheduleAgent-windows-x64-setup.exe, then open Schedule Agent from Start.
- **Linux:** use the AppImage or install the .deb through your software manager.
- Model downloads are optional. Reuse Ollama or another model server, or continue without AI.
- Google Calendar sync is optional.

## Install from a terminal

Windows Command Prompt:

```bat
curl.exe -fL https://github.com/Veershah611/ScheduleAgent-releases/releases/latest/download/install.ps1 -o "%TEMP%\schedule-agent-install.ps1" && powershell.exe -NoProfile -ExecutionPolicy Bypass -File "%TEMP%\schedule-agent-install.ps1"
```

Linux:

```bash
curl -fL https://github.com/Veershah611/ScheduleAgent-releases/releases/latest/download/install.sh -o /tmp/schedule-agent-install.sh && bash /tmp/schedule-agent-install.sh
```

Linux needs a compatible x86_64 desktop distribution (Ubuntu 22.04 baseline). ARM, mobile
and macOS packages are not currently provided.

## Updates

Windows and AppImage installations check for new releases automatically. Choose
**Install & restart**, or use **Settings > App updates > Check for updates**.
Updates are signature-verified and preserve your calendar, settings and model files.
Debian users can install the new .deb using their software manager.

Built-in AI runs on your computer. Connecting a model server sends prompts and calendar
tool results to that server. Choose an endpoint you trust.

This repository contains downloads and update metadata. It does not host the app source.
