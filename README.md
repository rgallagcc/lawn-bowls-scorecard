# Lawn Bowls Scorecard 🏏

A lightweight, browser‑based lawn bowls scorecard and match tracker built with **HTML, CSS, and vanilla JavaScript**.  
Designed to run entirely on **GitHub Pages** with no backend or dependencies.

The app allows you to record lawn bowls matches, track **end‑by‑end scoring**, store **player roles**, add **match notes**, view **historical statistics**, and **import/export match data** for long‑term record keeping.

---

## ✨ Features

### Match Management
- Add new matches with date and team names
- Edit existing matches
- Store optional notes per match
- View full match history

### End‑by‑End Scoring
- Record scores for each end
- Unlimited number of ends per match
- Automatic total score calculation

### Player‑Level Information
- Capture player names for:
  - Lead
  - Second
  - Skip
- Stored per match for future analysis

### Statistics
- Automatic match result calculation
- Win / Loss / Draw counts
- Basic historical overview

### Filtering
- Filter matches by:
  - Team name (partial matches supported)
  - Date range

### Import / Export
- Export all match data as:
  - JSON (for re‑import and long‑term storage)
  - CSV (for Excel / LibreOffice analysis)
- Import previously exported JSON files

### Hosting & Persistence
- Fully client‑side
- Uses browser `localStorage`
- Works offline after first load
- No server or database required

---

## 🚀 Live Hosting (GitHub Pages)

1. Create a GitHub repository
2. Add `index.html` and this `README.md`
3. Go to **Settings → Pages**
4. Set source to:
   - Branch: `main`
   - Folder: `/root`
5. Your app will be available at:
