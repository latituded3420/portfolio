# Salim Shaikh - Frontend Developer Portfolio

![Portfolio Website](https://img.shields.io/badge/Portfolio-Online-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-%2361DAFB?logo=react&logoColor=black)

## 🌟 Overview

A modern, responsive portfolio website showcasing my work as a Frontend Developer. Features include multi-language support (English, Spanish, French), dark/light theme toggle, smooth animations, and an interactive project showcase.

## ✨ Features

### ✅ Current Features
- **Multi-Language Support** - English, Spanish, and French translations
- **Dark/Light Mode** - Toggle between themes with local storage persistence
- **Smooth Animations** - Using Anime.js and AOS (Animate On Scroll)
- **Responsive Design** - Mobile-first approach, works on all devices
- **Particle Background** - Animated canvas background in hero section
- **Project Filtering** - Filter projects by category (Web, Mobile, Design)
- **Skill Progress Bars** - Animated skill level indicators
- **Contact Form** - Form validation with notification system
- **Social Links** - GitHub, LinkedIn, Email, and Resume links

### ⚙️ Tech Stack
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Animations**: Anime.js, AOS (Animate On Scroll)
- **Icons**: Font Awesome 6.4
- **Storage**: LocalStorage for theme and language preferences

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file with semantic markup
├── style.css           # Responsive CSS with dark mode support
├── script.js           # Main JavaScript functionality
├── languages.js        # Multi-language translation strings
├── email.js            # Email configuration (removed credentials)
├── assets/             # Images and media files
├── package.json        # Project dependencies
├── package-lock.json   # Locked dependencies
└── README.md           # Documentation
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Node.js (optional, for local development)

### Local Installation

1. Clone the repository:
```bash
git clone https://github.com/latituded3420/portfolio.git
cd portfolio
```

2. Open in browser:
```bash
# Using Python (Python 3)
python -m http.server 8000

# Or using Node.js with http-server
npx http-server
```

3. Visit `http://localhost:8000` in your browser

## 🌐 Live Demo

Visit the live portfolio: [https://latituded3420.github.io/portfolio](https://latituded3420.github.io/portfolio)

## 🎨 Customization

### Change Personal Information
Edit the following in `index.html`:
- Name and title in hero section
- About description
- Skills and proficiency levels
- Project details and links
- Social media links
- Contact email

### Modify Colors
Edit CSS variables in `style.css`:
```css
:root {
  --primary-color: #6c63ff;
  --secondary-color: #ff6b6b;
  /* ... other variables ... */
}
```

### Add More Languages
Edit `languages.js` and add new language translations, then update the language selector in `index.html`.

## 📋 Features Removed

### ❌ Security Fixes
- Removed hardcoded email credentials from `email.js`
- Removed backend email service integration (preventing credential exposure)
- Contact form now uses client-side validation only

### ❌ Optimizations
- Removed unnecessary commented EmailJS code
- Removed unused form fields (phone field)
- Cleaned up unused CSS classes

## 🔧 Development

### Available Scripts

```bash
# Install dependencies
npm install

# Run local server
npm start  # Requires http-server package

# Build for production
npm run build  # Creates optimized production build
```

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Features by Device

### Desktop
- Full navigation bar
- Hover effects on interactive elements
- Side-by-side layout for sections
- Particle background animation

### Tablet
- Optimized navigation (collapsible menu)
- Touch-friendly buttons
- Stacked layout for readability

### Mobile
- Hamburger menu navigation
- Optimized touch targets
- Single-column layout
- Responsive hero section

## 🔐 Security

- No sensitive credentials in codebase
- Client-side form validation only
- No external API integrations for contact form
- CORS-friendly static assets

## 📈 SEO Optimization

- Semantic HTML5 structure
- Meta tags for Open Graph
- Mobile-first responsive design
- Fast loading animations (defer non-critical)

## 🐛 Known Issues

None currently reported. Please open an issue if you find any bugs.

## 🤝 Contributing

Feel free to fork this repository and customize it for your own portfolio!

## 📝 License

This project is licensed under the MIT License - feel free to use it for your own portfolio.

## 📧 Contact

- **Email**: salimshaikh50113@gmail.com
- **LinkedIn**: [Salim Shaikh](https://www.linkedin.com/in/salim-shaikh-a78267281)
- **GitHub**: [latituded3420](https://github.com/latituded3420)
- **Location**: Pune, India

## 🙏 Acknowledgments

- [Anime.js](https://animejs.com/) - Animation library
- [AOS](https://michalsnik.github.io/aos/) - Scroll animation library
- [Font Awesome](https://fontawesome.com/) - Icon library
- Inspiration from modern portfolio designs

---

**Last Updated**: January 2026

Made with ❤️ by Salim Shaikh
