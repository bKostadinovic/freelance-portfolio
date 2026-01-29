# Freelance Portfolio

Professional portfolio landing page showcasing browser-based tools and web development projects.

🔗 **Live Demo:** [bora-portfolio.netlify.app](https://bora-portfolio.netlify.app)

---

## 📁 Project Structure

```
freelance-portfolio/
├── index.html
├── css/
│   └── portfolio.css
├── js/
│   └── smooth-scroll.js
└── README.md
```

---

## ✨ Features

- Hero section with stats
- 3 featured projects with live demos & GitHub links
- Skills organized by category
- Contact section (Upwork, Fiverr, Email, GitHub)
- Smooth scrolling navigation
- Fully responsive
- No dependencies

---

## 🚀 Deployment

### GitHub

```bash
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/bKostadinovic/freelance-portfolio.git
git branch -M main
git push -u origin main
```

### Netlify

1. Go to [netlify.com](https://netlify.com)
2. "Add new site" → "Import an existing project"
3. Choose GitHub → Select `freelance-portfolio`
4. Click "Deploy site"
5. Optional: Customize domain in settings

---

## 🎨 Customization

### Update Contact Links

In `index.html` around line 280:

```html
<!-- Add your Upwork URL -->
<a href="#" class="contact-link">View Profile →</a>

<!-- Add your Fiverr URL -->
<a href="#" class="contact-link">Browse Gigs →</a>

<!-- Add your email -->
<a href="mailto:your.email@example.com" class="contact-link">Get In Touch →</a>
```

### Change Colors

In `css/portfolio.css` lines 15-25:

```css
:root {
    --primary: #2563eb;
    --secondary: #10b981;
    --accent: #f59e0b;
}
```

### Add New Project

Copy a `.project-card` div in `index.html` and update:
- Icon emoji
- Title & description
- Feature tags
- Live demo link
- GitHub repo link

---

## 🔧 Built With

- HTML5
- CSS3 (Grid, Flexbox, CSS Variables)
- Vanilla JavaScript (ES6+)
- Zero dependencies

---

## 📄 License

MIT License

---

**Built by Bora Kostadinovic** | [GitHub](https://github.com/bKostadinovic)