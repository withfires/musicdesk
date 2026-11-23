# MusicDesk

Music apps for Windows 10 and 11. Download them from the [latest release](../../releases/latest).

**Website:** https://musicdeskforpc.netlify.app/

| App | What it is | Download |
| --- | --- | --- |
| **MusicDesk** 1.0.0 | Full desktop skin: big glowing clock, now-playing bar, artist search with top songs and previews, and a settings window for colours, size and layout. | `MusicDesk-1.0.0.zip` |
| **Music Widget Tiny** 2.0.0 | Small floating player in Card or Bar style, with lots of style options, an optional desktop clock and search on 9 platforms. | `MusicWidgetTiny-2.0.0.zip` |

This repository only hosts official releases. The source code is not public.

## Verify your download

Only download these apps from this page. To check your copy is the official file, run this in PowerShell (use the name of the zip you downloaded):

```powershell
Get-FileHash "$env:USERPROFILE\Downloads\MusicDesk-1.0.0.zip" -Algorithm SHA256
```

The hash must match:

```
f0ed9494bc0c2daee06ba7c8b0897f551a3edb0d450c4d2c736b98e7d8b03bef  MusicDesk-1.0.0.zip
1196352dc326323f657e4923253fe5d780f6293a24d2db2ace84d75bf1144957  MusicWidgetTiny-2.0.0.zip
```

## Install

1. Unzip the download and open `MusicDesk.exe` or `MusicWidget.exe`.
2. If Windows asks for the .NET 9 Desktop Runtime, install it from the link it shows (free, from Microsoft).
3. If Windows shows "Windows protected your PC", click **More info** → **Run anyway**.

## License

© 2026 MusicDesk. All rights reserved. Free for personal use. Redistribution, resale, modification and reverse engineering are not permitted. See [LICENSE.txt](LICENSE.txt).
