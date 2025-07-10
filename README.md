Where in the World? – Country Detail Web App
===========================================

📚 Overview
-----------
A responsive frontend web application that allows users to explore countries around the world. 
Built with HTML, CSS, and JavaScript, it fetches live data from the REST Countries API to display country details, supports region filtering, live search, and dark mode.

🚀 Features
-----------
✅ List all countries with flag, population, region, and capital  
✅ Search countries by name in real-time  
✅ Filter countries by region (Africa, America, Asia, Europe, Oceania)  
✅ View detailed country page with native name, population, region, subregion, capital, top-level domain, currencies, languages, and border countries  
✅ Dark mode toggle for better UX

🛠️ Tech Stack
--------------
- Frontend: HTML5, CSS3, JavaScript (ES6)
- API: REST Countries v3.1
- Icons: Font Awesome
- Fonts: Google Fonts (Nunito)

📂 Project Structure
--------------------
project-root/
 ├── index.html       -> Main country listing page
 ├── country.html     -> Individual country detail page
 ├── style.css        -> Styles for index and dark mode
 ├── country.css      -> Styles specific to country detail page
 ├── script.js        -> JS for index page: fetch, search, filter, theme
 └── country.js       -> JS for country page: fetch details, show borders

⚙️ Getting Started
-------------------
🔧 Prerequisites
- Any modern web browser (Chrome, Firefox, Edge)

🚀 Run Locally
1. Clone the repository
    git clone https://github.com/prince1323/GetCountryDetailDarft1.git
    cd GetCountryDetailDarft1

2. Open `index.html` in your browser
- Just double-click or right-click and open with your preferred browser.

🌐 Usage
--------
- Use the search bar to look up countries by name.
- Use the dropdown to filter by region.
- Click on any country card to view detailed information and neighboring countries.
- Toggle dark mode using the top right icon.

🚀 Future Enhancements
-----------------------
✅ Animate page transitions  
✅ Cache API responses for faster reloads  
✅ Add a map view using Leaflet.js  
✅ Add error handling for failed API calls


🛠 Developed by Prince Kumar
https://github.com/prince1323

