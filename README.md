# twisted-tracks
Practice tracks for Twisted ensemble

## Song mixer layout

- `tracks.html` loads a song list from `songs/index.json`.
- Each song number has its own JSON config file in `songs/`.
- Track URLs inside each song config are resolved relative to that config file.
- Serve the folder over HTTP for the JSON fetches to work correctly.
