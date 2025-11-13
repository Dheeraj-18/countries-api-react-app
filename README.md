#  World Countries Explorer (React)

A responsive and interactive web application built with **React** to explore data of countries from the **REST Countries API**.  
Users can **search**, **filter**, **view detailed country information**, and toggle **Light/Dark mode** globally.

---

## 🚀 Live Preview

🔗 **Visit Here:** https://countries-explorer-api.netlify.app/

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **React.js** | UI Rendering & Component Structure |
| **React Router** | Dynamic Routing for Country Details |
| **Context API** | Global Theme (Dark/Light Mode) Management |
| **Fetch API / useEffect** | Fetching Countries Data |
| **CSS (Flexbox & Responsive Design)** | Styling & Layout |

---

## ✨ Features

- ✅ Search countries by name  
- ✅ Filter countries by region (Asia, Africa, Europe, etc.)  
- ✅ Click any country to view **detailed info** (population, currencies, languages, borders, etc.)  
- ✅ **Dark/Light Theme** toggle using **Context API**  
- ✅ Fully **responsive** layout for all devices  
- ✅ Smooth UI interaction powered by React state & controlled rerenders  

---

## 🎯 Learning Goals Achieved

- Mastered **React Hooks** (`useState`, `useEffect`)
- Implemented **Dynamic Routing** via `react-router-dom`
- Managed global UI state with **Context API**
- Worked with **REST API** for live data handling
- Structured project into reusable & maintainable components

---

## 📂 Folder Structure
```
root/
│── components/
│   ├── Header.jsx
│   ├── CountryCard.jsx
│   └── SearchFilter.jsx
|   └── Home.jsx
|   └── CountryDetails.jsx
|   └── CountriesList.jsx
│
│
│── contexts/
│   └── ThemeContext.jsx
│
│── hooks/
│   └── useTheme.js
│
│── App.css
│── App.jsx
│── index.jsx
│── index.html
 ```



---

## ⚙️ Setup & Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/world-countries-explorer-react.git

# Navigate to project directory
cd world-countries-explorer-react

# Install dependencies
npm install

# Start development server
npm start


