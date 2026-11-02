# GWEN™

**Gaming World Entertainment Network — by Tenten1824.**

A Windows interface for PlayStation and Xbox Remote Play, Cloud Play,
controller support and Multi-view.

## Download

[Official downloads and release notes](https://github.com/Tenten1824/GWEN/releases/latest)

- New installation: **GWEN-Setup-1.19.23-Windows-x64.exe**.
- Read **HOW TO USE.txt** for setup, pairing, controller buttons and keyboard shortcuts.
- Existing Public installation: use **Settings → App updates → Check online now**.
  Download, confirm preparation, then restart when playback has stopped.
  Public and Developer update channels stay separate.

## What you need

Windows 10/11 x64, your own controller, and either your own supported console
or eligible provider account/service access. Start PS5 pairing on the same home
network. Cloud access depends on provider entitlement and availability; GWEN™
does not unlock paid games or bypass region restrictions. Embedded provider
pages require Microsoft Edge WebView2 Runtime.

PlayStation Remote Play and native Cloud controls reuse the existing streaming
engines. Xbox uses the embedded Microsoft experience; Xbox console gameplay and
every hardware/network combination have not been independently verified here.

## Quick controls

| Action | Keyboard / mouse | PlayStation | Xbox |
| --- | --- | --- | --- |
| Navigate native menus | Tab / arrow keys on focused controls | D-pad / left stick | D-pad / left stick |
| Select | Enter / Space on a focused button | Cross | A |
| Back | Esc in supported dialogs | Circle | B |
| Main tabs | Click tab | L1 / R1 | LB / RB |
| Native gameplay menu | — | Hold L3 + R3 for 0.7 seconds | Hold LS + RS for 0.7 seconds |
| Record supported native source | Ctrl + R | L2 + R3 | LT + RS |
| Native picture fullscreen | Double-click / F11; Esc to leave | Use fullscreen control | Use fullscreen control |

Click GWEN™ to focus it. Release both recording-chord buttons before repeating.
Native shortcuts do not override sign-in dialogs or embedded provider controls.

## Credits, licenses and source

Developed by **Tenten1824**, with development assistance from **OpenAI Codex**.
See [CREDITS.txt](CREDITS.txt) for upstream authors and acknowledgements.

The custom application/launcher retains its existing **AGPL-3.0-only** license.
Third-party components retain their own licenses, including PyQt GPL terms.
The release includes **GWEN-Public-1.19.23-Full-Source.zip**, build materials,
dependency notices and component source material. Do not treat GitHub's
automatically generated repository ZIP as a replacement for that source archive.
Product imagery and trademarks retain their owners' rights and are separate
from the software license. No Sony/Microsoft affiliation or endorsement is claimed.

## Verification and support

The desktop baseline passed 40 regression tests and four Public-channel checks.
The installer was checked in an isolated folder for install/startup/reinstall,
saved-data retention and uninstall. New live PS5, Cloud, Xbox and controller
hardware acceptance was not performed for this Public promotion.

The Windows installer is not Authenticode-signed. Official update feeds/packages
are signed separately and verified by GWEN™. Compare release SHA256SUMS.txt
when manually checking downloads.

For a problem: **Settings → Diagnostics → Save support report** while it happens,
before disconnecting if possible. Review the ZIP before sharing it. Never post
passwords, sign-in tokens or private pairing data.
