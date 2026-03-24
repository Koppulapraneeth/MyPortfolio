# 🌐 Praneeth Koppula — Personal Portfolio Website

> *"Building technology today for the innovations of tomorrow."*

A sleek, dark-themed personal portfolio website for **Praneeth Koppula**, an IoT Developer & Hardware Innovator built with pure HTML, CSS, and vanilla JavaScript — no frameworks required.

---

## 🔗 Live Preview

> Deploy on GitHub Pages, Netlify, or Vercel and paste your link here.

---

## ✨ Features

- **Custom Animated Cursor** — gold dot with a trailing ring that scales on hover
- **Loading Screen** — branded intro with animated progress bar
- **Typing Animation** — cycles through role titles (IoT Developer, Hardware Innovator, etc.)
- **Particle Canvas** — animated floating gold particles with connecting lines
- **Scroll Reveal Animations** — elements fade in as you scroll
- **Counter Animation** — numbers count up when they enter the viewport
- **Tech Orbit Visual** — animated rotating rings showcasing the tech stack
- **Contact Form** — opens the user's mail client pre-filled with the message
- **Responsive Design** — fully mobile-friendly with hamburger nav
- **Smooth Scrolling** — silky navigation between all sections

---

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file (all-in-one)
├── images/
│   └── praneeth-photo.jpg  # Profile photo (add your own)
└── README.md
```

> All CSS and JavaScript are embedded directly in `index.html` for zero-dependency deployment.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Koppulapraneeth/portfolio.git
cd portfolio
```

### 2. Add your photo

Place your profile photo at:

```
images/praneeth-photo.jpg
```

The avatar will auto-fall back to initials `PK` if the image is missing.

### 3. Open locally

Just double-click `index.html` or serve it with any static server:

```bash
# Using Python
python -m http.server 8000

# Using Node (npx)
npx serve .
```

Then visit `http://localhost:8000`.

---

## 🌍 Deploy to GitHub Pages

1. Push the repository to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://koppulapraneeth.github.io/portfolio`

---

## 🛠️ Customization

All content is in `index.html`. Key areas to update:

| Section | What to Edit |
|---|---|
| **Hero** | Name, description, CTA links |
| **About** | Bio text, tags, education card |
| **Skills** | Skill cards and list items |
| **Projects** | Project titles, descriptions, tech tags, Drive links |
| **Certifications** | Cert names, icons, Drive links |
| **Resume** | Google Drive CV link (2 places) |
| **Contact** | Email, phone, LinkedIn, GitHub, Instagram |
| **Footer** | Social links |

### Changing the CV link

Search for this URL and replace it in both places:

```
https://drive.google.com/file/d/1MZvABnxwZ_Dw1c7bZCidEVyvBeAZYTvU/view?usp=drivesdk
```

### Changing the color scheme

Edit the CSS variables at the top of the `<style>` block:

```css
:root {
  --gold:  #c8a96e;   /* Primary accent */
  --teal:  #4ecdc4;   /* Secondary accent */
  --bg:    #0b0c0f;   /* Background */
}
```

---

## 📦 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, animations, grid, flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Icons | Font Awesome 6.5 (CDN) |
| Fonts | Google Fonts — Cormorant Garamond, Syne, JetBrains Mono |

---

## 📄 Sections

1. **Hero** — Name, animated role titles, CTA buttons, profile card
2. **About** — Bio, tags, education & experience cards
3. **Skills** — Programming, Hardware/IoT, Creative tools
4. **Projects** — IoT Air Pollution Meter, ATM Simulator, Age Calculator, Scientific Calculator
5. **Certifications** — Microsoft Office Specialist, C Programmer, Python, Prompt Engineering, Appreciation
6. **Resume** — Animated tech orbit + CV download
7. **Contact** — Chips with live links + contact form

---

## 📬 Contact

| Platform | Link |
|---|---|
| 📧 Email | praneeth.koppula007@gmail.com |
| 📞 Phone | +91 9652568528 |
| 💼 LinkedIn | [praneeth-koppula](https://www.linkedin.com/in/praneeth-koppula-b1a682306) |
| 🐙 GitHub | [Koppulapraneeth](https://github.com/Koppulapraneeth) |
| 📸 Instagram | [@praneethkoppula](https://www.instagram.com/praneethkoppula) |

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

<p align="center">Designed & Built by <strong>Praneeth Koppula</strong> · 2026</p>
