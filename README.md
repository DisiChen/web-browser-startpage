# 🚀 Personal Minimalist Start Page

A clean, fast, and modern browser start page tailored for personal daily use. Designed with a dark glassmorphism UI, a real-time clock, built-in web search, and customizable favorite links.

!\[License](https://img.shields.io/badge/license-MIT-blue.svg)
!\[HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat\&logo=html5\&logoColor=white)
!\[CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat\&logo=css3\&logoColor=white)

\---

## ✨ Features

* **⚡ Lightweight \& Fast:** Single HTML file with zero external dependencies, loading in milliseconds.
* **🎨 Glassmorphism UI:** Features modern dark mode with vertical gradient backgrounds and elegant blur card effects.
* **🕒 Dynamic Clock:** Displays real-time local hours, minutes, and current date.
* **🔍 Quick Search Bar:** Direct web search triggered by pressing <kbd>Enter</kbd>.
* **📌 Custom Bookmarks:** Fully editable grid for your most frequently used websites with automatic favicon generation.
* **📱 Fully Responsive:** Optimized for both desktop and mobile viewports.

\---

## 🛠️ Customization \& Local Setup

### 1\. Edit Bookmarks

Open `index.html` and modify the bookmark elements under the `<div class="bookmarks-grid">` section:

```html
<a href="https://your-link.com" class="bookmark-card" target="\_blank">
    <img class="bookmark-icon" src="https://www.google.com/s2/favicons?domain=your-link.com\&sz=64" alt="Site Name">
    <span class="bookmark-title">Site Name</span>
</a>
```

### 2\. Change Search Engine

To switch default search engines, edit the search listener logic in the `<script>` section at the bottom of `index.html`:

* **Bing (Default):** `https://cn.bing.com/search?q=`
* **Google:** `https://www.google.com/search?q=`
* **DuckDuckGo:** `https://duckduckgo.com/?q=`

\---

## 🌐 Deploy to GitHub Pages

1. Fork or push this repository to your GitHub account.
2. Go to **Settings** -> **Pages**.
3. Under **Branch**, select `main` (or `master`) and folder `/ (root)`.
4. Click **Save**.
5. Set the generated URL (`https://<username>.github.io/<repository-name>`) as your browser's default new tab page.

\---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

