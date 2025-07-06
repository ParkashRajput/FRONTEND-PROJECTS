# 🍏 GSAP iPhone Showcase Website

A visually stunning and smooth-scrolling Apple iPhone product showcase built using **GSAP** and modern frontend technologies. This project mimics the official Apple feel with scroll-triggered animations, crisp transitions, and minimalistic UI.

---

## 🚀 Live Demo

👉 [Click here to view live](https://your-deployment-url.com)

---

## ✨ Features

- ⚡ GSAP-powered scroll animations
- 📱 iPhone mockups and 3D reveal effects
- 🖼️ Text fade-ins, zoom, pinning, parallax
- 🌓 Light and dark mode friendly
- 💻 Fully responsive and clean layout

---

## 🛠️ Built With

| Tech            | Role                        |
|-----------------|-----------------------------|
| **HTML5**       | Page structure              |
| **CSS3 / SCSS** | Styling and layout          |
| **JavaScript**  | Interaction and logic       |
| **GSAP**        | Scroll animations           |
| **GSAP ScrollTrigger** | Scroll-based triggers  |
| **Locomotive Scroll** *(optional)* | Smooth scroll effect |

---

## 📂 Folder Structure

```
gsap-iphone-site/
├── index.html
├── /css
│   └── style.css
├── /js
│   └── main.js
├── /assets
│   ├── /images
│   └── /iphone
└── README.md
```

---

## 🧑‍💻 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/gsap-iphone-site.git
cd gsap-iphone-site
```

### 2. Open the Project

Simply open `index.html` in your browser.  
Or launch a local server:

```bash
npx live-server
```

---

## 🔧 Animation Setup (main.js)

All animation logic is handled in `js/main.js` using `GSAP` and `ScrollTrigger`:

```js
gsap.to(".iphone", {
  scrollTrigger: {
    trigger: ".iphone-section",
    start: "top center",
    end: "bottom top",
    scrub: true,
    pin: true
  },
  scale: 1.2,
  rotation: 360
});
```

You can modify the animation logic easily to fit your custom flow.

---



---

---
---

## 🙌 Credits

- Inspired by Apple’s product pages
- Built using [GSAP](https://greensock.com/gsap/)
- Icons & mockups from Apple and [Pexels](https://www.pexels.com)

---

> Need help adding Apple-style sticky sections, GSAP pinning, or loading animations? I got you. Just ask!
