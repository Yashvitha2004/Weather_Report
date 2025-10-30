# Weather_Report
A modern weather report web app built with React and Tailwind CSS. It fetches real-time data from the Open-Meteo API to display temperature, humidity, wind speed, and weather conditions for any city. Fully responsive, fast, and user-friendly — designed for accurate and instant weather updates.

<img width="1860" height="935" alt="image" src="https://github.com/user-attachments/assets/896253e8-ec6c-46af-99a6-027e0ce59d0c" />

Features

✅ Search any city to get live weather data  
✅ Fetches real-time weather from Open-Meteo API
✅ Shows temperature, humidity, wind speed, and condition  
✅ Displays current local time of the selected city  
✅ Clean, minimal, and professional UI  
✅ Built using React + Vite for fast performance  
✅ Styled with Tailwind CSS for full responsiveness  
✅ Graceful error handling (invalid city / network errors)  
✅ Loading indicator while fetching data  
✅ Mobile-friendly and optimized layout  
✅ No API key or signup required  
✅ Can be hosted easily on GitHub Pages, Netlify, or Vercel

## 🧰 Tech Stack

| Category | Technology |
|-----------|-------------|
| Frontend Framework | React (Vite) |
| Styling | Tailwind CSS |
| API Source | Open-Meteo API |
| Language | JavaScript (ES6) |
| State Management | React Hooks (`useState`, `useEffect`) |
| Deployment | Netlify / Vercel / GitHub Pages |

## 🧩 Folder Structure

weather-report/
├─ src/
│ ├─ components/
│ │ ├─ SearchBar.jsx
│ │ └─ WeatherCard.jsx
│ ├─ styles/
│ │ └─ index.css
│ ├─ App.jsx
│ ├─ main.jsx
├─ index.html
├─ package.json
├─ tailwind.config.cjs
└─ vite.config.js


How It Works

User enters a city name (e.g., London or Bengaluru).

The app calls the Open-Meteo Geocoding API to get that city’s coordinates.

It then fetches current weather data using the Open-Meteo Forecast API.

Weather details are displayed in a beautifully styled card component.

In case of an invalid city or network issue, a friendly error message appears.


🧠 Code Highlights

React Hooks for state and effect management

Dynamic UI Rendering based on weather conditions

Reusable Components (SearchBar, WeatherCard)

Tailwind Utility Classes for elegant styling

Graceful Error Handling for smooth UX

Descriptive Weather Mapping from weather codes



🎨 UI Design

The interface uses a soft gradient background, rounded cards, and clean typography.
The color scheme dynamically changes based on weather conditions (clear, cloudy, rainy).
Built to be:

Minimal 🧘‍♂️

Intuitive 🧭

Mobile-friendly 📱

📸 Screenshots (Add Yours)

🖥️ Desktop View — Full layout with search and results

📱 Mobile View — Compact design with responsive cards


🌐 Deployment Options

You can easily deploy this app for free on:

Netlify – netlify deploy

Vercel – one-click GitHub import

GitHub Pages – npm run build then gh-pages -d dist

🧪 Testing

Tested on Chrome, Edge, and Firefox

Mobile responsive testing done via Chrome DevTools

Verified on Android (Chrome) and iPhone (Safari)

🛠️ Future Enhancements

🌈 Animated weather icons

🕒 7-day weather forecast

🌍 Multi-language support

💾 Save favorite cities locally

⏰ Add sunrise & sunset times

🪪 License

This project is open-source under the MIT License.
Feel free to modify, use, and share it with credit to the original author.


