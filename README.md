# 🍽️ Eureka Kitchen

> A full business-style restaurant website built with HTML & Tailwind CSS.

---

## 📌 Project Overview

**Eureka Kitchen** is a group project to design and develop a complete, professional restaurant website. The site features multiple pages, food cards, opening hours, and an embedded Google Map — built entirely with HTML and Tailwind CSS.

---

## 🌐 Pages

| Page | Description | Assigned To |
|------|-------------|-------------|
| `index.html` | Home page — hero section, highlights, call to action | You (Team Lead) |
| `menu.html` | Menu page — food cards with names, descriptions & prices | Member 2 |
| `about.html` | About page — restaurant story, team, and values | Member 3 |
| `contact.html` | Contact page — form, opening hours & Google Maps embed | Member 4 |

---

## ✅ Features

### Minimum Required
- [x] Food cards (menu items with image, name, description, price)
- [x] Opening hours section
- [x] Google Maps embed

### Additional Features (encouraged)
- Responsive navigation bar
- Hero/banner section
- Customer testimonials
- Newsletter subscription
- Social media links
- Smooth scroll and hover effects

---

## 🛠️ Tech Stack

- **HTML5** — Page structure and semantics
- **Tailwind CSS** (via CDN) — Styling and responsive design

> No frameworks, no build tools. Just clean HTML and Tailwind.

---

## 📁 Project Structure

```
eureka-kitchen/
├── index.html          # Home page
├── menu.html           # Menu page
├── about.html          # About page
├── contact.html        # Contact page
├── assets/
│   └── images/         # All images used across the site
└── README.md           # Project documentation
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-org>/eureka-kitchen.git
   cd eureka-kitchen
   ```

2. **Open in your browser**
   - Simply open any `.html` file directly in your browser — no server needed.
   - Recommended: use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code for live reloading.

3. **Tailwind CSS**
   - Tailwind is loaded via CDN — no installation required.
   - The CDN `<script>` tag is already included in each page's `<head>`.

---

## 🌿 Branching Strategy

We use a **simple feature-branch workflow** — everyone branches off `main` and merges back into `main` via Pull Requests:

```
main
  ├── feature/home-page
  ├── feature/menu-page
  ├── feature/about-page
  └── feature/contact-page
```

### Rules
- ❌ **Never push directly to `main`**
- ✅ Always create a **feature branch** for your page
- ✅ Open a **Pull Request** into `main` when your page is ready
- ✅ The team lead reviews and merges all Pull Requests

---

## 🤝 Contribution Guide

Each member works on their assigned page in a dedicated feature branch.

### Step-by-Step Workflow

```bash
# 1. Clone the repo (first time only)
git clone https://github.com/<your-org>/eureka-kitchen.git
cd eureka-kitchen

# 2. Create your feature branch from main
git checkout -b feature/<your-page>-page
# e.g., git checkout -b feature/menu-page

# 3. Work on your page, then stage and commit your changes
git add .
git commit -m "feat: add menu page with food cards"

# 4. Push your feature branch to GitHub
git push origin feature/<your-page>-page

# 5. Open a Pull Request on GitHub → base: main ← compare: feature/<your-page>-page
```

### ⚠️ Before Starting Each Work Session

Always pull the latest changes from `main` first to stay in sync with your teammates:

```bash
git checkout main
git pull origin main
git checkout feature/<your-page>-page
git merge main    # bring any new changes into your branch
```

### Commit Message Style
Use clear, consistent messages:
```
feat: add hero section to home page
fix: correct opening hours layout on mobile
style: update food card hover effects
```

---

## 👥 Team Members

| Name | Role | Page |
|------|------|------|
| [Tosin Kazeem] | Team Lead | Home (`index.html`) |
| [Timothy Paul] | Developer | Menu (`menu.html`) |
| [Editor Freedom] | Developer | About (`about.html`) |
| [Yilkime Zakka] | Developer | Contact (`contact.html`) |

---

## 📄 License

This project is created for academic/group assignment purposes.

---

*Eureka Kitchen — Where every dish tells a story.*
