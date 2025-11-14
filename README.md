# Magic GPX Editor - Support Website

This folder contains the support website for Magic GPX Editor, designed to be hosted on GitHub Pages.

## 🚀 Deploying to GitHub Pages

### Method 1: Using the GitHub Web Interface

1. Push this repository to GitHub
2. Go to your repository's Settings
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select the branch (usually `main` or `master`)
6. Select the `/docs` folder
7. Click "Save"

Your site will be available at: `https://yourusername.github.io/repositoryname/`

### Method 2: Using GitHub CLI

```bash
# Initialize git repository (if not already done)
git init
git add .
git commit -m "Add support website"

# Create GitHub repository and push
gh repo create magic-gpx-editor --public --source=. --push
```

Then follow the web interface steps above to enable GitHub Pages.

## 📝 Customizing

### Update Links

Before deploying, update the GitHub links in `index.html`:

- Replace `yourusername` with your GitHub username
- Replace `magic-gpx-editor` with your repository name

Find these lines in `index.html`:
```html
<a href="https://github.com/yourusername/magic-gpx-editor/issues" class="button">Report an Issue</a>
<a href="https://github.com/yourusername/magic-gpx-editor" class="button secondary">View on GitHub</a>
```

### Styling

The website uses a modern, Apple-inspired design with:
- Gradient header (blue to purple)
- Card-based layout
- Responsive design for mobile devices
- Smooth animations and transitions

Modify `styles.css` to change colors, fonts, or layout.

## 🎨 Design Features

- ✨ Modern gradient design
- 📱 Fully responsive (mobile, tablet, desktop)
- ♿ Accessible markup
- 🎯 SEO optimized
- ⚡ Fast loading (no external dependencies)

## 📂 File Structure

```
docs/
├── index.html      # Main support page
├── styles.css      # Stylesheet
└── README.md       # This file
```

## 🔧 Local Development

To test locally, simply open `index.html` in a web browser, or use a local server:

```bash
# Using Python 3
cd docs
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## 📄 License

This website template is part of Magic GPX Editor.
