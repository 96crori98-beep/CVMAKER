# ResumeForge 🚀

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/yourusername/resumeforge.svg)](https://github.com/yourusername/resumeforge/stargazers)

> **Free, open-source resume builder with ATS-friendly templates. Create professional resumes in minutes - no signup required.**

🌐 **Live Demo**: [https://yourusername.github.io/resumeforge](https://yourusername.github.io/resumeforge)

![ResumeForge Preview](https://images.unsplash.com/photo-1586281380349-632531db7ed4?w=800&h=400&fit=crop)

## ✨ Features

- 🎨 **Professional Templates** - Choose from multiple ATS-friendly resume designs
- ⚡ **Lightning Fast** - Build your resume in under 10 minutes
- 🔒 **100% Private** - Your data never leaves your browser
- 💯 **Free Forever** - No hidden fees, no subscriptions
- 📱 **Mobile Responsive** - Works perfectly on all devices
- 🎯 **ATS Optimized** - Passes applicant tracking systems
- 📄 **PDF Export** - Download high-quality PDFs instantly
- 🌙 **Auto-Save** - Never lose your progress

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. Fork this repository
2. Go to **Settings** → **Pages**
3. Select **Deploy from a branch** → **main** → **/(root)**
4. Your site will be live at `https://yourusername.github.io/resumeforge`

### Option 2: Local Development

```bash
# Clone the repository
git clone https://github.com/yourusername/resumeforge.git

# Navigate to the directory
cd resumeforge

# Open in your browser (or use a local server)
open index.html
```

### Option 3: Netlify/Vercel

Simply drag and drop the `index.html` file to [Netlify Drop](https://app.netlify.com/drop) or [Vercel](https://vercel.com).

## 🛠️ Customization

### Changing Colors

Edit the CSS variables in the `<style>` section:

```css
:root {
    --primary: #2563eb;        /* Main brand color */
    --primary-dark: #1d4ed8;   /* Hover state */
    --dark: #111827;           /* Text color */
    /* ... more variables */
}
```

### Adding Templates

1. Find a template image (recommended: 600x400px)
2. Add a new `<article class="template-card">` in the Templates section
3. Update the template name, description, and tags

### Updating Content

- **Hero Section**: Edit the text inside `.hero-content`
- **Features**: Add/remove `<article class="feature-card">` elements
- **FAQ**: Add/remove `<details class="faq-item">` elements
- **Testimonials**: Update the `.testimonial-card` elements

### SEO Configuration

Update these meta tags in the `<head>`:

```html
<title>Your Brand | Free Resume Builder</title>
<meta name="description" content="Your custom description">
<link rel="canonical" href="https://yourdomain.com">
<meta property="og:url" content="https://yourdomain.com">
<meta property="og:image" content="https://yourdomain.com/og-image.jpg">
```

Also update the JSON-LD structured data for better search results.

## 📁 File Structure

```
resumeforge/
├── index.html          # Main landing page (single file)
├── README.md           # This file
└── LICENSE             # MIT License
```

> **Note**: This is a single-file solution. All CSS and JavaScript are inline for easy deployment.

## 🎯 SEO Optimizations Included

- ✅ Semantic HTML5 structure
- ✅ Meta tags (description, keywords, robots)
- ✅ Open Graph / Facebook Cards
- ✅ Twitter Cards
- ✅ JSON-LD Structured Data (SoftwareApplication, FAQPage)
- ✅ Canonical URLs
- ✅ Alt text for all images
- ✅ Mobile-responsive design
- ✅ Fast loading (no external dependencies except fonts)
- ✅ Accessibility features (skip links, focus states, ARIA labels)

## 📝 Adding Resume Editor Functionality

This landing page is designed to be extended with actual resume editing capabilities. To add an editor:

1. Create a new file `editor.html`
2. Add form fields for:
   - Personal Information
   - Work Experience
   - Education
   - Skills
   - Projects
3. Use localStorage to save data
4. Add print-to-PDF functionality using `window.print()` or a library like [html2pdf.js](https://github.com/eKoopmans/html2pdf.js)

### Example Editor Link

Replace the template buttons with:

```html
<a href="editor.html?template=executive" class="btn btn-outline-blue">
    Use This Template
</a>
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Inter Font](https://fonts.google.com/specimen/Inter) by Google Fonts
- [Unsplash](https://unsplash.com) for stock images
- Icons from [Heroicons](https://heroicons.com)

## 📧 Contact

- GitHub: [@yourusername](https://github.com/yourusername)
- Email: your.email@example.com

---

<p align="center">Made with ❤️ for job seekers everywhere</p>
