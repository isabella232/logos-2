# DMG Background

Create a DMG background with retina support:

1. Export two `.png` images at `540x380` and `1080x760`
2. Create a combined image by running 
```bash
tiffutil -cathidpicheck background.png background@2x.png -out background.tiff
```
