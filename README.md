# README.md for improved portfolio

# Joshua Hamilton-Brown - Portfolio Website

[![Jekyll Build Status](https://github.com/joshuarhb/joshuarhb.github.io/workflows/Build%20and%20Deploy/badge.svg)](https://github.com/joshuarhb/joshuarhb.github.io/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This is the source code for my personal portfolio website, built with Jekyll and hosted on GitHub Pages.

## 🌐 Live Site

Visit the live site at: [https://joshuarhb.github.io](https://joshuarhb.github.io)

## 🚀 Features

- **Responsive Design**: Mobile-first approach with excellent cross-device compatibility
- **Modern Jekyll Setup**: Built with Jekyll 4.x and Minimal Mistakes theme
- **SEO Optimized**: Comprehensive meta tags, structured data, and search engine optimization
- **Performance Focused**: Optimized images, compressed assets, and fast loading times
- **Accessibility**: WCAG compliance considerations and keyboard navigation support
- **Blog Integration**: Full-featured blog with categories, tags, and search functionality
- **Social Integration**: Links to professional profiles and social sharing capabilities

## 🛠️ Tech Stack

- **Static Site Generator**: Jekyll 4.x
- **Theme**: Minimal Mistakes
- **Hosting**: GitHub Pages
- **Styles**: SCSS/Sass
- **JavaScript**: Vanilla JS with progressive enhancement
- **Build Process**: GitHub Actions (automatic deployment)

## 🏗️ Local Development

### Prerequisites

- Ruby 2.7+ 
- Bundler
- Git

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/joshuarhb/joshuarhb.github.io.git
   cd joshuarhb.github.io
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run locally**
   ```bash
   bundle exec jekyll serve --livereload
   ```

4. **View in browser**
   Open [http://localhost:4000](http://localhost:4000)

### Development Commands

```bash
# Serve with live reload (development)
bundle exec jekyll serve --livereload

# Build for production
bundle exec jekyll build

# Clean build files
bundle exec jekyll clean

# Check for outdated gems
bundle outdated

# Update gems
bundle update
```

## 📁 Project Structure

```
├── _config.yml          # Site configuration
├── _data/               # Data files (navigation, etc.)
├── _includes/           # Reusable components
├── _layouts/            # Page templates
├── _pages/              # Static pages (About, Projects, etc.)
├── _posts/              # Blog posts
├── _sass/               # Sass stylesheets
├── assets/              # Images, CSS, JS
│   ├── css/
│   ├── js/
│   └── images/
├── Gemfile              # Ruby dependencies
├── robots.txt           # Search engine instructions
└── README.md           # This file
```

## 🎨 Customization

### Colors and Styling

The site uses the "contrast" skin from Minimal Mistakes. Custom styles are added in:
- `assets/css/main.scss` - Main stylesheet with custom enhancements
- `_sass/` directory - Additional Sass partials if needed

### Content Management

- **Pages**: Add new pages in `_pages/` directory
- **Blog Posts**: Create new posts in `_posts/` with format `YYYY-MM-DD-title.md`
- **Navigation**: Edit `_data/navigation.yml`
- **Site Settings**: Modify `_config.yml`

### Adding New Features

1. **Comments**: Configure Disqus, Utterances, or Giscus in `_config.yml`
2. **Analytics**: Add Google Analytics tracking ID
3. **Search**: Already enabled with Lunr.js
4. **Social Sharing**: Configure share buttons in theme settings

## 🔧 Configuration Highlights

### SEO & Performance
- Comprehensive meta tags and Open Graph data
- XML sitemap generation
- robots.txt for search engine guidance
- Compressed HTML and CSS
- Optimized image formats

### Accessibility
- Semantic HTML structure
- Keyboard navigation support
- Alt text for images
- Focus indicators
- Screen reader friendly

### Security
- HTTPS enforcement (GitHub Pages default)
- Content Security Policy ready
- No inline JavaScript execution
- Secure external link handling

## 📱 Browser Support

- Chrome/Chromium (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch. No manual deployment required.

### Deployment Process
1. Push changes to `main` branch
2. GitHub Actions runs Jekyll build
3. Built site is deployed to `gh-pages` branch
4. Changes are live within minutes

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

While this is a personal portfolio, I welcome:
- Bug reports and fixes
- Suggestions for improvements
- Questions about implementation

Please open an issue or submit a pull request.

## 📬 Contact

- **Email**: [me@joshuarhb.com](mailto:me@joshuarhb.com)
- **GitHub**: [@joshuarhb](https://github.com/joshuarhb)
- **LinkedIn**: [/in/joshuarhb](https://linkedin.com/in/joshuarhb)
- **Website**: [joshuarhb.github.io](https://joshuarhb.github.io)

## 🙏 Acknowledgments

- [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme by Michael Rose
- [Jekyll](https://jekyllrb.com/) static site generator
- [GitHub Pages](https://pages.github.com/) for hosting
- Icons by [Font Awesome](https://fontawesome.com/)

---

*Last updated: January 2025*<- Added 27 new files with professional content and Force rebuild Thu Jan  8 18:53:11 EET 2026 -->
