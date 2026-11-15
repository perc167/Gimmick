# Gimmick

A custom Discord client for Windows: themes, a top-bar of extras, a music studio, and a mascot who answers when you say "hey Gimmick".

## Download

Get `Gimmick-Setup-x.y.z.exe` from the [latest release](https://github.com/perc167/Gimmick/releases/latest) and run it.

The installer is not code-signed, so Windows SmartScreen will warn you the first time: click **More info**, then **Run anyway**.

## Updates

Gimmick updates itself. It checks for a new release when it starts and every hour, downloads it in the background, and installs it the next time you close Gimmick.

## Notes

- Gimmick is unofficial and is not made or endorsed by Discord. Modified clients are against Discord's terms of service; use it at your own risk.
- "Hey Gimmick" needs your own Claude API key. Put `ANTHROPIC_API_KEY=...` in a file named `.env` in `%APPDATA%\Gimmick` and restart Gimmick.
- VST plugins in the studio need Python with the `pedalboard` package installed.
