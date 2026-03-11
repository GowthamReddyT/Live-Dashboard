# 🌍 Live Dashboard — Real-Time Environmental Data

A lightweight, browser-based **Real-Time Environmental Data Dashboard** that visualizes live air quality and weather metrics using interactive line charts. Built with pure **HTML**, **CSS**, and **Chart.js** — no frameworks, no backend required.

---

## 📊 Features

- 📡 **Real-time data simulation** — Charts update automatically every hour
- 📈 **6 live metrics tracked:**
  - PM2.5 Levels (Fine Particulate Matter)
  - PM10 Levels (Coarse Particulate Matter)
  - Ozone (O₃) Levels
  - Humidity Levels
  - Temperature Levels
  - CO (Carbon Monoxide) Levels
- 🎨 Responsive grid layout with clean, modern styling
- ⚡ Powered by [Chart.js](https://www.chartjs.org/) via CDN — zero install needed

---

## 🗂️ Project Structure

```
Live-Dashboard/
├── index.html      # Main dashboard UI & chart logic
└── styles.css      # Styling and responsive layout
```

---

## 🚀 Getting Started

### Prerequisites

No installation required! Just a modern web browser.

### Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/GowthamReddyT/Live-Dashboard.git
   ```

2. **Navigate to the project folder:**
   ```bash
   cd Live-Dashboard
   ```

3. **Open in your browser:**
   ```bash
   open index.html
   ```
   Or simply double-click `index.html` to open it in your default browser.

---

## 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure & layout |
| CSS3 | Styling & responsive grid |
| [Chart.js](https://www.chartjs.org/) | Interactive line charts |

---

## 📷 Dashboard Overview

The dashboard displays **6 real-time line charts** in a responsive grid:

| Metric | Unit | Range |
|--------|------|-------|
| PM2.5 | µg/m³ | 0 – 50 |
| PM10 | µg/m³ | 0 – 80 |
| Ozone | ppb | 0 – 100 |
| Humidity | % | 0 – 100 |
| Temperature | °C | 0 – 40 |
| CO | ppm | 0 – 10 |

Charts are updated every **60 minutes** and show data for the last **3 hourly intervals**.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**GowthamReddyT**  
GitHub: [@GowthamReddyT](https://github.com/GowthamReddyT)