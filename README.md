# 🚀 Modern Developer Portfolio

A simple, lightweight, and fast personal developer portfolio built with standard **HTML5**, **CSS3**, and **Vanilla JavaScript**. Designed with a clean, modern light aesthetic, responsive grid layouts, and zero external build tooling required.

---

## ✨ Features

- ☀️ **Modern Light Theme (Default)** with smooth dark mode toggle support.
- 📱 **100% Responsive Design** (optimized for Mobile, Tablet, and Desktop).
- ⚡ **Zero-Dependency & Fast**: Pure HTML5, CSS3, and modern ES6+ JavaScript.
- 🎯 **Interactive Project Filtering**: Filter showcase items by category (Full Stack, Frontend, Web Apps).
- 📋 **Copy-to-Clipboard Email Action** with interactive tooltips and toast alerts.
- ✉️ **Contact Form with Validation**: Client-side validation and responsive toast notifications.
- 🐙 **GitHub & Vercel Ready**: Deployable in seconds with zero configuration.

---

## 📁 Project Structure

```text
portfolio/
├── index.html        # Main semantic HTML5 webpage & content
├── css/
│   └── style.css     # CSS custom properties, responsive design, animations
├── js/
│   └── main.js       # Theme switcher, smooth scroll, project filters & form logic
├── vercel.json       # Vercel deployment headers & clean URLs configuration
├── .gitignore        # Git ignore rules
└── README.md         # Documentation & deployment guide
```

---

## 🛠️ How to Customize for Yourself

All content is clean, well-commented, and simple to edit directly in [`index.html`](file:///Users/laxmanpatel/Desktop/portfolio/index.html):

1. **Your Name & Title**:
   - Change `Laxman Patel` and `Full Stack & Frontend Developer` in the Hero and Navigation sections.
2. **Your Social & GitHub Links**:
   - Update `href="https://github.com/..."` and `href="https://linkedin.com/in/..."` with your actual profile links.
3. **Your Email**:
   - Update `laxmanpatel@example.com` in both the hero links and the contact section (`#user-email-text`).
4. **Your Projects**:
   - Edit the `<article class="project-card">` elements in the `#projects` section to showcase your own projects, titles, descriptions, and repository/demo links.
5. **Your Skills**:
   - Customize or add skill badges under the `#skills` section.

---

## 💻 How to Run Locally

You can run this project locally using any simple web server:

### Option 1: Using Python (Built-in on Mac & Linux)
```bash
python3 -m http.server 3000
```
Then open your browser and navigate to: `http://localhost:3000`

### Option 2: Using VS Code Live Server
Right-click `index.html` inside VS Code and click **"Open with Live Server"**.

### Option 3: Using Node.js `npx serve`
```bash
npx serve .
```

---

## 📤 Step-by-Step: Upload Code to GitHub

Follow these simple steps in your terminal to push your portfolio to GitHub:

### 1. Initialize Git repository
```bash
git init
git add .
git commit -m "Initial commit: Modern developer portfolio"
```

### 2. Create a new repository on GitHub
1. Go to [GitHub.com/new](https://github.com/new).
2. Enter a repository name (for example: `portfolio` or `my-portfolio`).
3. Set the repository to **Public**.
4. Click **Create repository** (do *not* check initialize with README, as we already have one).

### 3. Connect local repository to GitHub and push
```bash
# Rename branch to main
git branch -M main

# Add your GitHub repository as remote (replace YOUR-USERNAME with your actual GitHub username)
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git

# Push the code
git push -u origin main
```

---

## 🌐 Step-by-Step: Deploy to Vercel (Free)

Vercel provides free, high-speed hosting with custom domain support and automatic HTTPS.

### Method A: Deploy via Vercel Dashboard (Easiest)
1. Go to [Vercel.com](https://vercel.com) and sign in with your GitHub account.
2. Click **"Add New..."** → **"Project"**.
3. Select your `portfolio` repository from the list and click **"Import"**.
4. Leave all settings at their defaults (Framework Preset: *Other*, Root Directory: `./`).
5. Click **"Deploy"**.
6. 🎉 Your portfolio will be live at `https://your-portfolio-name.vercel.app` in under 30 seconds!

### Method B: Deploy using Vercel CLI (From Terminal)
```bash
# Install and run Vercel CLI
npx vercel

# For production deployment
npx vercel --prod
```

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
