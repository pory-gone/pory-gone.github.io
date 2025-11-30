---
title: "How This Site Was Built"
date: 2025-11-30
draft: true
description: "A guide on how I built this site with Hugo"
tags: ["hugo", "tutorial", "web development"]
---

# How I Built This Site with Hugo

This site is built with **Hugo**, an incredibly fast static site generator written in Go.

## Why Hugo?

Hugo offers several advantages:

- ⚡ **Speed**: Incredibly fast builds
- 🎨 **Flexibility**: Total control over layouts
- 📝 **Markdown**: Write content in Markdown
- 🆓 **Free**: 100% open source
- 🚀 **GitHub Pages**: Easy deployment

## Installation

```bash
# On Linux
sudo apt install hugo

# On macOS
brew install hugo

# On Windows
choco install hugo
```

## Creating a New Site

```bash
hugo new site my-site
cd my-site
```

## Project Structure

```
my-site/
├── archetypes/     # Content templates
├── assets/         # CSS, JS, images to be processed
├── content/        # Your markdown content
├── layouts/        # HTML templates
├── static/         # Static files (copied as-is)
└── hugo.toml       # Configuration file
```

## Custom Styling

For this site, I created a custom glitchy theme inspired by Porygon with:

- Custom CSS in `assets/css/main.css`
- Pink and cyan color palette
- Glitch animations and effects
- Responsive design

## Deployment to GitHub Pages

The site automatically deploys to GitHub Pages using GitHub Actions whenever I push to the main branch.

## Tips

- Use `hugo server -D` to preview with drafts
- Use `hugo new posts/my-post.md` to create new posts
- Keep your layouts modular and reusable
- Test locally before pushing

Hugo is perfect for blogs, portfolios, and documentation sites!
