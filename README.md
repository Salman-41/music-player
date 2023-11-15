# Music Player README

This is a simple music player project built with HTML, CSS, and JavaScript. It allows users to play and control music, displaying song information, progress bar, and duration. Here's a quick guide to understand and use the project:

## Project Structure

- **index.html**: Contains the structure of the web page.
- **style.css**: Defines the styles for the web page.
- **script.js**: Implements the functionality of the music player.

## Getting Started

1. Open the `index.html` file in a web browser.
2. The music player interface will be displayed with song details, controls, and a progress bar.

## Player Controls

- **Play/Pause Button**: Click the play/pause button (▶/❚❚) to start or pause the currently playing song.
- **Next/Previous Buttons**: Use the next and previous buttons (⏭/⏮) to navigate between songs.
- **Progress Bar**: Click on the progress bar to jump to a specific point in the song.

## Songs

The music player comes with a predefined list of songs. You can easily extend or modify the list by updating the `songs` array in the `script.js` file. Each song has a name, display name, and artist.

```javascript
const songs = [
  {
    name: 'jacinto-1',
    displayName: 'Electric Chill Machine',
    artist: 'Jacinto Design',
  },
  // Add more songs as needed
];
```

# Project Features

- **Play/Pause Functionality**: Click on the play/pause button to control the playback of the music.
- **Next/Previous Song**: Navigate between songs using the next and previous buttons.
- **Progress Bar**: Track the progress of the currently playing song with the progress bar.
- **Dynamic Song Loading**: Song information and audio source dynamically update when changing songs.

# How to Use

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Enjoy the music playback and experiment with the player controls.

Feel free to customize and enhance the project according to your preferences!
