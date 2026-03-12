Below is a **clean, professional, copy-paste ready `README.md`** for your repository with:

* GitHub badges
* Live demo link
* Clear structure
* No GIF
* No future improvements section

---

# 📖 Divine Pearls Presenter

[![Live Demo](https://img.shields.io/badge/Live-Demo-green?style=for-the-badge\&logo=github)](https://alihusains.github.io/presenter/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge\&logo=github)](https://github.com/alihusains/presenter)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![Pure JS](https://img.shields.io/badge/Vanilla-JavaScript-yellow?style=for-the-badge\&logo=javascript)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen?style=for-the-badge)

A **beautiful full-screen presentation tool** that converts content from **Divine Pearls (ya-mahdi.net)** into a **slide-based presentation format** suitable for projection in mosques, majalis, and gatherings.

Instead of scrolling through a webpage, the content is transformed into **clean slides with large Arabic text and translations**, making it easy to display on **projectors, TVs, and large screens**.

---

# 🌐 Live Demo

Try it online:

[https://alihusains.github.io/presenter/](https://alihusains.github.io/presenter/)

Paste any Divine Pearls link such as:

```
https://ya-mahdi.net/view.php?cat=maf_dua40&lang=en
```

and start presenting immediately.

---

# ✨ Features

## 🎥 Presentation Mode

* Converts Divine Pearls pages into **slide-based presentations**
* Ideal for **projectors and large displays**
* Minimal, distraction-free interface
* Smooth slide navigation

---

## 🌍 Language Support

The presenter automatically detects language from the Divine Pearls link.

Supported languages:

| Language   | Code |
| ---------- | ---- |
| English    | `en` |
| Urdu       | `ur` |
| Roman Urdu | `ro` |
| Azerbaijan | `az` |

Arabic text is displayed prominently with translation below it.

---

# 📑 Slide Structure

Each Divine Pearls page is converted into slides.

### Intro Slide

Contains:

* Title
* Description

### Content Slides

Each slide displays:

```
Arabic Line
Translation Line
```

Each Arabic line becomes **one slide**, making recitation clear and readable for audiences.

---

# ⌨ Keyboard Shortcuts

| Key           | Action          |
| ------------- | --------------- |
| → / Space     | Next Slide      |
| ← / Backspace | Previous Slide  |
| Home          | First Slide     |
| End           | Last Slide      |
| F             | Fullscreen Mode |

* | Increase Font Size

- | Decrease Font Size
  S | Display Settings
  ? | Show Keyboard Help
  Esc | Exit Presentation

---

# 🖱 Navigation Methods

Slides can be navigated using multiple input methods:

| Method                          | Supported |
| ------------------------------- | --------- |
| Keyboard shortcuts              | ✓         |
| Mouse click (left/right screen) | ✓         |
| Navigation arrows               | ✓         |
| Scroll wheel                    | ✓         |
| Touch swipe                     | ✓         |
| Progress bar                    | ✓         |

---

# 🎛 Display Controls

Users can customize the presentation display.

| Feature         | Description                                      |
| --------------- | ------------------------------------------------ |
| Font resize     | Increase or decrease Arabic and translation size |
| Auto-fit text   | Automatically scale text to fit screen           |
| Fullscreen mode | Ideal for projection                             |
| Slide counter   | Displays current slide position                  |
| Progress bar    | Jump to any slide instantly                      |
| Settings panel  | Adjust display preferences                       |

---

# 🧠 How It Works

The application parses Divine Pearls pages and converts them into slides.

### Step 1 — User Input

Paste a link from:

```
https://ya-mahdi.net
```

Example:

```
https://ya-mahdi.net/view.php?cat=maf_dua40&lang=en
```

---

### Step 2 — Fetch Content

The page is fetched using CORS proxy services:

* AllOrigins
* CodeTabs

If one fails, the other is used automatically.

---

### Step 3 — Parse HTML

The parser extracts content using the page structure.

| HTML Class                        | Purpose                |
| --------------------------------- | ---------------------- |
| `.card.big-card`                  | Main content container |
| `.arabic.arabic-line`             | Arabic text            |
| `.translation.translatable`       | Translation text       |
| `.translation:not(.translatable)` | Title / description    |

---

### Step 4 — Generate Slides

Each Arabic line is paired with its translation to create slides:

```
Arabic line
↓
Translation
↓
Slide generated
```

---

# 📂 Project Structure

```
presenter
│
├── index.html
├── fonts
│   ├── Al-Qalam.ttf
│   ├── Jameel.ttf
│   └── Roboto.ttf
│
└── README.md
```

---

# ⚙ Technologies Used

| Technology         | Purpose              |
| ------------------ | -------------------- |
| HTML5              | Page structure       |
| CSS3               | Styling and layout   |
| Vanilla JavaScript | Application logic    |
| DOMParser API      | HTML parsing         |
| CORS Proxy         | Fetch external pages |

No frameworks or external dependencies are required.

---

# 📱 Responsive Design

The presenter works across devices:

* Desktop
* Tablets
* Mobile
* Large projector screens

Font sizes automatically adjust for different screen sizes.

---

# 🧩 Fonts

| Font     | Usage                  |
| -------- | ---------------------- |
| Al-Qalam | Arabic text            |
| Jameel   | Urdu translation       |
| Roboto   | English / Roman Urdu   |
| Lora     | Azerbaijan translation |

Google Fonts fallbacks are included.

---

# 🚀 Running Locally

Clone the repository:

```bash
git clone https://github.com/alihusains/presenter.git
```

Open the file:

```
index.html
```

in your browser.

No installation or build step required.

---

# 🌐 Example Links

You can load any Divine Pearls page.

Examples:

```
https://ya-mahdi.net/view.php?cat=maf_dua40&lang=en
https://ya-mahdi.net/view.php?cat=maf_ziyarat&lang=ur
https://ya-mahdi.net/view.php?cat=maf_namaz&lang=ro
```

Supported categories include:

* Duas
* Ziyarat
* Namaz
* Aamal

---

# ❤️ Credits

Content source:

Divine Pearls Library
[https://ya-mahdi.net](https://ya-mahdi.net)

This project simply converts their content into a **presentation format for easier viewing during gatherings**.

---

# ⭐ Support the Project

If you find this project useful:

* Star the repository
* Share it with your community
* Use it in mosques and gatherings

---

# 👨‍💻 Product Design :

Ali Husain Sorathiya

GitHub
[https://github.com/alihusains](https://github.com/alihusains)

Project Repository
[https://github.com/alihusains/presenter](https://github.com/alihusains/presenter)

Live Demo
[https://alihusains.github.io/presenter/](https://alihusains.github.io/presenter/)
