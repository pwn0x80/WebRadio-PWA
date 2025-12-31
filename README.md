# 🌸 WebRadio-PWA 🎶

Welcome to **WebRadio-PWA** — your cheerful little companion for discovering and streaming online radio stations! 💖  
Bookmark your favorites, enjoy smooth playback, and explore endless tunes with a playful and colorful interface. 🐰✨

---

## 🎀 Features

- 🎵 Instantly stream online radio stations
- 🌈 Browse by genres or search your favorite stations
- 🐹 Bookmark stations for easy access
- 💕 Colorful and responsive UI
- 🌸 Works perfectly on mobile & desktop
- 🛡️ Offline support (PWA ready!)
- 🐰 Fun animations and interactive audio controls

---
## 📂 Project Structure

.
├── backend
│   ├── controllers
│   │   └── radioController.js
│   ├── index.js
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
│   ├── routes
│   │   └── radioList.route.js
│   ├── services
│   │   └── radio.js
│   └── test
│       └── radio.test.js
└── frontend
    ├── package.json
    ├── package-lock.json
    ├── public
    │   ├── favicon.ico
    │   ├── index.html
    │   ├── lofi.json
    │   ├── logo192.png
    │   ├── logo512.png
    │   ├── manifest.json
    │   └── robots.txt
    ├── README.md
    └── src
        ├── App.js
        ├── assets
        │   ├── gif
        │   │   └── musicGif.gif
        │   └── svg
        │       ├── addbookmark.svg
        │       ├── Bookmark.jsx
        │       ├── bookmark.svg
        │       ├── button2.svg
        │       ├── button.svg
        │       ├── genres.svg
        │       ├── home.svg
        │       ├── next.svg
        │       ├── prev.svg
        │       └── volume.svg
        ├── components
        │   ├── bottomBar
        │   │   ├── BottomBar.jsx
        │   │   └── BottomBar.styles.js
        │   ├── contentWrapper
        │   │   ├── ContentWrapper.jsx
        │   │   └── ContentWrapper.styles.jsx
        │   ├── controller
        │   │   ├── Controller.jsx
        │   │   └── Controller.styles.jsx
        │   └── popUpBox
        │       ├── PopUpBox.js
        │       └── PopUpBox.styles.js
        ├── index.css
        ├── index.js
        ├── page
        │   ├── Bookmarklist
        │   │   └── BookMarklist.jsx
        │   ├── contentBox
        │   │   └── ContentBox.jsx
        │   ├── Genres
        │   │   └── GenresList.jsx
        │   ├── Home
        │   │   ├── Home.jsx
        │   │   └── Home.style.jsx
        │   ├── HomeContentBox
        │   │   └── HomeContentBox.jsx
        │   ├── Search
        │   │   └── Search.jsx
        │   └── SearchBar
        │       └── SearchBar.jsx
        ├── README.md
        ├── redux
        │   ├── radioSlice.js
        │   ├── store.js
        │   └── urlUpdate.js
        ├── services
        │   ├── indexedDB.js
        │   └── radioListServices.js
        └── utils
            ├── index.js
            ├── useAudioController.jsx
            ├── useGreeting.jsx
            └── useScrollFetch.jsx

28 directories, 58 files



- **backend**: Handles API requests, communicates with radio-browser APIs, and serves data to the frontend.
- **frontend**: React-based client with features like infinite scroll, bookmarks, and audio controls.
- **redux**: State management for radio stations, bookmarks, and playback controls.
- **services**: Encapsulates API calls and IndexedDB interactions.
- **components**: Reusable UI components such as player, controllers, and popups.

---

## 🛠️ Technologies Used

- **Frontend**: React, Redux Toolkit, Styled Components, Lottie Animations
- **Backend**: Node.js, Express.js, radio-browser API
- **Testing**: Mocha, Chai, Supertest
- **PWA**: Manifest & service worker enabled

---

## 🚀 Getting Started

### Backend

1. Navigate to the backend folder:
   ```bash
   cd backend


## 📌 Usage

- Open the frontend in a browser.

- Browse radio stations by genre or search for a specific station.

- Click on a station to start playing.

- Use the bottom audio controller to manage playback.

- Add stations to bookmarks for easy access.

## 📂 Folder Highlights

-- backend/controllers: Contains all API controllers.

-- backend/routes: Defines API endpoints.

-- frontend/src/components: Reusable UI components like BottomBar, Controller, PopUpBox.

-- frontend/src/page: Page-level components (Home, Search, Genres, BookmarkList).

-- frontend/src/redux: Redux slices and store configuration.

-- frontend/src/services: API calls and IndexedDB services.
