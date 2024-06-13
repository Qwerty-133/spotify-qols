<!-- markdownlint-disable-next-line first-line-heading -->
<div align="center">
  <h1>Spotify QoLs</h1>
  A collection of various Spicetify extensions to improve your Spotify experience.
</div>

<br>
<p align="center">
  <a href="LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/Qwerty-133/spotify-qols">
  </a>
  <a href="commits">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Qwerty-133/spotify-qols">
  </a>
</p>

This is a mono-repository for Spicetify extensions written by me.

> :warning: Spicetify frequently updates, some of these scripts may not be up-to-date.

## Demonstration

![Track Explorer Usage](assets/demos/Track%20Explorer%20Demo.gif)
![Track Explorer Settings](assets/demos/Track%20Explorer%20Settings.png)

## Extension List

### Track Explorer

This extension allows you to discover new music by skipping songs you've already listened to. If the discovery mode is enabled and you've listened to a song for more than 30 seconds, the song will be skipped the next time it is played automatically.

The track isn't skipped if the user has manually played the track (by double clicking it).

**Features**:

- Enable/disable discovery mode by pressing the magnifier icon in the player or by using the shortcut.
- The shortcut may be changed in the settings menu accessible from Profile > Track Explorer > Shortcuts
- The remembered tracks can be reset from the settings menu.
- Remembered tracks can also be exported or imported from the settings menu.

## Installation

Install [Spicetify](https://spicetify.app/docs/advanced-usage/installation/) if not already installed.
After installation, follow these steps:

1. Copy the code from the extension you want to install.
2. Open Spicetify's config directory by running `spicetify -c`.
3. Open the `Extensions` folder.
4. Create a new file with the name of the extension you want to install. Example: `TrackExplorer.js`.
5. Paste the code into the file.
6. Save the file.
7. Run `spicetify config extensions extension-name.js` to enable the extension.
8. Apply changes by running `spicetify apply`.
