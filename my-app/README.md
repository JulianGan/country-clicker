# 🌍 Country Clicker

A fun and interactive web app that displays **all countries** with their flags!  
Click on any flag to **increment a counter** for that country.  
Track your favorites, run competitions, or just explore the world in a visual way.

## ⚡ Tech Stack

- [Vite](https://vitejs.dev/) – Lightning-fast frontend tooling
- [React](https://react.dev/) – Component-based UI library
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- Optional: [Tailwind CSS](https://tailwindcss.com/) for styling

---

## ✨ Features

- ✅ Displays all 254 countries and reserved codes (based on ISO 3166-1)
- 🏁 Flag icons shown using each country's Alpha-2 code
- 🖱️ Clicking a flag increments a counter
- 🔍 Search and filter countries (optional extension)

---

## 📦 Installation

```bash
git clone https://github.com/your-username/country-clicker.git
cd country-clicker
npm install
npm run dev
```

Then open `http://localhost:5173` in your browser.

---

## 📁 Project Structure

```
├── public/
│   └── flags/             # Flag images (e.g., US.png, FR.png)
├── src/
│   ├── components/        # React components like CountryCard
│   ├── data/              # List of countries with Alpha-2 codes
│   ├── App.jsx            # Main application component
│   └── main.jsx           # Vite entry point
├── index.html
├── package.json
└── README.md
```

---

## 🗺️ Data Source

- Country names and Alpha-2 codes: [ISO 3166-1](https://www.iso.org/iso-3166-country-codes.html)
- Flags: [flagcdn.com](https://flagcdn.com/) or hosted locally

---

## 🚀 Deployment

Easily deploy using:

- **[Vercel](https://vercel.com/)** 
- **[Netlify](https://www.netlify.com/)** 
- **GitHub Pages** (with Vite’s base path config)

---

## 🤝 Contributing

Want to improve this project?  
Issues and pull requests are welcome. Feel free to add features like:

- Country search/filter
- Persistent counters per user (backend or cloud sync)
- Leaderboards

---

## 📄 License

MIT License © 2025 Your Name
