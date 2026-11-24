# My Dear Queen Tazmim — assets.json version

Upload these files to the root of a PUBLIC GitHub repository:

```text
index.html
assets.json
assets/
  romantic-red-background.png
My Pictures/
  Tazmim.jpg
  Picture2.jpg
My Songs/
  Song1.mp3
  Song2.mp3
```

Edit `assets.json` whenever you add/remove media. Paths are relative to the repository root and must match exact file names and capitalization. List all pictures in `pictures` and all audio files in `songs`. The page displays eight mystery slots at a time.

Example:
```json
{
  "pictures": ["My Pictures/Tazmim.jpg", "My Pictures/Picture2.jpg"],
  "songs": ["My Songs/Song1.mp3", "My Songs/Song2.mp3"]
}
```

Publish with GitHub Pages: Repository → Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.

Supported pictures: JPG, JPEG, PNG, WEBP, GIF. Supported audio: MP3, OGG, WAV, M4A. Browsers may require a tap on Play before audio starts.
