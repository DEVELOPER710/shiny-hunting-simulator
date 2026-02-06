
# ✨ Shiny Hunting Simulator ✨

A simple, web-based **Pokémon Shiny Hunting Simulator** inspired by in-game encounters.
Built to be lightweight, mobile-friendly, and easy to host on **GitHub Pages**.

---

## 🎮 Features

- Hunt **all non-legendary Pokémon from Generation 1–5**
- Manual Pokémon name input with validation
- Encounter batches:
  - 1 / 2 / 3 / 5 encounters per click
- Default shiny odds: **1 / 30,000** per Pokémon
- ✨ **Sparkle animation for shiny Pokémon only**
- Persistent progress using `localStorage`:
  - Encounters since last shiny
  - Lifetime total encounters
  - Shiny history (with encounters count)
- Mobile-friendly responsive layout
- No audio, no external frameworks

---

## 🕹️ How to Use

1. Enter a Pokémon name (official Pokédex spelling)
2. Click **Start** to begin the hunt
3. Click **Next** to repeat encounters
4. A shiny will automatically:
   - Show sparkle animation
   - Reset the counter
   - Be logged in shiny history

All progress is saved automatically — refreshing the page will **not** reset data.

---

## 📦 Files

- `index.html` – Main simulator (HTML, CSS, JS in one file)
- `README.md` – Project documentation

---

## 🧠 Data Source

- Pokémon sprites & data fetched from **PokéAPI**
- Sprites used:
  - `front_default`
  - `front_shiny`

---

## 👤 Credits

**By DEVELOPER710**

Pokémon © Nintendo / Game Freak  
This project is for educational and fan-use only.

---

✨ Happy shiny hunting!
