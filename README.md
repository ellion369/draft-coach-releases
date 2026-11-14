# Draft Coach

A draft coach for League of Legends on Windows. It reads champion select from your own League client, suggests bans and picks from how you actually play, and writes a game plan once all ten champions are locked: your lane, both junglers, every teammate's matchup, teamfights and your build.

## Install

1. Download the installer from the [latest release](https://github.com/ellion369/draft-coach-releases/releases/latest): the file named `DraftCoach_<version>_x64-setup.exe`.
2. Run it. Windows may show "Windows protected your PC", because the installer has no paid code-signing certificate. Choose **More info**, then **Run anyway**.
3. Open Draft Coach and enter your Riot ID.

Windows 10 or 11, 64-bit.

## You need your own API key

The coach runs on Claude (Anthropic) or Gemini (Google). Add your key under **Settings → API keys**. It is stored in Windows Credential Manager on your PC and sent only to that provider. Usage is billed to your own account.

- Claude: https://console.anthropic.com/settings/keys
- Gemini: https://aistudio.google.com/apikey

## Updates

Draft Coach checks this page every time it starts. A new version downloads, installs and restarts by itself. If champion select is already open, it waits and shows an update bar instead.

## What it does and does not do

Draft Coach only reads champion select from your own client. It never clicks, picks or bans for you. Player and champion statistics come from OP.GG; champion art comes from Riot's Data Dragon.

Draft Coach isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
