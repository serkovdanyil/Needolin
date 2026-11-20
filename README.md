# Needolin

**Custom music replacement for Hollow Knight: Silksong**

Needolin lets you replace the game's music with your own tracks. Add your favorite music, create playlists, and customize playback to your liking.

## Features

- Replace the game's original music with custom tracks.
- WAV and MP3 audio support.
- Sequential and random playback modes.
- Shuffle playback without repeating tracks until the current cycle is complete.
- In-game mod configuration menu.
- Multiple interface languages.
- Configurable keyboard shortcuts.

## Installation

1. Make sure BepInEx 5 and the required dependencies are installed.
2. Place `Needolin.dll` in your `BepInEx/plugins` folder.
3. Launch the game once to let the mod create its folders.
4. Put your music files in:

   `BepInEx/plugins/Needolin/Tracks`

5. Restart the game, or refresh the track list through the mod menu if that option is available.

## Controls

Open the Needolin menu using its assigned hotkey. You can change the key in the mod configuration.

The menu lets you enable or disable music replacement, choose a playback mode, and manage your playlist.

## Supported formats

- `.mp3`
- `.wav`

For the smoothest playback, WAV files are recommended.

## Troubleshooting

**Music does not play**
- Make sure your files are in the `Tracks` folder.
- Check that the audio format is supported.
- Check the mod configuration and the BepInEx log for errors.

**MP3 playback stutters**
- Try using WAV files.
- Make sure you are running the latest version of Needolin.

**The mod does not appear**
- Make sure `Needolin.dll` is inside `BepInEx/plugins`.
- Check that BepInEx is installed and loading correctly.

## Credits

Thanks to everyone who tests Needolin and helps improve the mod!
