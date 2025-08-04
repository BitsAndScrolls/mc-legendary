# Minecraft Legendary Edition Wiki

A comprehensive, modern wiki for the Minecraft Legendary Edition modpack featuring 170+ carefully selected mods for the ultimate adventure experience.

## 🚀 Quick Start

This wiki is designed to be hosted on GitHub Pages for free. Follow these steps to set up your own copy:

### 1. Repository Setup

```bash
# Clone or fork this repository
git clone [your-repo-url]
cd legendary-edition-wiki

# Or create a new repository with these files
```

### 2. File Structure

```
legendary-edition-wiki/
├── index.html              # Main homepage
├── getting-started.html    # Getting started guide
├── mods.html              # Complete mod list
├── skills.html            # Skill system guide (to be created)
├── creatures.html         # Creature bestiary (to be created)
├── guides.html            # Advanced guides (to be created)
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── README.md              # This file
└── _config.yml            # Jekyll configuration (optional)
```

### 3. GitHub Pages Setup

1. Go to your repository settings on GitHub
2. Scroll down to "Pages" section
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"
6. Your wiki will be available at `https://yourusername.github.io/repository-name`

### 4. Customization

#### Update Content
- Edit HTML files to match your specific modpack configuration
- Update mod lists in `mods.html`
- Modify getting started guide based on your pack's difficulty/focus
- Add your own branding and styling

#### Styling
- All CSS is embedded in each HTML file for easy customization
- Modify CSS variables in `:root` section to change colors/theme
- Responsive design works on desktop, tablet, and mobile

#### Adding New Pages
1. Create new HTML file following the existing template structure
2. Update navigation links in all pages
3. Add appropriate content sections

## 🎨 Features

### ✨ Modern Design
- **Responsive Layout**: Works perfectly on all devices
- **Dark/Light Themes**: Easy to customize color schemes
- **Smooth Animations**: Engaging user experience with CSS animations
- **Interactive Elements**: Hover effects, smooth scrolling, collapsible sections

### 📱 User Experience
- **Search Functionality**: Real-time search across mod database
- **Filter System**: Category-based filtering for easy navigation
- **Table of Contents**: Auto-generated TOC with smooth scrolling
- **Progressive Disclosure**: Collapsible sections to reduce information overload

### 🔧 Technical Features
- **No Dependencies**: Pure HTML/CSS/JavaScript - no build process required
- **SEO Optimized**: Proper meta tags and semantic markup
- **Fast Loading**: Optimized assets and efficient code
- **Cross-Browser Compatible**: Works in all modern browsers

## 📝 Content Structure

### Homepage (`index.html`)
- Hero section with modpack overview
- Feature highlights
- Quick navigation cards
- Statistics and key information

### Getting Started (`getting-started.html`)
- Installation instructions
- First steps survival guide
- Skill system explanation
- Build recommendations
- Safety tips and warnings

### Mods List (`mods.html`)
- Searchable mod database
- Category filtering
- Featured mod highlights
- Detailed mod descriptions
- Links to mod pages

### Additional Pages (Template Ready)
- **Skills Guide**: Detailed breakdown of Reskillable and magic systems
- **Creature Bestiary**: Complete guide to dragons and legendary creatures
- **Advanced Guides**: Dragon hunting, magic mastery, endgame content

## 🎯 Customization Guide

### Color Scheme
Update CSS variables in any HTML file:

```css
:root {
    --primary-color: #2c3e50;    /* Main brand color */
    --accent-color: #e74c3c;     /* Accent/highlight color */
    --gold-color: #f39c12;       /* Special elements */
    --bg-light: #f8f9fa;         /* Light backgrounds */
    /* ... more variables */
}
```

### Adding Your Branding
1. Replace "Legendary Edition" with your modpack name
2. Update meta tags for SEO
3. Add your logo/favicon
4. Customize header gradients and styling

### Content Updates
- Mod lists: Update the mod cards in `mods.html`
- Installation: Modify installation steps for your pack
- Guides: Customize survival tips and progression paths
- Images: Add screenshots and mod-specific images

## 🛠️ Development

### Local Development
Simply open HTML files in your browser - no server required for basic functionality.

For advanced features (if you add them later):
```bash
# Optional: Use a simple HTTP server for testing
python -m http.server 8000
# Or
npx serve .
```

### Adding New Features
- **Search Enhancement**: Add more sophisticated search with fuzzy matching
- **Dark Mode Toggle**: Implement user-selectable themes
- **Comments System**: Integrate with GitHub Issues or external service
- **Analytics**: Add Google Analytics or similar tracking

### Performance Optimization
- **Image Optimization**: Compress images and use WebP format
- **CSS Minification**: Minify CSS for production
- **Lazy Loading**: Implement for mod cards and images
- **Caching**: Add service worker for offline functionality

## 📊 Analytics & Maintenance

### Recommended Analytics
- Google Analytics for visitor tracking
- GitHub repository insights for engagement
- User feedback through GitHub Issues

### Regular Updates
- Keep mod versions current
- Update guides based on user feedback
- Add new content as modpack evolves
- Monitor and fix broken links

## 🤝 Contributing

### For Modpack Users
- Report issues via GitHub Issues
- Suggest improvements and additions
- Submit corrections for mod information
- Share screenshots and experiences

### For Developers
- Fork the repository
- Create feature branches
- Submit pull requests
- Follow existing code style

## 📜 License

This wiki template is open source and free to use. Individual mod information belongs to their respective creators.

### Attribution
- Original design and development: [Your Name]
- Mod information: Various mod authors
- Minecraft: Mojang Studios

## 🔗 Links

- **Modpack Download**: [Add your modpack link]
- **Discord Community**: [Add discord invite]
- **Issue Tracker**: [GitHub Issues URL]
- **Mod Sources**: CurseForge, Modrinth

## 💡 Tips for Success

1. **Keep Content Updated**: Regular updates keep users engaged
2. **Encourage Community**: Enable discussions and feedback
3. **Mobile-First**: Most users browse on mobile devices
4. **Performance Matters**: Fast loading times improve user experience
5. **Search is Key**: Good search functionality is essential for large mod lists

---

**Ready to launch your wiki?** Simply upload these files to your GitHub repository and enable GitHub Pages!
