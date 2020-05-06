# 🎧 `voxctl`
`voxctl` is a command line tool for controlling the [VOX](https://vox.rocks)
music player from the terminal.

Under the hood, it works by proxying calls to [VOX](https://vox.rocks) using
[JavaScript for
Automation](https://developer.apple.com/library/archive/releasenotes/InterapplicationCommunication/RN-JavaScriptForAutomation/Articles/Introduction.html)
which was introduced in Mac OS X Yosemite. `voxctl` currently supports all
commands from the [VOX](https://vox.rocks) scripting suite.

## Requirements
* macOS 10.10 or newer.

## Installation
TBD.

## Usage
```
Usage:
  $ voxctl [command]

Commands:
  start               # Starts VOX
  quit                # Quits VOX
  play                # Begins playback
  pause               # Pauses playback
  togglePlay          # Toggles playback between playing and paused 
  next                # Skips to the next track in the playlist
  previous            # Skips to the previous track in the playlist
  shuffle             # Toggles shuffle on or off
  playUrl URL         # Plays the specified URL
  addUrl URL          # Adds the specified URL to the playlist
  rewindForward       # Rewinds the current track forward
  rewindForwardFast   # Rewinds the current track forward fast
  rewindBackward      # Rewinds the current track backward
  rewindBackwardFast  # Rewinds the current track backward fast
  increaseVolume      # Increases the volume
  decreaseVolume      # Decreases the volume
  togglePlaylist      # Shows/hides the playlist
  info                # Displays information about the current track in JSON
  isRunning           # Prints true if VOX is open, otherwise false
  help                # Prints this information
```

## License
See [LICENSE](https://github.com/majjoha/voxctl/blob/master/LICENSE).
