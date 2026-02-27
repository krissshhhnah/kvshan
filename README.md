# 📘 KV Shan — Official Author Website

A modern, dynamic author platform powered by **Blogger (Headless CMS)** and a custom frontend built with **Vanilla JavaScript**.

This project transforms Blogger into a robust content engine while delivering a premium, distraction-free reading experience through a fully custom UI.

---

## 🚀 Live Website
🌐 [www.kvshan.com](https://www.kvshan.com)

---

## 🧠 Architecture Overview

Blogger (CMS) → JSON Feed API → Custom JS Fetch → Slug-Based Routing → Dynamic UI

* **Blogger** is used strictly as a Headless Content Management System.
* The **Frontend** handles rendering, filtering, routing, and reading enhancements without heavy frameworks.

---

## ✨ Features

### 📚 Dynamic Blog System
* Fetches posts directly from the Blogger JSON feed.
* Automatically converts feed entries into clean post objects.
* Extracts featured images and generates excerpts automatically.

### 🔗 Slug-Based Routing
* Clean, SEO-friendly URLs: `/blog/why-you-feel-good-then-fall-back-again`
* No query strings for a professional look.

### 🔎 Search & Filtering
* **Live Client-Side Search:** Instant filtering by title and excerpt.
* **Category Filtering:** Dynamic extraction and filtering by Blogger labels.

### ⏱ Reading Enhancements
* **Reading Time Calculation:** Automatic estimation based on 200 WPM.
* **Reading Progress Bar:** Scroll-based percentage tracking.
* **Typography Optimized:** Clean HTML stripping for long-form reading comfort.

---

## 🛠 Tech Stack
* **HTML5** & **CSS3**
* **Vanilla JavaScript (ES6)**
* **Blogger JSON Feed API**
* *No frameworks. No build tools. Pure performance.*

---

## 📂 Project Structure
```text
/
├── index.html
├── blog.js
├── style.css
└── README.md
```

---

## 🔌 Blogger Integration
**Feed endpoint:** `https://www.kvshan.com/feeds/posts/default?alt=json&max-results=50`

The engine cleans inline Blogger styles and dynamically extracts:
* Title & Slug
* Published Date
* Categories/Labels
* Featured Image & Content

---

## ⚙️ Setup Instructions
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/kvshan-website.git](https://github.com/your-username/kvshan-website.git)
    ```
2.  **Run Locally:**
    Open `index.html` in your browser (or use a Live Server extension).
3.  **Deployment:**
    Compatible with GitHub Pages, Netlify, Vercel, or any static hosting provider.

---

## 🧩 How Slug Routing Works
The router checks `window.location.pathname`. If the path starts with `/blog/`, it matches the slug from the fetched posts and renders the specific article dynamically without a page reload.

---

## 📈 Performance Notes
* No heavy frameworks or unnecessary libraries.
* Lightweight DOM manipulation.
* Minimal network requests.
* Optimized for long-form reading.

---

## 🔮 Future Enhancements
- [ ] Dark mode toggle
- [ ] Bookmark system (localStorage)
- [ ] Related posts engine
- [ ] Infinite scroll
- [ ] PWA for offline reading
- [ ] Structured data (Schema.org for SEO)

---

## ✍ Author
**KV Shan** *Author | Thinker | Systems Builder* 📩 [kvshan23@gmail.com](mailto:kvshan23@gmail.com)  
🌐 [www.kvshan.com](https://www.kvshan.com)

---

## 📜 License
This project is proprietary and belongs to **KV Shan**.
