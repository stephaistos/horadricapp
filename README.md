# Small companion tool for Diablo 2 : Resurrected

## Features:
- save a cropped screenshot around item stats
- item stats to text file
- item stats checked against a picklist to get an idea of value/use
- pixel based - No memory access
- configuration by config.ini file
- tray icon application, use via configurable hotkey
- extremely accurate tesseract traineddata

## Requirements, known issues/limitations:
- Large Font Mode MUST be enable in game settings (it changes overlay settings and make it easier to detect stats)
- OCR in english language only
- openCV and tesseract must be installed or libraries copied in tool directory, full dependencies list:
gif.dll
jpeg62.dll
leptonica-1.81.1.dll
libpng16.dll
libwebpmux.dll
lzma.dll
opencv_world454.dll
tesseract41.dll
tiff.dll
webp.dll
zlib1.dll
- OCR might not work properly when the item overlay pops over dark textures (equipped inventory seems to be the worse)
- tested resolutions 720p, 1080p, 1440p. 1920x1080 recommended. Fancy ratios are likely to get terrible results.
- picklist needs to be tuned
- some affixes are not split in properties.csv (on-hit skills,
