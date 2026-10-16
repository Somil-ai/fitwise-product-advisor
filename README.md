# Fitwise Product Advisor

> An AI-powered product recommendation and comparison tool built as a Final Year Project.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen?style=flat)
![PWA](https://img.shields.io/badge/PWA-ready-blueviolet?style=flat)

---

## 🔗 Live Demo

> Host on GitHub Pages after pushing — link will be:  
> `https://<your-username>.github.io/fitwise-product-advisor/Fitwise%20Product%20Advisor.html`

---

## 📌 About the Project

Fitwise is a single-page web application that helps users find the best tech product for their specific needs. Instead of showing generic bestseller lists, it scores every product against the user's actual budget, priorities, must-have features, and deal-breakers — and explains exactly why each product ranks where it does.

Built entirely with **vanilla HTML, CSS, and JavaScript** — no frameworks, no backend, no build tools. Everything runs in the browser and data is persisted using `localStorage`.

---

## ✨ Features

### 🔍 Smart Needs Analysis
- 5-step questionnaire: category, budget, purpose, features, priorities
- Weighted scoring algorithm considers budget fit, performance priorities, must-have features, brand preference, and use-case match
- Deal-breaker filters that exclude products automatically

### 📦 Product Catalog
- 25 real products across 5 categories
- Search, filter by category/brand, sort by rating/price/best match
- Category pill filters for quick browsing
- Export catalog as CSV

### 📊 Results & Recommendations
- Best match highlighted with a score ring (0–100%)
- Budget tier breakdown (Budget / Mid-range / Premium)
- All ranked matches with reason cards explaining each score
- Export results as CSV
- Print-friendly report

### 🔄 Side-by-Side Comparison
- Compare up to 4 products at once
- Highlights the best value in each row
- Covers specs, scores, features, pros & cons

### 💖 Wishlist
- Save any product with the heart icon
- Persisted across sessions via localStorage

### 📈 Product Detail Page
- Full specifications table
- Score cards (Performance, Durability, Design, Support)
- Price history chart (Chart.js)
- Tabbed layout: Specs / Scores / Price History / Reviews

### ⭐ Customer Reviews
- Users can submit reviews with name, rating, and text
- Reviews stored in localStorage per product

### 🤖 AI Chat Assistant
- Floating chatbot (bottom-right corner)
- Keyword-based NLP answers questions about products, features, budgets, and how to use the app
- Recognises product names and returns quick summaries

### 🛠️ Admin Panel
- Add, edit, and delete products
- Manage categories
- Reset to demo data

### 🌙 Dark Mode
- System preference detection on first load
- Manual toggle with the ◐ button

### 📱 PWA Ready
- Installable on mobile and desktop
- Works offline after first load (manifest included)

---

## 🗂️ Categories & Products

| Category | Products |
|---|---|
| Laptops | MacBook Air M3, Dell XPS 15, Lenovo ThinkPad E14, ASUS ROG Zephyrus G14, Acer Aspire 5, HP Spectre x360 |
| Smartphones | iPhone 15, Samsung Galaxy S24, Google Pixel 8a, OnePlus 12, Samsung Galaxy A35, Nothing Phone 2a |
| Tablets | iPad Air M2, Samsung Galaxy Tab S9, Lenovo Tab P12, iPad 10th Gen |
| Headphones | Sony WH-1000XM5, Bose QuietComfort 45, Apple AirPods Max, Sennheiser HD 560S, JBL Tune 770NC |
| Smartwatches | Apple Watch Series 9, Samsung Galaxy Watch 6, Garmin Forerunner 265, Noise ColorFit Ultra 3 |

---

## 🚀 How to Run

No installation needed. Just open the HTML file:

```bash
# Clone the repo
git clone https://github.com/<your-username>/fitwise-product-advisor.git

# Open in browser
cd fitwise-product-advisor
start "Fitwise Product Advisor.html"   # Windows
open "Fitwise Product Advisor.html"    # macOS
```

Or simply **double-click** `Fitwise Product Advisor.html`.

---

## 🏗️ Project Structure

```
fitwise-product-advisor/
├── Fitwise Product Advisor.html   # Entire application (HTML + CSS + JS)
├── manifest.json                  # PWA manifest
└── README.md                      # This file
```

Everything is self-contained in a single HTML file — styles, logic, and data.

---

## 🧠 How the Scoring Algorithm Works

Each product gets a score out of 100 based on:

| Factor | Weight |
|---|---|
| Budget fit | 28% |
| Priority scores (user-ranked) | 30% |
| Must-have features | 20% |
| Nice-to-have features | 8% |
| Preferred brand match | 6% |
| Use-case match | 8% |

Products missing must-have features are penalised heavily. Products excluded by deal-breakers are shown separately at the bottom.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and semantic markup |
| CSS3 | Styling, dark mode, responsive layout, animations |
| Vanilla JavaScript (ES6+) | All logic, routing, state management |
| Chart.js (CDN) | Price history line chart |
| localStorage | Data persistence (products, sessions, wishlist, reviews) |
| Google Fonts | Bricolage Grotesque + DM Sans |

---

## 📸 Screenshots

> Add screenshots here after running the project.

| Catalog | Advisor | Results |
|---|---|---|
| *(screenshot)* | *(screenshot)* | *(screenshot)* |

---

## 👨‍💻 Author

**Your Name**  
Final Year Student — B.Tech / BCA / MCA  
**College Name**, India  
GitHub: [@your-username](https://github.com/your-username)

---

## 📄 License

This project is open source under the [MIT License](LICENSE).
