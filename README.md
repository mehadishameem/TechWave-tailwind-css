# TechWave - Modern Podcast Landing Page

A responsive podcast website for TechWave, built with HTML, Tailwind CSS CDN, and custom CSS. It features a modern dark theme, podcast episodes, host information, subscription links, and adaptive layouts for mobile and desktop screens. Designed to deliver daily tech insights, productivity strategies, and personal growth stories from industry leaders, this project closely follows Figma design specifications with custom breakpoints and interactive animations.

---

## 🌐 Live Preview & Repository

- **Live Site:** [TechWave - Podcast Website](https://mehadishameem.github.io/TechWave-tailwind-css/)
- **GitHub Repository:** [mehadishameem/TechWave-tailwind-css](https://github.com/mehadishameem/TechWave-tailwind-css)

---

## ✨ Key Features

- **Responsive Navigation Bar**: Sticky top header with a blurred background, brand logo, mobile hamburger drawer toggle (CSS-only), navigation anchors, and a gradient CTA button.
- **Interactive Hero Banner**:
  - Animated circular artwork with an outer pulsing pink glow and a continuously rotating dashed neon ring.
  - Centered microphone illustration with a floating "New" badge.
  - Clear heading, value proposition, and quick action buttons (Listen on Spotify & Subscribe).
- **About The Podcast & Stats**:
  - Overview of the podcast mission.
  - 4-card statistics grid highlighting monthly listeners, published episodes, average rating, and featured experts.
- **"Why Choose TechWave" Bento Grid**:
  - Responsive 5-card bento grid (spanning 1 column on mobile, 2 columns on tablet, and 6-column bento spans on desktop).
  - Cards highlight Audio Quality, Mobile Experience, Global Community, Exclusive Interviews, and Rich Learning Resources with dedicated icons.
- **Featured Episodes**:
  - 3 curated podcast episode cards featuring gradient artwork covers with glowing play-button hover overlays.
  - Episode titles, summaries, and duration tags with clock icons.
- **Meet The Host**:
  - Dedicated spotlight card for host **Alex Kumar**.
  - Circular portrait, industry bio, and styled social media links (LinkedIn, X, Instagram, YouTube) with custom magenta borders and smooth hover states.
- **Branded Soundwave Footer**:
  - Authentic audio soundwave background texture.
  - Centered TechWave brand logo.
  - Direct links to popular podcast platforms (Spotify, Apple Podcasts, YouTube, Twitter) presented cleanly in a responsive layout.
  - Copyright information.

---

## 🛠️ Technologies Used

- **HTML5**: Semantic tags (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`) for accessibility and clean document structure.
- **Tailwind CSS (CDN)**: Utility-first CSS framework configured with custom Figma design tokens.
- **Custom CSS3**:
  - `@keyframes spin` for the rotating dashed ring.
  - `@keyframes pulse` for the glowing podcast circle aura.
  - Custom gradient backgrounds and smooth scroll behavior.
- **Google Fonts**: Inter font family (`wght@400;500;600;700;800;900`).

---

## 🎨 Design System & Breakpoints

### Color Palette
| Color Name | Hex Code | Description |
| :--- | :--- | :--- |
| **Brand (Background)** | `#1A0B2E` | Deep dark purple canvas |
| **Card / Panel** | `#2A1648` / `#230E3D` | Slightly lighter purple for elevated cards |
| **Neon Accent** | `#00FF88` | High-visibility green for highlights, badges & buttons |
| **Muted Text** | `#C4B5D4` | Soft lavender-gray for easy reading |

### Responsive Breakpoints
- **Mobile (Default)**: `< 576px`
- **Tablet (`md:`)**: `576px` and above
- **Desktop (`lg:`)**: `992px` and above

---

## 📂 Project Structure

```text
B13-A02-TechWave/
├── assets/                  # Icons, vectors, host image, and backgrounds
│   ├── TechWave.svg         # Primary vector logo
│   ├── hero-bg.png          # Hero section background
│   ├── hero-circle.png      # Inner podcast circle artwork
│   ├── microphone.png       # Microphone overlay
│   ├── host.png             # Alex Kumar portrait
│   ├── footer-bg.png        # Soundwave footer texture
│   └── ... (social & platform icons)
├── index.html               # Main landing page
├── index.css                # Supplementary project styles
├── tailwind.css             # Tailwind base entry
└── README.md                # Project documentation
```

---

## 🚀 Getting Started Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mehadishameem/TechWave-tailwind-css.git
   ```

2. **Navigate to the project folder:**
   ```bash
   cd TechWave-tailwind-css
   ```

3. **Open the project:**
   - Double click `index.html` to open it in any web browser, or
   - Use VS Code Live Server extension: right-click `index.html` and choose **"Open with Live Server"**.

---

## 👤 Author

- **Name:** Mehadi Shameem
- **GitHub:** [@mehadishameem](https://github.com/mehadishameem)
- **Course:** Programming Hero - Web Development Batch 13
