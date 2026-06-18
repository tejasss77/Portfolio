# 🚀 Tejas Sonar's Portfolio

A **modern, interactive personal portfolio website** built with clean HTML, CSS, and JavaScript. This portfolio showcases projects, skills, certifications, and coding profiles with an admin editing mode for easy customization.

---

## 📋 Table of Contents

- [Features](#features)
- [Main Components](#main-components)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Admin Edit Mode](#admin-edit-mode)
- [Customization Guide](#customization-guide)
- [License](#license)

---

## ✨ Features

✅ **Responsive Design** — Mobile-friendly and works on all screen sizes  
✅ **Dark Mode UI** — Modern dark theme with blue accent colors  
✅ **Admin Edit Mode** — Password-protected editing for dynamic content updates  
✅ **Smooth Animations** — Hover effects and transitions for interactive feel  
✅ **SEO Optimized** — Proper semantic HTML structure  
✅ **Fast Performance** — Lightweight, no external dependencies  
✅ **Export to JSON** — Save your portfolio data locally  
✅ **Professional Styling** — Clean typography with Google Fonts (Inter & JetBrains Mono)  

---

## 🏗️ Main Components

### 1. **Navigation Bar** (`<nav>`)
- Fixed header with your name/logo
- Quick navigation links to all sections
- Admin button to toggle edit mode
- Responsive menu for mobile devices

### 2. **Hero Section** (`#hero`)
- Eye-catching introduction with your name
- Professional headline with animated cursor effect
- Call-to-action buttons (e.g., "Download Resume", "View Work")
- Badge for current role/status

### 3. **About / What I Do Section** (`#about`)
- Skill tags grid showing your technical expertise
- Easy to add/remove skills in edit mode
- Color-coded with blue accent highlights

### 4. **Projects Section** (`#projects`)
- **Grid layout** displaying your portfolio projects
- Each project card shows:
  - Project name & number
  - Description
  - Technology tags
  - Optional link to live project or GitHub repo
- Click to open project links
- Hover effects for better UX

### 5. **Certifications Section** (`#certifications`)
- Displays achieved certifications and badges
- Each cert card includes:
  - Certification icon
  - Certification name
  - Issuing organization
  - Optional link to credential

### 6. **Coding Profiles Section** (`#profiles`)
- Links to your coding platforms:
  - GitHub, LeetCode, CodeForces, etc.
  - Custom platform cards with handles
  - Direct links to your profiles

### 7. **Contact Section** (`#contact`)
- Centralized contact information
- Links to email, LinkedIn, Twitter, etc.
- Professional call-to-action card

### 8. **Footer**
- Copyright and attribution
- Links to GitHub or personal website

---

## 🚀 Getting Started

### 1. **Clone the Repository**
```bash
git clone https://github.com/tejasss77/Portfolio.git
cd Portfolio
```

### 2. **Open in Browser**
Simply open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# Or drag the file into your browser
```

### 3. **Deploy Online**
- **GitHub Pages**: Push to GitHub and enable Pages in repository settings
- **Netlify**: Drag & drop the `index.html` file
- **Vercel**: Import the repository
- **Any Static Host**: Upload `index.html` to your web server

---

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main portfolio file (all-in-one)
├── README.md           # This file
└── .gitignore          # Git ignore rules
```

**Note:** This is a single-file portfolio for simplicity. All HTML, CSS, and JavaScript are contained in `index.html`.

---

## 🔐 Admin Edit Mode

Your portfolio includes a **password-protected admin panel** for easy editing:

### How to Use:
1. Click the **⚙ admin** button in the navigation bar
2. Enter the admin password
3. Once unlocked, editable fields will show a **dashed blue border**
4. Click any field to edit (name, description, links, etc.)
5. **Click the field again** to finish editing
6. Use the **Save** button to persist changes locally
7. Use the **Export** button to download your data as JSON

### Features:
- **Add Projects** — New project cards with custom tech tags
- **Add Certifications** — Add new certifications with links
- **Add Profiles** — Link to coding platforms
- **Delete Items** — Remove unwanted entries with the delete button
- **Edit in Place** — All editable fields support inline editing
- **Data Persistence** — Changes are saved to browser's local storage

---

## 🎨 Customization Guide

### Change Colors
Edit the CSS variables in the `<style>` tag (lines 21-36):
```css
:root {
  --bg: #0a0a0f;          /* Background color */
  --blue: #3b82f6;        /* Primary accent color */
  --text: #f0f0f5;        /* Text color */
  /* ... more variables */
}
```

### Update Your Information
Search for these sections in the HTML and replace with your details:
- **Name**: `<div class="nav-logo">Tejas Sonar</div>`
- **About**: Hero section description
- **Projects**: Add/remove project cards
- **Contact Info**: Email, social links, etc.

### Add Your Own Fonts
Replace the Google Fonts link (line 9-11) with your preferred fonts:
```html
<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT:wght@400;700&display=swap" rel="stylesheet">
```

### Responsive Adjustments
Mobile styles are at the bottom of the CSS (line 938+). Adjust breakpoints as needed.

---

## 🔑 Admin Password

The default admin password can be set/changed in the JavaScript code. Look for the password validation logic to customize it.

---

## 📱 Browser Support

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Mobile Browsers (iOS Safari, Chrome Mobile)

---

## 📝 Tips & Best Practices

1. **Keep It Updated** — Regularly update projects and skills
2. **Optimize Images** — Use compressed images for faster loading
3. **Test Responsiveness** — Check on mobile and tablet devices
4. **Export Backups** — Regularly export your data to JSON
5. **Custom Domain** — Link your own domain for professionalism

---

## 📄 License

No license has been specified yet. Feel free to use this for personal or commercial projects.

---

## 🤝 Contributing

Want to improve this portfolio? Feel free to:
- Fork the repository
- Make your changes
- Submit a pull request

---

## 💡 Future Enhancements

Potential features to add:
- Blog section for articles
- Dark/Light theme toggle
- Analytics integration
- Resume PDF download
- Testimonials section

---

## 📧 Contact

For questions or feedback, reach out through the contact section on the portfolio!

---

**Built with ❤️ by Tejas Sonar**
