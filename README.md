# Creating-GIF-with-Python
A small script that combines a sequence of images into an animated GIF using `imageio`.

## What it does
`projects.py` reads `pic1.jpg` and `pic2.jpg` and stitches them together into an animated GIF (`team.gif`), with each frame shown for 500ms, looping forever.

## Requirements
```bash
pip install imageio
```
## Usage
1. Place your source images in the project folder (update the `filenames` list in `projects.py` to match your image names).
2. Run the script:
```bash
python projects.py
```
3. The output `team.gif` will be created in the same folder.

## Files
- `projects.py` — the GIF-generation script
- `pic1.jpg`, `pic2.jpg` — sample source images
- `team.gif` — generated output (not committed; see `.gitignore`)
