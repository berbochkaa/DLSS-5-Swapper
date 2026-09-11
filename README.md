<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/e1d2b624-bfbd-438a-8905-f720d5dbea5f" />|
DLSS 5 Swapper
Install and manage DLSS 5 Neural Rendering for compatible games and emulators.
Download
Windows Installer · Portable · Checksums

Both are on the latest release page, with SHA256SUMS.txt beside them.
<img width="1598" height="1130" alt="image" src="https://github.com/user-attachments/assets/8f285140-9034-43ed-b152-232077a63919" />
Features
Easy installation: native DLSS games, or compatible non-DLSS games through DLSS5-Feeder.
Your library: Steam, Epic, GOG, modern Xbox Game Pass folders, and manually added games/emulators.
Search and filters: combine title, graphics API, DLSS status/version and add-ons; click counters to filter.
Flexible layout: group by store or show everything in one list, with game artwork and light/dark themes.
Controlled scanning: full-drive scanning is off by default. Added folders still scan normally; enable all-drive discovery or remove scan folders in Settings.
Right-click shortcuts: open/copy folder, rescan, change cover, restore originals or hide a game.
Backups and History: restore original files, keep installation records, and copy History/activity/install logs.
Save diagnostics: one file with the install log, the game’s own ReShade and Feeder logs, the manifest and your driver - shown to you before it is written, and ready to attach to a report.
In-game overlay: press F8 to open the app's own panel over the running game and move the real DLSS Neural Rendering sliders while you play. Supports the DLSS5-Feeder and RenoDX v4.7 routes only. Drag the grip in its bottom right corner to resize it; each game remembers its own size.
Rendering API override: optional, per game, with Automatic as the default; detection is never overwritten.
Custom add-ons: the Add-ons page remains available alongside the integrated installation routes.
Multipass neural rendering: an installation route that runs the neural pass up to ten times per frame, on DX12, DX11 and 64-bit DX9 - including games with no DLSS of their own.
Community (BETA): read what worked for other people on the games you own, leave your own report, and talk it over underneath it. Opt-in, and everything you leave can be edited, deleted or withdrawn.
Community chat: one live room for everyone using the app - screenshots, game cards, replies with mentions and reactions.
New in 2.2.6
Community chat, and the fault 2.2.5 shipped in every native install - fixed at the cause.

💬 Community chat
One live room for everyone using the app, on its own page under Games.

Screenshots in the conversation. Paste, drop or pick up to four images. They are compressed on your machine before they leave it, and they expire after 24 hours. Tag one DLSS 5 ON or DLSS 5 OFF and a comparison reads without explaining it.
Game cards. Attach any game from the Community page: its result and its report count travel with the message, and a click opens its reports in place.
Replies with mentions, reactions, and your own messages to edit or delete. Any image can be saved to disk.
Live. New messages arrive while you read, an unread count waits on the sidebar while you are elsewhere, and a half-written message survives leaving the page.
It uses the community name you chose in Settings.

And four things that were wrong
Native DLSS (RenoDX) installed the multipass consumer	The native route's add-on was picked as "the first .addon64 in the folder", and once the multipass build shipped beside the ordinary one it sorted first. It is chosen by name now, in the app and in the build
Two RenoDX consumers could sit side by side	Both register as "RenoDX DLSS"; ReShade keeps whichever loads first and drops the other, so the route you picked stopped deciding what ran. An install now moves any other renodx-dlss* add-on beside the game into the backup, and Restore originals puts yours back exactly
A hidden switch could pick multipass on the Feeder route	Left over from development, with no way to see it or turn it off. It is gone: multipass comes only from its own route
Community dropdowns were white on white	In the dark theme the option lists drew white text on a white popup. Every dropdown now takes a solid colour from the theme
Installed a game on Native DLSS with 2.2.5? Press Install again on the same route and the wrong file is replaced, or Restore originals to undo it entirely.

Full 2.2.6 notes →

Earlier releases
Each one is written up in full - what broke, why, and what was changed.

2.2.5	Multipass - the neural pass up to ten times per frame, plus nine faults fixed at the cause
2.2.4	The Community page - compare notes with everyone else, plus eight faults fixed at the cause
2.2.3	Six reported faults, fixed at the cause - OptiScaler on older cards, a game's own stale shader compiler, the overlay on a scaled display
2.2.2	The reports people sent - games it could not find, installs it refused, the overlay's own page
2.2.1	The Overlay page - themes you can write yourself, and a preview that runs before you choose
2.2.0	Optional OptiScaler and a smarter library
Every release also carries its own notes and downloads on the releases page.

Compatibility
Category	Support
System	Windows 10/11 x64; compatible 32-bit and 64-bit games
ReShade / Feeder GPUs	RTX 20 / 30 / 40 / 50; older-series support is reported by the bundled modified runtime's author
OptiScaler GPUs	64-bit games with native DLSS enabled. The bundled neural model runs on Blackwell (RTX 50 / RTX PRO Blackwell); an older card needs a modded nvngx_dlssnr.dll you supply, which is never overwritten. Driver 616.56 recommended
DirectX 12	Native DLSS, Feeder, or eligible OptiScaler games
DirectX 11	Feeder for 32/64-bit games; eligible OptiScaler games
DirectX 9 / 8	DX9: 32/64-bit; DX8: 32-bit, through dgVoodoo2 → DX11 → Feeder
Vulkan / OpenGL	ReShade/Feeder; eligible Vulkan games can also use OptiScaler
DirectX 10	Not directly supported by Feeder; choose DX11 when available
In-game overlay	64-bit DirectX 11 / 12 games with ReShade add-on support; DLSS5-Feeder and RenoDX v4.7 only
OptiScaler's DX11/Vulkan path uses a DX12 bridge with FSR output by default. For Vulkan backend changes, restore originals first. OptiScaler is not the emulator/non-DLSS route.

Emulators
Select the emulator folder and its active renderer, then use ReShade/Feeder.

Emulators
DuckStation	PCSX2	RPCS3
Dolphin	PPSSPP	Xenia
Cemu	Ryujinx	yuzu / suyu / Eden / Citron / Sudachi
shadPS4	Azahar / Citra / Lime3DS	melonDS
Flycast	xemu	Vita3K
RetroArch	mGBA	Snes9x
Play!		
Compatibility varies by renderer and game. Xenia HUD correction remains experimental.

38 languages
All 38 languages
English	العربية	简体中文	繁體中文
Español	Português	Русский	Deutsch
Français	日本語	한국어	Italiano
Türkçe	Polski	Українська	Nederlands
Čeština	Magyar	Română	Ελληνικά
Svenska	Dansk	Norsk	Suomi
ไทย	Tiếng Việt	Bahasa Indonesia	Bahasa Melayu
Filipino	हिन्दी	বাংলা	فارسی
اردو	Български	Српски	Hrvatski
Slovenčina	Català		
Arabic, Persian and Urdu support right-to-left layout.

Screenshots

<img width="1617" height="1220" alt="image" src="https://github.com/user-attachments/assets/0ddc7aa4-16d3-42aa-b808-eab9e675c522" />
<img width="1595" height="1132" alt="image" src="https://github.com/user-attachments/assets/3f98481b-1b79-4fc3-acb1-ee3d7c8b96f2" />
<img width="1678" height="1334" alt="image" src="https://github.com/user-attachments/assets/55346f1f-4077-4a00-bfca-9b0e6e8a825d" />
<img width="1600" height="1392" alt="image" src="https://github.com/user-attachments/assets/2db4babc-568f-4598-918a-fa50645196a4" />
Before installing
Anti-cheat: red warning and optional confirmation, not a blanket block. Injection can cause crashes or account bans; the app never bypasses anti-cheat.
Requirements: Feeder needs Visual C++ runtimes (x64, plus x86 for 32-bit games). Some components download on first use.
Compatibility is not guaranteed. Keep backups; existing mods may conflict. Not every reported game crash is fixed.
Linux/Proton: experimental community source only; no Linux binaries in this release.
Community and privacy
Opening the Community page downloads public game reports. A live connection count is held only in memory; no connection identifiers are stored.
A report is sent only after you review and submit the fields shown in its dialog: game, route, rendering API, result, optional comment, GPU, driver, CPU, OS and app version.
The app uses a random install ID to prevent duplicate votes. The server stores only its hash. Remove my community activity hides all your reports and replies and resets your public community profile.
The owner-only administrator access code is verified by the community server and stored locally with Windows encrypted storage. It is never written to the public profile or the normal community settings file.




