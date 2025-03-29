# Music Player

A beautiful, user-friendly and functional music player built with vanilla HTML, CSS, and JavaScript that allows users to upload and play local music files.

![Music Player Screenshot](/api/placeholder/400/320)

## Features

- **Local Music Upload**: Upload and play multiple audio files from your device
- **Elegant UI**: Clean and modern interface with gradient background
- **Playback Controls**: Play/pause, previous/next track functionality
- **Progress Tracking**: Interactive progress bar with time display
- **Volume Control**: Adjustable volume slider with mute option
- **Playlist Management**: Organized playlist that highlights the current track
- **Responsive Design**: Works well across different screen sizes

## Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No internet connection required for usage after initial page load

### Installation

1. Clone this repository or download the HTML file
   ```
   git clone https://github.com/yourusername/music-player.git
   ```
   
   Or simply download the `index.html` file directly

2. Open the HTML file in your web browser

### Usage

1. Click the "Upload Music" button in the top-right corner
2. Select one or multiple audio files from your device
3. Your songs will appear in the playlist at the bottom
4. Use the playback controls to manage your music:
   - Center button: Play/pause the current track
   - Left button: Go to previous track
   - Right button: Skip to next track
5. Adjust volume using the slider at the bottom
6. Click on any song in the playlist to play it immediately
7. Drag the progress bar to seek to different positions in the current track

## How It Works

The music player uses the browser's built-in Audio API to handle playback of local audio files. The key components include:

- **File Handling**: Uses the File API to read local audio files
- **Audio Playback**: Leverages the HTML5 `<audio>` element for playing music
- **UI Updates**: JavaScript event listeners update the interface in real-time
- **Local Storage**: Files are stored in memory using Object URLs (no server uploads)

## Customization

You can easily customize the player by modifying the CSS variables in the style section:

- Change the gradient background colors
- Adjust the sizes and spacing
- Modify the color scheme to match your preferences

## Browser Support

This music player works in all modern browsers that support HTML5 audio and the File API:

- Chrome 6+
- Firefox 3.6+
- Safari 6+
- Edge 12+
- Opera 11.5+

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- SVG icons based on Lucide icons (https://lucide.dev/)
- Inspired by modern music streaming interfaces

## Future Enhancements

- Add support for audio visualization
- Implement playlist saving between sessions
- Add shuffle and repeat functionality
- Create themes and color customization options
- Add keyboard shortcuts for playback control