# Cybersecurity Portfolio Website

A modern, responsive portfolio website for cybersecurity professionals, penetration testers, and security researchers. Built with clean HTML5 and CSS3, optimized for GitHub Pages deployment.

## 🚀 Live Demo

Visit your portfolio at: `https://<your-username>.github.io/`

## ✨ Features

- **Modern Dark Theme**: Cybersecurity-focused aesthetic with accent colors
- **Fully Responsive**: Mobile-first design that works on all devices
- **SEO Optimized**: Meta tags, Open Graph, and Twitter Card support
- **Accessibility**: WCAG compliant with keyboard navigation and screen reader support
- **Performance**: Lightweight, no external dependencies
- **GitHub Pages Ready**: Deploy in seconds with zero configuration

## 📁 Project Structure

```
your-username.github.io/
├── index.html          # Main portfolio page
├── styles.css          # Responsive CSS styling
├── README.md           # This file
├── CNAME              # Custom domain configuration (optional)
└── assets/
    ├── resume.pdf      # Your resume (add your own)
    ├── pgp-key.asc     # PGP public key (optional)
    ├── favicon.ico     # Website icon
    └── images/
        └── social-preview.png  # Social media preview image
```

## 🛠️ Setup Instructions

### Option 1: Quick Setup (Recommended)

1. **Create Repository**
   ```bash
   # Create a new repository named exactly: your-username.github.io
   # Replace 'your-username' with your actual GitHub username
   ```

2. **Clone and Add Files**
   ```bash
   git clone https://github.com/your-username/your-username.github.io.git
   cd your-username.github.io
   
   # Copy the portfolio files to this directory
   # index.html, styles.css, README.md, and assets/ folder
   ```

3. **Customize Content**
   - Replace all `<Your Name>` placeholders with your name
   - Update `<your@email.com>` with your email
   - Update `<username>` with your GitHub username
   - Add your own content to portfolio and projects sections
   - Replace placeholder certifications with your actual ones

4. **Deploy**
   ```bash
   git add .
   git commit -m "Initial portfolio deployment"
   git push origin main
   ```

5. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

Your site will be live at `https://your-username.github.io` within a few minutes!

### Option 2: Fork and Customize

1. Fork this repository
2. Rename it to `your-username.github.io`
3. Customize the content
4. Enable GitHub Pages in settings

## 📝 Customization Guide

### Personal Information

Update these placeholders in `index.html`:

```html
<!-- Update these placeholders -->
<Your Name>           → Your actual name
<your@email.com>      → Your email address
<username>            → Your GitHub username
```

### Portfolio Content

1. **About Section**: Update the bio and skills
2. **Portfolio**: Replace with your actual case studies
3. **Projects**: Add your GitHub repositories and tools
4. **Certifications**: List your security certifications
5. **Contact**: Ensure all contact methods are correct

### Styling

Customize colors in `styles.css`:

```css
:root {
    --accent-color: #00ff9f;        /* Primary accent color */
    --accent-secondary: #ff6b6b;    /* Secondary accent color */
    --primary-bg: #0a0a0a;          /* Main background */
    --secondary-bg: #1a1a1a;        /* Section backgrounds */
    /* Modify other variables as needed */
}
```

### Adding Your Assets

1. **Resume**: Add `resume.pdf` to the `assets/` folder
2. **PGP Key**: Add `pgp-key.asc` to the `assets/` folder (optional)
3. **Images**: Add profile photos, project screenshots to `assets/images/`
4. **Favicon**: Replace `assets/favicon.ico` with your own

## 🌐 Custom Domain Setup

To use a custom domain (e.g., `yourname.com`):

1. **Create CNAME file**
   ```bash
   echo "yourname.com" > CNAME
   git add CNAME
   git commit -m "Add custom domain"
   git push
   ```

2. **Configure DNS**
   - For apex domain (`yourname.com`):
     ```
     A    185.199.108.153
     A    185.199.109.153
     A    185.199.110.153
     A    185.199.111.153
     ```
   
   - For subdomain (`www.yourname.com`):
     ```
     CNAME    your-username.github.io
     ```

3. **Update GitHub Settings**
   - Go to repository settings → Pages
   - Add your custom domain
   - Enable "Enforce HTTPS"

## 🔧 Development

### Local Development

```bash
# Serve locally (requires Python)
python -m http.server 8000

# Or with Node.js
npx http-server

# Or with PHP
php -S localhost:8000
```

Visit `http://localhost:8000` to preview your site.

### Content Guidelines

**Portfolio Entries**:
- Sanitize sensitive information
- Use generic company descriptions
- Focus on technical achievements
- Include impact metrics where possible

**Projects**:
- Link to public repositories
- Include clear descriptions
- Add technology tags
- Show GitHub stars/forks if impressive

**Security Best Practices**:
- Don't expose sensitive client information
- Use responsible disclosure principles
- Keep PGP key up to date
- Regularly update contact information

## 📱 Browser Support

- ✅ Chrome/Edge (90+)
- ✅ Firefox (88+)
- ✅ Safari (14+)
- ✅ Mobile browsers
- ⚠️ Internet Explorer (not supported)

## 🎯 SEO Optimization

The site includes:

- Semantic HTML structure
- Meta descriptions and keywords
- Open Graph tags for social sharing
- Twitter Card support
- Structured data for search engines
- Optimized loading performance

## 🔒 Security Features

- Content Security Policy headers (configure in GitHub Pages)
- No external dependencies
- Secure HTTPS delivery via GitHub Pages
- PGP key integration for secure communication

## 📈 Analytics (Optional)

To add Google Analytics:

```html
<!-- Add before closing </head> tag -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🤝 Contributing

Feel free to:
- Report bugs
- Suggest improvements
- Submit pull requests
- Share feedback

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🆘 Troubleshooting

### Common Issues

**Site not loading after deployment**:
- Check repository name matches `your-username.github.io`
- Ensure GitHub Pages is enabled in settings
- Wait 5-10 minutes for initial deployment

**Custom domain not working**:
- Verify DNS configuration
- Check CNAME file content
- Ensure HTTPS is enforced in settings

**Styling issues**:
- Clear browser cache
- Check CSS file path in HTML
- Validate CSS syntax

**Mobile responsiveness**:
- Test on actual devices
- Use browser dev tools
- Check viewport meta tag

### Getting Help

- 📧 Check GitHub Issues for common problems
- 💬 GitHub Discussions for questions
- 📖 GitHub Pages documentation
- 🔍 Search Stack Overflow for specific issues

## 🎉 Success Checklist

- [ ] Repository created with correct name
- [ ] GitHub Pages enabled
- [ ] Personal information updated
- [ ] Portfolio content added
- [ ] Resume uploaded
- [ ] Social links working
- [ ] Mobile responsive
- [ ] Custom domain configured (optional)
- [ ] Analytics added (optional)
- [ ] SEO meta tags updated

---

**Built with ❤️ for the cybersecurity community**

Remember to keep your portfolio updated with new projects, certifications, and achievements. Good luck with your cybersecurity career!