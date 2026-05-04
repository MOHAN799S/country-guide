# 🌍 Country Guide

A clean, interactive web app that lets users search for any country and instantly view key details — flag, capital, population, continent, currency, and timezone — all in a beautiful glassmorphism UI.

---

## 🚀 Live Demo

https://nationlens.netlify.app/

---

## 📸 Preview

<img width="1454" height="914" alt="Screenshot 2026-05-04 172701" src="https://github.com/user-attachments/assets/719a8a86-81f5-4a44-a715-a11fdc4f6bce" />


---

## ✨ Features

- 🔍 **Real-time country search** — just type a country name and hit search
- 🏳️ **Flag display** — fetches and renders the official country flag
- 📊 **Key country details** — capital, population, continent, currency & timezone
- ⏳ **Animated loader** — smooth loading state between searches
- ❌ **Error handling** — user-friendly messages for invalid or empty inputs
- 💎 **Glassmorphism UI** — modern frosted-glass aesthetic with hover effects
- ✍️ **Typewriter animation** — animated text effect using pure CSS

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | App structure |
| **CSS3** | Glassmorphism design, animations, responsive layout |
| **Vanilla JavaScript** | Async/Await API calls, DOM manipulation |
| **REST Countries API** | Country data source |
| **Google Fonts (Poppins)** | Typography |
| **Boxicons** | Search icon |

---

## 📡 API Used

[REST Countries API](https://restcountries.com/) — `https://restcountries.com/v3.1/name/{country}`

Data fetched per search:
- Country name & flag
- Capital city
- Population
- Continent
- Currency
- Timezone(s)

---

## 📁 Project Structure

```
country-guide/
│
├── index.html        # Main file (HTML + CSS + JS all-in-one)
└── README.md         # Project documentation
```

---

## ⚙️ How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/MOHAN799S/country-guide.git
   ```

2. **Navigate into the folder**
   ```bash
   cd country-guide
   ```

3. **Open in browser**
   ```bash
   open index.html
   # or just double-click the file
   ```

> No build tools, no dependencies, no npm install — just open and run! ✅

---

## 💡 Key Concepts Demonstrated

- **Fetch API** with `async/await` and Promise chaining
- **Error handling** with `.catch()` for network and input errors
- **DOM manipulation** — dynamic content updates without page reload
- **CSS animations** — keyframe-based loader and typewriter effects
- **Glassmorphism design** — backdrop blur, gradient overlays, and border effects
- **Responsive UX** — loading states and conditional rendering

---

## 🔮 Future Improvements

- [ ] Add search suggestions / autocomplete
- [ ] Show neighboring countries
- [ ] Add dark/light mode toggle
- [ ] Display languages spoken
- [ ] Make fully mobile responsive

---

## 👤 Author

**Mohan Lakshman Sangidi**
- GitHub: MOHAN799S(https://github.com/MOHAN799S)
- LinkedIn: Mohan Lakshman Sangidi
(https://www.linkedin.com/in/mohan-lakshman-sangidi-287322256/)


---

⭐ **If you found this project useful, consider giving it a star!**
