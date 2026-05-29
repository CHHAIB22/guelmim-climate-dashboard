# 🌤️ Guelmim Climate Intelligence Dashboard

A responsive, dark-themed weather & solar intelligence dashboard built with **vanilla HTML/CSS/JS** and **Chart.js**, pulling real-time data from the [Open-Meteo API](https://open-meteo.com/).

> Designed for Guelmim, Morocco — ideal for solar energy analysis and PFE/research projects.

---

## ✨ Features

| Tab | Description |
|---|---|
| ⚡ **Énergie Solaire** | Live GHI, PV estimation, hourly irradiance chart, 7-day data table |
| 🌡️ **Atmosphère** | 16 atmospheric parameters (temp, humidity, dew point, pressure, wind, UV…) |
| 📅 **Prévisions** | 7-day forecast cards + Tmax/Tmin bar chart |
| 📆 **Climatologie** | Monthly averages (temp, GHI, wind) with switchable charts |
| 🕐 **Historique** | Today vs yesterday vs 7 days ago — line chart + detailed table |

---

## 🛠️ Tech Stack

- **HTML5 / CSS3** — glassmorphism UI, CSS variables, responsive grid
- **JavaScript (ES6+)** — async/await, fetch API, dynamic DOM
- **[Chart.js 4.4](https://www.chartjs.org/)** — line & bar charts
- **[Tabler Icons](https://tabler.io/icons)** — icon webfont
- **[Open-Meteo API](https://open-meteo.com/)** — free, no API key required
- **Google Fonts** — Outfit · Space Mono · Syne

---

## 🚀 Quick Start

```bash
# Clone the repo
git clone https://github.com/CHHAIB22/guelmim-climate-dashboard.git

# Open directly in browser — no build step needed
open index.html
```

Or deploy instantly with **GitHub Pages**:

1. Push `index.html` to your repo
2. Go to **Settings → Pages → Source → main / root**
3. Done ✅

---

## 📡 Data Sources

All data is fetched live from **Open-Meteo** (free, open-source weather API):

- **Current weather** — temperature, wind, radiation, UV, cloud cover
- **Hourly** — GHI, dew point, evapotranspiration, cloud layers
- **Daily** — Tmax, Tmin, sunshine duration, precipitation, wind max
- **Location** — Guelmim, Morocco (lat: 28.99°N, lon: -10.05°W)

---

## 📸 Preview


```
screenshots/dashboard-overview.png
```

---

## 📁 Project Structure

```
guelmim-climate-dashboard/
│
├── index.html          # Single-file app (HTML + CSS + JS)
└── README.md
```

---

## 🎯 Use Cases

- **PFE / Mémoire** — solar irradiance analysis for Guelmim region
- **PVsyst validation** — compare real GHI data vs simulation
- **Bi-axial tracker justification** — sunshine duration & irradiance trends
- **Agricultural monitoring** — ET₀ evapotranspiration, wind, precipitation

---

## 👨‍💻 Author

**Mohamed-Amine CHHAIB**  
Final-year DUT student — Énergies Renouvelables & Efficacité Énergétique  
École Supérieure de Technologie (EST) — Guelmim, Morocco  


[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/mohamed-amine-chhaib)
[![GitHub](https://img.shields.io/badge/GitHub-CHHAIB22-black?style=flat&logo=github)](https://github.com/CHHAIB22)

---

## 📄 License

MIT — free to use, adapt, and share with attribution.
