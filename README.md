# Patrick Buckley - Personal Portfolio Website

A modern, Chicago-themed personal portfolio website showcasing professional experience, education, skills, and achievements.

## Features

- 🏙️ **Chicago-themed design** with animated GIF backgrounds
- 🎨 **Modern UI/UX** with smooth animations and transitions
- 📱 **Fully responsive** design for all devices
- 🎯 **Interactive elements** with hover effects and smooth scrolling
- 🏗️ **CSS-based city skyline** on the hero section
- 🚇 **Animated L train background** on contact section

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (Vanilla JS)
- Font Awesome Icons

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # Interactive functionality
├── .gitignore          # Git ignore file
└── README.md           # This file
```

## Setup Instructions

1. Clone the repository:
```bash
git clone <repository-url>
cd "Websites - Qvibe"
```

2. Open `index.html` in your web browser, or use a local server:
```bash
python3 -m http.server 8000
```

3. Visit `http://localhost:8000` in your browser

## GitHub Setup

To push this repository to GitHub:

1. **Install Xcode Command Line Tools** (if not already installed):
```bash
xcode-select --install
```

2. **Create a new repository on GitHub:**
   - Go to https://github.com/new
   - Name your repository (e.g., "patrick-buckley-portfolio")
   - Don't initialize with README (we already have one)
   - Click "Create repository"

3. **Push to GitHub:**
```bash
git init
git add .
git commit -m "Initial commit: Personal portfolio website with Chicago theme"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

## Customization

- Update personal information in `index.html`
- Modify colors in `styles.css` (CSS variables in `:root`)
- Add/remove sections as needed
- Replace GIF files with your own:
  - `chicago-hero.gif` for hero section
  - `l-train.gif` for contact section

## License

© 2025 Patrick Buckley. All rights reserved.

