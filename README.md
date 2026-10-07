# League Coach

A coach for League of Legends that watches your game and gives one clear call at a time: champion select, your build, what to do next. It covers Summoner's Rift, Arena, ARAM and ARAM: Mayhem. Advice shows in its own window, so put it on a second monitor. It never touches the game: it only reads your screen and Riot's own local game data.

## Install

1. Download **LeagueCoach-Setup-x.y.z.exe** from the [latest release](../../releases/latest).
2. Run it. Windows may say "Windows protected your PC" because the installer isn't signed: click **More info**, then **Run anyway**. It installs for your user only (no admin prompt).
3. Open **League Coach** from the Start menu or the desktop shortcut.

## First run

- **Claude:** the coach needs an Anthropic API key. Get one at console.anthropic.com → API Keys, paste it in the setup screen and press Connect. It's stored in Windows Credential Manager and only sent to Anthropic. Calls are billed to your key. Settings → AI also takes an OpenAI, Google Gemini or OpenRouter key instead.
- **League:** set the client language to English (the coach reads card names). Leave League Coach open while you play.
- **During a game:** press **F8** to ask the coach about whatever is on screen.

## Updates

League Coach checks for new versions by itself and shows an update bar. Press **Install update**: it downloads, checks and installs, then reopens. It never updates during a game.

## Uninstall

Settings → Apps → League Coach → Uninstall. Your games and settings stay in `%LOCALAPPDATA%\LeagueCoach`; delete that folder to remove them too.
