# Blend Vocal Association of Calgary

A welcoming community choir website built with Jekyll and hosted on GitHub Pages.

## 🚀 Quick Start

### Prerequisites

- **Ruby** (version 3.0 or higher)
- **RubyGems** (usually comes with Ruby)
- **Git**

### Local Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/BlendVocal.git
   cd BlendVocal
   ```

2. **Install Ruby dependencies**
   ```bash
   bundle install
   ```

3. **Start the local development server**
   ```bash
   bundle exec jekyll serve
   ```

4. **View your site**
   Open your browser and navigate to `http://localhost:4000`

### Development Commands

- **Start development server with live reload:**
  ```bash
  bundle exec jekyll serve --livereload
  ```

## 📁 Project Structure

```
BlendVocal/
├── _config.yml          # Jekyll configuration
├── _data/               # Site data files
│   └── navigation.yml   # Navigation menu
├── _pages/              # Page content
│   ├── about.md         # About page
│   ├── auditions.md     # Auditions page
│   └── home.md          # Home page
├── _site/               # Generated site (don't edit)
├── assets/              # Static assets (CSS, JS, images)
├── Gemfile              # Ruby dependencies
└── CNAME                # Custom domain configuration
```

## 🛠️ Making Changes

### Adding/Editing Pages

1. **Create a new page:**
   - Add a new `.md` file in the `_pages/` directory
   - Use the following front matter format:
   ```yaml
   ---
   title: "Page Title"
   permalink: /page-url/
   ---
   ```

2. **Edit existing pages:**
   - Modify files in the `_pages/` directory
   - Changes will automatically reload in development

### Updating Navigation

Edit `_data/navigation.yml` to modify the site navigation menu.

### Styling and Assets

- CSS files are in `assets/css/`
- JavaScript files are in `assets/js/`
- Images should be placed in `assets/img/`

## 🚀 Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

### Manual Deployment

1. **Commit your changes:**
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

2. **GitHub Pages will automatically build and deploy your site**

### Custom Domain

The site is configured with a custom domain (`blendvocal.ca`). The `CNAME` file contains the domain configuration.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## 📄 License

This project is for the Blend Vocal Association of Calgary.

---

**Need help?** Contact mahtabsabet
