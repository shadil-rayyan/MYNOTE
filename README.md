# My Knowledge Base

A modern, searchable documentation site for all my notes and resources.

## 🚀 Features

- 📝 Markdown-based content
- 🔍 Instant search
- 🌓 Dark/Light mode
- 📱 Mobile responsive
- 🚀 Fast static site generation

## 🛠️ Setup

1. Install dependencies:
   ```bash
   pip install -r requirements-docs.txt
   ```

2. Run locally:
   ```bash
   mkdocs serve
   ```
   Then open http://localhost:8000 in your browser.

3. Build for production:
   ```bash
   mkdocs build
   ```
   The site will be in the `site/` directory.

## 📁 Project Structure

```
docs/
  ├── index.md          # Homepage
  ├── Python/           # Python notes
  ├── Project/          # Project documentation
  └── Todo/             # Todo lists by category
```

## 📝 Adding Content
- Add new Markdown files in the appropriate directory
- Update `mkdocs.yml` to include new pages in the navigation

## 🌐 Deployment
Deploy to any static hosting service like GitHub Pages, Netlify, or Vercel.

## 📄 License
MIT