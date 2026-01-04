## Rishikesh Expedition 2026 – Itinerary Site

A single-page, mobile‑responsive itinerary website for a **3‑day Rishikesh trip** (Feb 15–17, 2026), themed in **peach, cream, and mint** for a calm, aesthetic feel. Designed to be easily shared with friends or exported as a PDF.

***

## ✨ Features

- **Single HTML file**  
  No build tools, no dependencies – just open `index.html` in any browser.

- **Mobile‑first, responsive layout**  
  Works smoothly on phones, tablets, and desktops using pure CSS media queries.

- **Soft color palette**  
  Peach, cream, orange, and light green for a relaxed visual mood.

- **Clear, structured itinerary**
  - Trip overview cards (duration, group size, stay, budget)
  - Day‑by‑day tables for all three days
  - Cost breakdown (stay, travel, food, activities)
  - Pre‑trip checklist and packing tips

- **Café & activity guide with links**  
  Hyperlinked cafés, Ganga Aarti, Beatles Ashram, bridges, and stay information (Google Maps + context pages).

- **High‑quality imagery**  
  Curated hero images (Ganga Aarti style shot, bridges, cafés, art) for a polished look.

***

## 📁 Project Structure

```text
.
└── index.html   # Self-contained page with HTML + CSS
```

All fonts are loaded via Google Fonts, and images are pulled from high‑quality photo CDNs (e.g., Pexels/Unsplash‑style links). No external JS or CSS files are required.

***

## 🚀 Getting Started

### Option 1 – Open locally

1. Clone or download this repository.
2. Open `index.html` in your browser:
   - Double‑click `index.html`, _or_
   - Right‑click → “Open With…” → your browser of choice.

### Option 2 – Deploy on GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under “Source”, choose the `main` (or `master`) branch and `/root`.
4. Save – GitHub will give you a public URL for sharing.

***

## 🧩 Customization

You can easily adapt this for other trips:

- **Dates & location**  
  Edit the header section (`<header class="header">`) to change the trip name, dates, and tagline.

- **Colors**  
  Adjust the palette in the `:root` block near the top of the `<style>` tag:
  ```css
  :root {
    --bg-gradient: linear-gradient(135deg, #ffe4d6 0%, #fff7ec 40%, #e4ffe9 100%);
    --accent-peach: #ffb999;
    --accent-mint: #b9f2c8;
    /* … */
  }
  ```

- **Itinerary & costs**  
  Modify the tables in the **Day‑by‑Day** and **Budget** sections to match new activities or prices.

- **Links & maps**  
  Swap Google Maps URLs and external links for your own cafés, hotels, or activities.

***

## 📄 Converting to PDF

For sharing with your group as a document:

1. Open `index.html` in your browser.
2. Print (Ctrl/Cmd + P).
3. Destination → “Save as PDF”.
4. Set:
   - Margins: `Default` or `None` (depending on your taste)
   - Background graphics: **enabled** (to keep colors)
5. Save as e.g. `Rishikesh_Expedition_2026.pdf`.

***

## 📝 License

You’re free to **clone, modify, and reuse** this layout for personal or educational projects. If you adapt it significantly, consider mentioning the original inspiration in your README so others can trace the design lineage.
