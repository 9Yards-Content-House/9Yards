# 9Yards Content House - Coming Soon Website

A modern, responsive coming soon page for 9Yards Content House, a premier content creation agency.

## Features

- 📱 **Fully Responsive Design** - Optimized for all devices from mobile to desktop
- ⏰ **Interactive Countdown Timer** - Dynamic countdown to launch date
- 🎨 **Modern UI/UX** - Clean, professional design with smooth animations
- 🚀 **Performance Optimized** - Fast loading with optimized assets
- 📈 **SEO Ready** - Proper meta tags, structured data, and sitemap
- ♿ **Accessible** - WCAG compliant with proper ARIA labels
- 🌐 **PWA Ready** - Progressive Web App manifest included

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with flexbox and grid
- **JavaScript/jQuery** - Interactive elements
- **Bootstrap** - Responsive framework
- **Font Awesome** - Social media icons
- **Web Fonts** - Poppins and Aldrich fonts

## Project Structure

```
├── index.html              # Main HTML file
├── manifest.json           # PWA manifest
├── sitemap.xml            # SEO sitemap
├── robots.txt             # Search engine directives
├── css/
│   ├── main.css           # Main styles
│   └── util.css           # Utility classes
├── js/
│   └── main.js            # Custom JavaScript
├── images/
│   ├── bg01.jpg           # Background image
│   └── icons/             # Logos and icons
├── fonts/                 # Custom fonts
└── vendor/                # Third-party libraries
```

## Setup and Deployment

1. **Local Development**
   ```bash
   # Clone or download the project
   # Open index.html in a web browser
   # Or use a local server like Live Server
   ```

2. **Deployment**
   - Upload all files to your web server
   - Ensure proper MIME types are configured
   - Update URLs in meta tags if needed

## Customization

### Countdown Timer
Update the countdown end date in `index.html`:
```javascript
$(".cd100").countdown100({
    endtimeYear: 2025,
    endtimeMonth: 9,
    endtimeDate: 1,
    // ...
});
```

### Social Media Links
Update social media URLs in the navigation section of `index.html`.

### Colors and Branding
Main colors are defined in CSS custom properties in `main.css`:
- Primary: `#E6411C` (Orange)
- Secondary: `#212282` (Blue)

## Performance

- ✅ Optimized images and fonts
- ✅ Critical CSS inlined
- ✅ Non-critical CSS loaded asynchronously
- ✅ Proper resource preloading
- ✅ Minified vendor libraries

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest) 
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Contact

For questions about this project, contact:
- Website: https://9yards.co.ug
- Instagram: [@9_yards_content_house_](https://www.instagram.com/9_yards_content_house_/)
- TikTok: [@9.yards.content.house](https://www.tiktok.com/@9.yards.content.house)
- YouTube: [@9Yards-ch](https://www.youtube.com/@9Yards-ch)
- Facebook: [9yardscontenthouse](https://www.facebook.com/9yardscontenthouse)

## License

© 2025 9Yards Content House. All rights reserved.