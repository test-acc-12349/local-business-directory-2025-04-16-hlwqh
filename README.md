# Local Business Directory

![Local Business Directory Banner](assets/images/banner.png)

> Discover the best local businesses in one place - A comprehensive directory website featuring local businesses in a clean, responsive 3-column grid layout.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
  - [Adding Directory Items](#adding-directory-items)
  - [Modifying Categories](#modifying-categories)
  - [Updating Hero Section](#updating-hero-section)
  - [Styling Customization](#styling-customization)
- [Deployment](#deployment)
  - [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Support & Resources](#support--resources)

## Overview

Local Business Directory is a modern, responsive directory website template designed to showcase local businesses. Built with HTML5, CSS3, and JavaScript, it features a clean 3-column grid layout, search functionality, and category filtering.

## Features

- ✨ Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 📱 Mobile-friendly design
- 🖼️ Image optimization
- 🚀 Fast loading times
- 📊 SEO optimized
- 🎨 Customizable styling

## Getting Started

### Prerequisites

- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS
- Git (optional)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/local-business-directory.git
```

2. Navigate to project directory:
```bash
cd local-business-directory
```

3. Open `index.html` in your browser

## Directory Structure

```
local-business-directory/
├── index.html
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── responsive.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── listings/
│   └── data.json
└── README.md
```

## Customization Guide

### Adding Directory Items

1. Open `listings/data.json`
2. Add new business entry:
```json
{
  "id": "unique-id",
  "name": "Business Name",
  "category": "Category",
  "description": "Business description",
  "address": "Business address",
  "phone": "Phone number",
  "website": "Website URL",
  "image": "image-filename.jpg"
}
```
3. Add corresponding image to `assets/images/`

### Modifying Categories

1. Open `index.html`
2. Locate the categories section:
```html
<div class="categories">
  <button class="category-btn" data-category="all">All</button>
  <!-- Add/modify categories here -->
  <button class="category-btn" data-category="restaurants">Restaurants</button>
</div>
```

### Updating Hero Section

1. Open `index.html`
2. Locate the hero section:
```html
<section class="hero">
  <h1>Your Custom Title</h1>
  <p>Your custom description</p>
</section>
```

### Styling Customization

1. Open `assets/css/style.css`
2. Modify color variables:
```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
}
```

## Deployment

1. Upload files to your web host
2. Ensure all file permissions are set correctly
3. Test all functionality

### Custom Domain Setup

1. Purchase domain name
2. Update DNS records:
   - A record: Point to your hosting IP
   - CNAME record: www to your domain

## Troubleshooting

Common issues and solutions:

- **Images not loading**: Check file paths and permissions
- **Search not working**: Clear browser cache
- **Layout issues**: Verify CSS file is properly linked
- **Mobile responsiveness**: Test on multiple devices

## Support & Resources

- 📧 Email Support: support@example.com
- 📚 Documentation: [docs.example.com](https://docs.example.com)
- 💬 Community Forum: [forum.example.com](https://forum.example.com)
- 🐛 Issue Tracker: [GitHub Issues](https://github.com/yourusername/local-business-directory/issues)

---

## License

MIT License - See [LICENSE.md](LICENSE.md) for details

---

Made with ❤️ by [Your Name]

[⬆ back to top](#local-business-directory)