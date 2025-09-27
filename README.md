# SpotifyClone (Deezer API)

An iOS music app built with Swift 6 and SwiftUI.  
It lets you search for tracks, view artist/album info, and play 30-second previews from the Deezer API.

## Features
- **Search**: Search songs by artist name with live results.
- **Play music**: Stream 30s track previews using `AVPlayer`.
- **Track details**: Display song title, artist, album cover, and duration.
- **Play screen**: Includes play/pause, fake progress bar with slider, and basic controls (shuffle, repeat, skip UI).
- **Modern UI**: Spotify-style search bar, album artwork, and dark UI styling.
- **Architecture**: MVVM with async/await networking.

## Tech Stack
- Swift 6
- SwiftUI
- AVFoundation (music playback)
- Async/Await URLSession
- JSON decoding with Codable
- MVVM architecture

## API
This app uses the [Deezer public API](https://developers.deezer.com/api) for fetching track and artist data.

## Future Work
- Save liked songs with Core Data
- Add mini player at bottom
- Firebase login & user accounts
