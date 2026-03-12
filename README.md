# 🎵 M3U Generator

A simple, fast, **browser-based playlist generator** for creating and editing `.m3u8` playlists.

Add songs manually, paste multiple URLs, or import an existing playlist to quickly build a clean playlist compatible with media players like **VLC, MPV, Kodi, and more**.

No installation. No backend. Everything runs **locally in your browser**.

---

## ✨ Features

### 🎧 Manual Song Entry

Add tracks individually with a **song name and URL**.

### 📋 Bulk URL Import

Paste multiple audio URLs (one per line) and generate playlist entries automatically.

### 📂 Playlist Import

Import existing **`.m3u` or `.m3u8` playlists** (similar to how VLC loads playlists).

The tool will automatically:

* parse the playlist
* extract song names
* rebuild the playlist structure

### 🧠 Smart Filename Parsing

Automatically converts filenames into readable track names.

Example:

```
my_song_name.mp3
```

becomes

```
My Song Name
```

### 🔗 URL Encoding

Handles:

* spaces
* special characters
* malformed URLs

### ⚡ Live Playlist Preview

Preview the generated playlist before downloading.

### ⬇ Export Playlist

Download a ready-to-use:

```
playlist.m3u8
```

---

## 🎼 Supported Audio Formats

The generator supports common audio file formats:

* MP3
* FLAC
* M4A
* OGG
* WAV
* AAC

---

## 📦 Example Playlist Output

```
#EXTM3U
#EXTINF:-1,Example Song
https://server/music/example.mp3
```

This playlist can be opened in:

* VLC
* MPV
* Kodi
* Jellyfin
* Plex
* any M3U compatible player

---

## 🚀 Usage

1. Open the HTML file in your browser
2. Add songs using one of the methods:

   * Manual entry
   * Bulk URL paste
   * Import an existing playlist
3. Preview the playlist
4. Click **Download playlist.m3u8**

Done.

---

## 🖥️ Running the Tool

No setup required.

Just open:

```
m3u-generator.html
```

in any modern browser.

---

## 🌐 Browser Compatibility

Works on all modern browsers:

* Chrome
* Firefox
* Edge
* Brave
* Chromium-based browsers

---

## 💡 Use Cases

Perfect for:

* personal music servers
* self-hosted audio collections
* streaming playlists
* quickly building playlists from URLs
* editing existing M3U playlists

---

## 📄 License

MIT License

