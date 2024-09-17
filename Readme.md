# Spotify Clone

This is a Spotify clone built using **HTML**, **CSS**, and **JavaScript**. The application allows you to add and manage playlists by organizing songs into folders. It reads the playlist data dynamically from folders, making it easy to add new playlists without modifying the code.

## Here You Can Preview at [Click Here](https://myspotifyone.freewebhostmost.com/)

## Features

- Dynamic playlist generation based on folder structure.
- Easy to add new playlists by adding folders.
- Supports cover images and playlist details via JSON files.
- Responsive design using HTML and CSS.
- Song playback using JavaScript.


## Usage

### Adding a New Playlist

To add a new playlist to the Spotify clone:

1. **Create a new folder** inside the `songs/` directory. Name the folder based on the playlist name (e.g., `my-favorite-songs`).
2. **Add the following files** to the new folder:
   - `info.json`: This file contains information about the playlist in the following format:
     ```json
     {
       "title": "My Favorite Songs",
       "description": "A collection of my favorite songs for the summer."
     }
     ```
   - `cover.jpg`: The cover image for the playlist.
   - Add your song files (`.mp3`) to the folder.

3. The Spotify clone will automatically detect the new playlist and display it in the UI.

### Example Playlist Folder (`songs/my-favorite-songs/`):