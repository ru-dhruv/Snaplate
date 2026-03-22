# 🍽️ Snaplate — AI Food Scanner

> **Snap your food. Know what you eat.**

Snaplate is an AI-powered Android app that lets you point your camera at any food and instantly get its calories, macros, and nutritional breakdown — no manual logging, no barcodes, no effort.

Built by **Dhruv Singh**, first-year CS student at SOIT RGPV Bhopal, as a solo project.

---

## 📸 Preview

The landing page features:
- Animated phone mockup with live scan simulation
- Full sections: Hero, About, Problem, Solution, Contact
- Sign In / Sign Up modal
- Formspree-powered contact form
- Fully responsive design

---

## 🛠️ Technologies Used

### Landing Page (Web)
| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Styling, animations, responsive layout |
| **Vanilla JavaScript** | Modal, toast notifications, form handling |
| **Google Fonts** | Nunito & Space Mono typography |
| **Formspree** | Contact form backend (`formspree.io/f/xwvrjdgv`) |

### Android App(coming soon...)
| Technology | Purpose |
|---|---|
| **Kotlin / Java** | Native Android development |
| **Google Gemini Vision API** | AI food recognition from camera images |
| **Android Camera2 / CameraX** | Camera access and image capture |
| **SharedPreferences / Room DB** | Local data storage for daily calorie log |
| **Retrofit / OkHttp** | API networking |

---

## 🚀 How to Run the Landing Page

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code recommended)

### Steps

**Option 1 — Open directly:**
1. Download or clone this repository
2. Open `index.html` in your browser
3. That's it — no build step needed

**Option 2 — Using VS Code Live Server:**
1. Install the **Live Server** extension in VS Code
2. Right-click `index.html` → **Open with Live Server**
3. The page opens at `http://127.0.0.1:5500`


### Contact Form Setup
The form uses **Formspree**. To connect it to your own email:
1. Go to [formspree.io](https://formspree.io) and create a free account
2. Create a new form and copy your endpoint ID
3. In `index.html`, replace `xwvrjdgv` with your own form ID in the `handleContact` function:
```javascript
fetch('https://formspree.io/f/YOUR_FORM_ID', { ... })
```

> ⚠️ **Known Fix:** Make sure the textarea in the contact form has `name="message"` (not `nmae="message"` — there's a typo in some versions of the file).

---

## 🔮 Future Features (coming soon)

Here's what's coming next to Snaplate:

### 🧠 Smarter AI
- **Portion size estimation** — AI estimates grams based on visual size
- **Multi-food detection** — scan a full plate and get breakdown per item
- **Meal history memory** — remembers your frequent meals for faster logging

### 📊 Better Tracking
- **Weekly & monthly nutrition reports** — charts and trends over time
- **Custom calorie goals** — set targets based on your weight/fitness goals
- **Water intake tracker** — log hydration alongside food
- **Macro split visualiser** — pie chart of protein / carbs / fat daily

### 🌐 Social & Community
- **Food diary sharing** — share your daily meals with friends
- **Community recipes** — user-submitted healthy recipes with auto-nutrition
- **Streak system** — gamified daily logging streaks and badges

### 🔗 Integrations
- **Google Fit / Health Connect** — sync calorie data with fitness apps
- **Barcode scanner** — scan packaged food labels as a fallback
- **Restaurant menu scanner** — point at a menu and get nutrition estimates

### 🔐 Accounts & Sync
- **Cloud sync** — access your food log across devices
- **Google Sign-In** — one-tap authentication
- **Profile & BMI calculator** — personalised daily calorie recommendations

---

## 📲 App Launch

> 🚧 **Apk file coming soon..**
> 🚧 **Coming Soon to Google Play Store!**

The Snaplate Android app is currently in active development.

- **Beta APK** — available soon for direct download
- **Play Store listing** — launching shortly after beta testing
- **Target release** — 2025

To get notified when the app launches:
- ⭐ Star this repository
- Watch for releases on GitHub
- Or drop a message via the [contact form](https://snaplate.app/#contact)

---

## 👨‍💻 About the Developer

**Dhruv Singh**
First-year B.Tech CSE (AI/ML) student at SOIT, RGPV Bhopal
Also pursuing BS in Data Science from IIT Madras

- 🐙 GitHub: [github.com/ru-dhruv](https://github.com/ru-dhruv)
- 💼 LinkedIn: [linkedin.com/in/dhruv-singh-b80068344](https://linkedin.com/in/dhruv-singh-b80068344)

---

## 📄 License

© 2025 Snaplate. All rights reserved.

---

<div align="center">
  Made with ♥ by Dhruv Singh · SOIT RGPV Bhopal
</div>
