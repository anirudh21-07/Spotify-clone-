# 🎵 Spotify Web Player Clone

A **Spotify Web Player UI Clone** created using **HTML and CSS**. This project recreates the look and layout of Spotify's web player, including the sidebar, music library, playlists, music cards, navigation bar, and bottom music player.

> **Note:** This is a frontend UI project created for learning and practice. It does not connect to Spotify's actual music service.

## 🚀 Features

* 🎧 Spotify-inspired dark interface
* 🏠 Home and Search navigation
* 📚 Your Library section
* 🎵 Create playlist and podcast cards
* 🔥 Recently Played section
* 📈 Trending music section
* 🎶 Featured Charts section
* 🎼 Bottom music player
* ⏯️ Player controls
* 🔊 Volume control
* ❤️ Like/favorite icon
* 📱 Responsive layout for smaller screens
* 🎨 Font Awesome icons
* ✨ Google Fonts integration

## 🛠️ Technologies Used

* **HTML5** – Page structure
* **CSS3** – Styling and responsive layout
* **Font Awesome** – Icons
* **Google Fonts** – Montserrat font

## 📁 Project Structure

```text
Spotify-Clone/
│
├── index.html
├── styleS.css
├── README.md
│
└── spotify/
    ├── logo.png
    ├── library_icon.png
    ├── backward_icon.png
    ├── forward_icon.png
    ├── player_icon1.png
    ├── player_icon2.png
    ├── player_icon3.png
    ├── player_icon4.png
    ├── player_icon5.png
    ├── card1img.jpeg
    ├── card2img.jpeg
    ├── card3img.jpeg
    ├── card4img.jpeg
    ├── card5img.jpeg
    └── card6img.jpeg
```

## 🎨 Main Sections

### Sidebar

The sidebar contains:

* Home
* Search
* Your Library
* Create Playlist
* Browse Podcasts

### Main Content

The main area contains:

* Recently Played
* Trending Now Near You
* Featured Charts
* Music cards with images and descriptions

### Music Player

The bottom player contains:

* Album artwork
* Song title and artist
* Like button
* Playback controls
* Progress bar
* Microphone
* Queue/list controls
* Device control
* Volume control
* Full-screen control

## 📱 Responsive Design

The project uses a CSS media query:

```css
@media (max-width:1000px) {
    .hide {
        display:none;
    }
}
```

This hides selected navigation elements on smaller screens to make the interface more suitable for different screen sizes.

## ▶️ How to Run

No installation is required.

### Method 1 — Open directly

1. Download or clone this repository.
2. Open the project folder.
3. Make sure the `spotify` image folder is present.
4. Open `index.html` in your browser.

### Method 2 — VS Code

1. Open the project folder in **VS Code**.
2. Open `index.html`.
3. Right-click the file.
4. Select **Open with Live Server** if you have the Live Server extension installed.

## 🔮 Future Improvements

This project can be improved by adding:

* ▶️ Functional play/pause buttons
* 🎵 Actual audio playback
* 🔍 Working search functionality
* ❤️ Functional favorite button
* 📚 Dynamic playlists
* 🔊 Functional volume control
* ⏱️ Real-time song progress
* 🎶 Multiple songs
* 📱 Better mobile responsiveness
* 🌐 Spotify API integration

## ⚠️ Disclaimer

This project is a **Spotify-inspired educational frontend project** made for learning HTML and CSS. It is not affiliated with or endorsed by Spotify.


⭐ If you found this project useful, consider giving the repository a star!
