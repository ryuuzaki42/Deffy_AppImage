
# Deffy_AppImage

 - Deffy + Wine

Deffy converts DFF files (either containing DSD or DST) to DSF files or converts DSF files to DFF files

https://www.mymymyohmy.com/software/deffy.html

## Repository: https://github.com/ryuuzaki42/Deffy_AppImage
     Deffy: 6.0.0
---
### To change font size, change the DPI value in LogPixels
In the user.reg in `~/.config/Deffy_AppImage/user.reg`

At the end of block `[Control Panel\\Desktop]`

### Added LogPixels with desire value

#### To 100% text size
`"LogPixels"=dword:00000060`

#### To 125% text size
`"LogPixels"=dword:00000090`

#### To 150% text size
`"LogPixels"=dword:000000144`

---
https://www.mymymyohmy.com/software/deffy.html#download
