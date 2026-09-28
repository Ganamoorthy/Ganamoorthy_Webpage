# 🌐 Ganamoorthy Sivadhas - Personal Portfolio Website

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive Design](https://img.shields.io/badge/Design-Responsive%20%26%20Glassmorphism-6366f1?style=for-the-badge)](#)

A modern, responsive, and visually dynamic personal portfolio website designed and developed for **Ganamoorthy Sivadhas**, an Electronics and Computer Science undergraduate, IoT developer, and embedded systems enthusiast.

The website highlights hardware engineering achievements, IoT innovations, award-winning competitions, technical skills, and allows visitors to easily connect or download his CV.

---

## ✨ Features

- **⚡ Sleek Glassmorphism & Dark UI**: Styled with deep slate tones (`#0f172a`), neon/pastel accents, floating ambient glowing orbs, and glassmorphic card elements with backdrop blur.
- **⌨️ Dynamic Typing Animation**: Integrated with [Typed.js](https://github.com/mattboldt/typed.js/) to cycle through key specializations: *IoT Developer*, *PCB Designer*, and *Programmer*.
- **📱 Fully Responsive**: Custom CSS media queries optimized across desktops, tablets, and mobile devices with a slide-out hamburger navigation menu.
- **📜 Scroll Animations & Active Nav**: Smooth reveals powered by [ScrollReveal.js](https://scrollrevealjs.org/) and a debounced scrollspy that updates the active navigation item dynamically.
- **🏆 Project Showcase with Award Highlights**: Detailed showcase of embedded and IoT projects (including competition finalists such as *SLT Mobitel TechNovation 2025* and *Pitch Arena*).
- **💬 Direct WhatsApp Contact Form**: Interactive contact form that validates user inputs and instantly opens a pre-formatted WhatsApp chat.
- **📄 Instant CV Download**: One-click downloadable curriculum vitae stored locally within the repository assets.

---

## 🛠️ Tech Stack & Libraries

### **Core Technologies**
- **HTML5**: Semantic document structure and accessible web layouts.
- **Vanilla CSS3**: Custom design system, CSS variables, keyframe orb animations, flexbox/grid layouts, and responsive breakpoints.
- **Vanilla JavaScript (ES6+)**: DOM manipulation, debounced scroll handling, WhatsApp API deep-linking, and mobile navigation toggling.

### **Libraries & External Resources**
- **[Typed.js (v2.0.16)](https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js)**: Typing animation for dynamic titles in the hero banner.
- **[ScrollReveal.js](https://unpkg.com/scrollreveal)**: Directional animations on scroll for cards, text, and images.
- **[Font Awesome (v6.5.1)](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css)**: Scalable vector icons for technologies and skills.
- **[Unicons (v4.0.8)](https://unicons.iconscout.com/)**: Clean line icons for navigation and social handles.
- **[Google Fonts (Inter)](https://fonts.google.com/specimen/Inter)**: Modern sans-serif typography.

---

## 📁 Repository Structure

```text
Ganamoorthy_Webpage-main/
├── .gitattributes                # Git line ending normalization rules
├── .gitignore                   # Ignores dependencies (node_modules/)
├── 111.jpg                      # Profile / hero section avatar photograph
├── circuit-board.png            # Custom tech badge icon for Arduino boards
├── infinity.png                 # Custom tech badge icon for Arduino IDE
├── index.html                   # Main single-page portfolio markup
├── script.js                    # Interactive features, animations & form logic
├── style.css                    # Design system, themes, and responsive styles
├── assets/
│   └── cv/
│       └── Ganamoorthy_Sivadhas_CV.pdf   # Downloadable curriculum vitae
└── README.md                    # Project documentation
```

---

## 🚀 Getting Started

No build tools, bundlers, or package installations are required to run this portfolio locally.

### **Option 1: Direct Browser Launch**
Simply double-click [`index.html`](index.html) or right-click and choose **Open With > Google Chrome** (or any modern web browser).

### **Option 2: Using VS Code Live Server (Recommended)**
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by *Ritwick Dey*).
3. Right-click [`index.html`](index.html) and select **"Open with Live Server"**.
4. The site will run at `http://127.0.0.1:5500/index.html` with automatic hot-reloading on changes.

### **Option 3: Using Python HTTP Server**
Run the following command in the project root directory:
```bash
# Python 3
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

---

## 🔬 Featured Projects Highlighted on the Site

| Project | Description | Role / Recognition |
| :--- | :--- | :--- |
| **Lumofit – Smart Posture Belt with AI** | Solar-powered assistive wearable with posture correction, health tracking (ECG, PPG, gyro, accelerometer, GPS, microphone), and firmware AI integration. | Hardware Engineer & IoT Developer <br>🏆 *Finalist - SLT Mobitel TechNovation 2025* |
| **Guide Pro: Intelligent Presentation System** | ESP32-powered edge device for presentation feedback, featuring an INMP441 microphone, OLED display, and Vosk offline speech-to-text framework. | Embedded IoT Engineer |
| **IoT-Based RFID Attendance System** | ESP32-driven RFID identification with real-time cloud sync, duplicate-scan protection, and audio-visual indicators. | Hardware Engineer & IoT Developer <br>🏆 *Finalist - Evolve Inter-University Challenge* |
| **Smartens – Wearable Assistance System** | Low-power ESP32-C3 wearable with MAX30102 heart rate tracking, GPS positioning, BLE connectivity, vibration motor, and interactive UI. | Hardware Engineer & IoT Developer <br>🏆 *Finalist - Pitch Arena, University of Ruhuna* |

---

## ⚙️ Customization Guide

If you wish to update details or deploy this for your own use:

1. **Personal Information & Bio**:
   - Update text in the `#home` and `#about` sections within [`index.html`](index.html).
2. **Profile Picture**:
   - Replace [`111.jpg`](111.jpg) with your own portrait image (or change the `src` attribute in the `.featured-image` block of [`index.html`](index.html)).
3. **Resume / CV**:
   - Replace [`assets/cv/Ganamoorthy_Sivadhas_CV.pdf`](assets/cv/Ganamoorthy_Sivadhas_CV.pdf) with your updated PDF resume.
4. **WhatsApp Contact Form Number**:
   - In [`script.js`](script.js), modify the `phoneNumber` variable (around line 124) with your international phone number format (without `+`):
     ```javascript
     let phoneNumber = "94773700858";
     ```
5. **Social Media Links**:
   - Update social links inside both `.social_icons` and `.footer-social-icons` in [`index.html`](index.html).

---

## 📬 Contact & Socials

- **Developer**: Ganamoorthy Sivadhas
- **Email**: [sivadhasganamoorthy@gmail.com](mailto:sivadhasganamoorthy@gmail.com)
- **Phone**: +94 773700858
- **LinkedIn**: [linkedin.com/in/ganamoorthy-sivadhas-334668285](https://www.linkedin.com/in/ganamoorthy-sivadhas-334668285)
- **GitHub**: [@Ganamoorthy](https://github.com/Ganamoorthy)
- **Twitter/X**: [@GSivadhas](https://x.com/GSivadhas)
- **Instagram**: [@ganamoorthy_](https://www.instagram.com/ganamoorthy_/)

---

## 📄 License

This project is open-source and personal intellectual property. Feel free to explore, learn from, and adapt the code for your own portfolio.
