# 🚀 Crypto Dashboard

A modern and responsive cryptocurrency dashboard built with **React**, **Tailwind CSS**, **Recharts**, and the **CoinGecko API**. The application provides real-time cryptocurrency market data, interactive price charts, search functionality, and dark/light mode support.

## 📌 Features

- 📈 Real-time cryptocurrency market data
- 🔍 Search cryptocurrencies by name
- 🌙 Dark Mode / ☀️ Light Mode toggle
- 📊 Interactive 7-day price trend charts
- 💰 Current Price display
- 🏦 Market Capitalization display
- 🏅 Market Cap Ranking
- 📱 Fully responsive design
- 🔄 Automatic data refresh every 60 seconds
- ⚡ Fast and lightweight user experience

---

## 🛠️ Technologies Used

### Frontend
- React
- JavaScript (ES6+)
- Tailwind CSS

### Data Visualization
- Recharts

### API
- CoinGecko API

### Development Tools
- Vite
- VS Code
- Git & GitHub

---

## 📂 Project Structure

```text
crypto-dashboard/
│
├── public/
│
├── src/
│   ├── components/
│   │   └── CryptoCard.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── vite.config.js
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/etrazia17/crypto-dashboard.git
```

### 2️⃣ Navigate to Project Folder

```bash
cd crypto-dashboard
```

### 3️⃣ Install Dependencies

```bash
npm install
```

### 4️⃣ Start Development Server

```bash
npm run dev
```

The application will run at:

```text
http://localhost:5173
```

---

## 🌐 API Information

This project uses the CoinGecko API to fetch cryptocurrency market data.

Endpoint used:

```text
https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&sparkline=true
```

Data fetched includes:

- Coin Name
- Symbol
- Current Price
- Market Cap
- Market Cap Rank
- 24-Hour Price Change
- 7-Day Sparkline Data

---

## 🧠 Concepts Implemented

This project demonstrates:

- React Functional Components
- Props
- State Management with useState
- Side Effects with useEffect
- API Integration using Fetch API
- Async/Await
- Conditional Rendering
- Search Filtering
- Dynamic Styling
- Dark Mode Implementation
- Responsive UI Design

---

## 📷 Screenshots

### Dashboard

_Add project screenshots here._

Example:

```text
screenshots/crypto-dashboard-main.png
screenshots/dashboard-search.png
screenshots/dashboard-light-mode.png
```

---

## 🔮 Future Improvements

- Add cryptocurrency details page
- Add sorting functionality
- Add favorite coins feature
- Add pagination
- Add portfolio tracking
- Add price alerts

---


## 📄 License

This project is created for learning and portfolio purposes.