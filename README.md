# Shelved 📚 — Personal & Shared Library Catalog

A lightweight, standalone web application in a single file (`index.html`) to organize, track, and read your personal and household book collection. Runs directly in any web browser with **zero build steps, zero node/npm dependencies, and full offline capability**.

---

## ✨ Features

- **"Old Library" Aesthetic**: Deep vintage palette (`#1D1617`, `#262630`, `#2A374D`, `#444A41`, `#9F6932`, `#522623`), classic literary typography, and warm shelf styling.
- **Instant Book Metadata Autocomplete**: Search by title, author, or ISBN via Google Books API, Open Library, and Wikipedia to auto-fill high-resolution covers, authors, publication year, publisher, detailed synopsis, page count, and granular BISAC genres.
- **Physical & Digital Multi-Format Tracking**: Support for *Physical*, *Digital*, *Physical & Digital* (dual-ownership), and *Audiobook* formats with direct links to cloud/eBook readers.
- **Built-in ePub Reader**: Open and read `.epub` eBook files directly in the browser with offline storage (IndexedDB), distraction-free typography, dark mode, and automatic reading progress tracking.
- **Multi-User Reader Profiles**: Switch between reader profiles directly from the header navbar. Each profile has isolated reading progress, page numbers, status, and favorites.
- **Custom Shelf & Room Locations**: Organize books across rooms, physical shelves, and digital clouds. Customize shelf icons, reorder shelves with drag & drop, and browse by location in the *Where to Find* view.
- **3 Dynamic View Modes**:
  - 🏛️ **Shelf View**: Elegant visual bookshelf covers with status badges.
  - 📜 **Detailed List View**: Rich cards with complete synopsis, ratings, and locations.
  - 📋 **Table View**: Compact, sortable spreadsheet-like table.
- **Advanced Search & Filtering**: Filter by format, reading status, categories, age group, and shelf locations.
- **Cloud & Multi-Device Sync (GitHub)**: Sync catalog changes live across all your phones, laptops, and tablets by configuring your GitHub repository and Personal Access Token in Settings ⚙️.
- **Companion Database File (`library-data.js`)**: Back up, download, or link your local database file directly for offline auto-saving.

---

## 🚀 How to Run Locally

Simply double-click **`index.html`** to open it in your favorite web browser (Chrome, Edge, Firefox, Safari). No web server or installation required.

---

## 🌐 Deploy to GitHub Pages

1. Push this repository to GitHub.
2. In your repository on GitHub, go to **Settings ⚙️** → **Pages**.
3. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` and `/ (root)`.
4. Your library catalog will be live at:
   `https://<your-username>.github.io/<repository-name>/`
