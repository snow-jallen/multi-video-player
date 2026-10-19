# Multi Video Player

Single-page app: open `index.html` in a browser, pick up to 9 video files, and they play side by side in a grid.

- **Play all / Pause all** (or Space) controls every video at once
- Hover a video for its own play/pause, seek, and volume
- Click a video to toggle its audio (selected = blue outline = audible); All audio / No audio buttons
- Hover a video and press **⤢** to make it primary: it takes the large center column and the rest move to the sides. Press **⤡** on it to return to the grid
- **Audio follows primary** (toolbar checkbox): making a video primary gives it the audio and mutes the rest
- **Sync** snaps all videos to the first video's timestamp if they drift
- Drag and drop files onto the page also works

No server or build step; files never leave your machine.
