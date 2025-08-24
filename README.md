# 🌟 Sanjay Sajnani - Portfolio Website

A modern, responsive portfolio website showcasing full-stack web development skills with elegant design and smooth animations.

## 🎨 Features

### ✨ Design & User Experience
- **Modern Retro Aesthetic** - Elegant amber/gold color scheme with vintage-inspired design elements
- **Fully Responsive** - Seamless experience across desktop, tablet, and mobile devices
- **Dark/Light Mode Toggle** - Smooth theme switching with user preference persistence
- **Smooth Animations** - AOS (Animate On Scroll) library for engaging scroll-triggered animations
- **Glassmorphism Effects** - Modern glass card designs with backdrop blur effects

### 🛠 Technical Implementation
- **Vanilla HTML/CSS/JavaScript** - No framework dependencies for optimal performance
- **Tailwind CSS** - Utility-first CSS framework for rapid styling
- **Custom CSS Properties** - Advanced styling with CSS variables and custom properties
- **Mobile-First Design** - Progressive enhancement from mobile to desktop
- **Performance Optimized** - Minimal dependencies and optimized asset loading

### 🎯 Sections
- **Hero Section** - Introduction with animated avatar and gradient backgrounds
- **About Me** - Professional summary and personal brand
- **Technical Skills** - Interactive skill pills showcasing technology expertise
- **Featured Projects** - Showcase of key projects with live demo links
- **Work Experience** - Professional timeline with detailed achievements
- **Contact** - Multiple contact methods with social links

## 🚀 Live Demo

[View Portfolio](https://your-portfolio-url.com) *(Replace with your actual URL)*

## 📸 Screenshots

### Light Mode
![Light Mode Screenshot](./screenshots/light-mode.png)

### Dark Mode
![Dark Mode Screenshot](./screenshots/dark-mode.png)

## 🛠 Technologies Used

### Frontend
- **HTML5** - Semantic markup and modern web standards
- **CSS3** - Advanced styling with flexbox, grid, and custom properties
- **JavaScript (ES6+)** - Modern JavaScript features and DOM manipulation
- **Tailwind CSS** - Utility-first CSS framework

### Libraries & Tools
- **AOS (Animate On Scroll)** - Scroll-triggered animations
- **Google Fonts** - Space Grotesk and Inter font families
- **CSS Custom Properties** - Dynamic theming and color management

### Design Features
- **Responsive Grid Layouts** - CSS Grid and Flexbox for responsive design
- **CSS Transitions & Animations** - Smooth hover effects and state changes
- **Backdrop Filters** - Modern glassmorphism effects
- **Color Scheme Management** - CSS custom properties for theme switching

## 📁 Project Structure

```
portfolio/
│
├── index.html              # Main HTML file
├── README.md              # Project documentation
├── screenshots/           # Portfolio screenshots
│   ├── light-mode.png
│   └── dark-mode.png
│
└── assets/ (optional)
    ├── images/           # Profile images and project screenshots
    └── icons/            # Custom icons and favicons
```

## 🎨 Color Palette

### Light Mode
- **Primary**: `#daa520` (Golden)
- **Secondary**: `#8b4513` (Saddle Brown)
- **Background**: `#fefcf7` (Warm White)
- **Text**: `#92400e` (Amber 800)
- **Accent**: `#cd853f` (Peru)

### Dark Mode
- **Primary**: `#f4d03f` (Light Golden)
- **Secondary**: `#b8860b` (Dark Golden)
- **Background**: `#0a0a0a` (Rich Black)
- **Text**: `#fbbf24` (Amber 400)
- **Accent**: `#f59e0b` (Amber 500)

## ⚙️ Installation & Setup

### Quick Start
1. **Clone the repository**
   ```bash
   git clone https://github.com/TELIBO/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   ```bash
   # Option 1: Direct file opening
   open index.html
   
   # Option 2: Using a local server (recommended)
   python -m http.server 8000
   # or
   npx serve .
   ```

3. **Access the portfolio**
   - Direct file: Open `index.html` in your browser
   - Local server: Visit `http://localhost:8000`

### Development Setup
For development with live reload:

```bash
# Using VS Code Live Server extension
# 1. Install "Live Server" extension
# 2. Right-click index.html
# 3. Select "Open with Live Server"

# Or using Node.js live-server
npm install -g live-server
live-server
```

## 🎯 Customization Guide

### 1. Personal Information
Edit the following sections in `index.html`:

```html
<!-- Hero Section -->
<h1>Your Name</h1>
<div>Your Title</div>

<!-- About Section -->
<p>Your professional summary...</p>

<!-- Contact Section -->
<a href="mailto:your-email@gmail.com">Email Me</a>
<a href="https://linkedin.com/in/your-profile">LinkedIn</a>
<a href="https://github.com/your-username">GitHub</a>
```

### 2. Skills & Technologies
Update the skills section with your technologies:

```html
<span class="skill-pill">Your Technology</span>
```

### 3. Projects
Replace project information:

```html
<a href="your-project-url" target="_blank" class="group glass-card">
  <div class="modern-heading text-3xl font-bold">Project Name</div>
  <div class="mb-6">Tech Stack</div>
  <p>Project description...</p>
</a>
```

### 4. Color Customization
Modify CSS custom properties in the `<style>` section:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --background-color: #your-color;
}
```

### 5. Profile Image
Replace the avatar placeholder:

```html
<!-- Current placeholder -->
<div class="mx-auto h-42 w-52 rounded-full border-4">
  <span class="text-6xl font-bold">SS</span>
</div>

<!-- With actual image -->
<img src="path/to/your/image.jpg" 
     alt="Your Name" 
     class="mx-auto h-42 w-52 rounded-full border-4" />
```

## 📱 Responsive Breakpoints

- **Mobile**: `< 640px` - Single column layout, stacked navigation
- **Tablet**: `640px - 1024px` - Adapted grid layouts, collapsible navigation
- **Desktop**: `> 1024px` - Full layout with side-by-side content
- **Large Desktop**: `> 1536px` - Max-width container with centered content

## ⚡ Performance Features

- **Optimized Assets** - Compressed images and minimal external dependencies
- **Efficient CSS** - Utility-based classes for reduced CSS bundle size
- **Lazy Loading** - AOS animations load on demand
- **Local Storage** - Theme preference persistence
- **Smooth Scrolling** - Hardware-accelerated CSS transitions

## 🌐 Browser Compatibility

- ✅ **Chrome** 90+
- ✅ **Firefox** 88+
- ✅ **Safari** 14+
- ✅ **Edge** 90+
- ⚠️ **IE 11** - Limited support (no CSS Grid, custom properties)

## 🔧 Troubleshooting

### Common Issues

1. **Dark mode not working**
   - Ensure JavaScript is enabled
   - Check browser console for errors
   - Verify localStorage permissions

2. **Animations not showing**
   - Check AOS library loading
   - Verify internet connection for CDN resources
   - Ensure `data-aos` attributes are present

3. **Responsive issues**
   - Verify Tailwind CSS is loading correctly
   - Check viewport meta tag in HTML head
   - Test with browser developer tools

4. **Font loading problems**
   - Verify Google Fonts CDN connection
   - Check for ad blockers blocking font requests
   - Ensure backup font families are specified

## 🚀 Deployment

### GitHub Pages
1. Push to GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Access via `https://username.github.io/repository-name`

### Netlify
1. Connect GitHub repository to Netlify
2. Set build command: (none needed)
3. Set publish directory: `/` (root)
4. Deploy automatically on git push

### Vercel
```bash
npm install -g vercel
vercel --prod
```

### Traditional Hosting
Upload all files to your hosting provider's public directory (usually `public_html`, `www`, or similar).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Sanjay Sajnani**
- Portfolio: [Live Site](https://your-portfolio-url.com)
- LinkedIn: [sanjay-sajnani](https://linkedin.com/in/sanjay-sajnani)
- GitHub: [@TELIBO](https://github.com/TELIBO)
- Email: sanjaysajnani2005@gmail.com

## 🙏 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [AOS Library](https://michalsnik.github.io/aos/) for scroll animations
- [Google Fonts](https://fonts.google.com/) for typography
- [Heroicons](https://heroicons.com/) for beautiful icons
- Design inspiration from modern portfolio trends

## 📈 Future Enhancements

- [ ] Add blog section with markdown support
- [ ] Implement contact form with backend integration
- [ ] Add project filtering and search functionality
- [ ] Include testimonials section
- [ ] Add progressive web app (PWA) features
- [ ] Implement analytics tracking
- [ ] Add multi-language support
- [ ] Include skills proficiency indicators

---

⭐ **Star this repository if you found it helpful!** ⭐
