# PT. Raya Filter Konsep - Company Profile Website

A modern, responsive company profile website for PT. Raya Filter Konsep, showcasing their air and oil filtration solutions from EMW Filtertechnik (Germany) and SKF RecondOil (Sweden).

## Features

### 🎨 Design & User Experience
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Accessibility**: WCAG compliant with proper focus management
- **Performance**: Optimized for fast loading and smooth interactions

### 🚀 Technical Features
- **HTML5 & CSS3**: Modern semantic markup and styling
- **Tailwind CSS**: Utility-first CSS framework for rapid development
- **Vanilla JavaScript**: Enhanced interactivity without heavy frameworks
- **Progressive Web App**: Service worker for offline functionality
- **AOS Animations**: Smooth scroll-triggered animations
- **SEO Optimized**: Meta tags and structured data

### 📱 Sections Included
1. **Homepage (Beranda)** - Hero section with company introduction
2. **About Us (Tentang Kami)** - Company history, vision, and mission
3. **Products & Solutions (Produk & Solusi)** - EMW and SKF product showcase
4. **Industries & Applications (Industri & Aplikasi)** - Use cases and client portfolio
5. **Sustainability (Keberlanjutan)** - Environmental commitment
6. **Contact Us (Kontak)** - Contact form and company information

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Basic web server (optional, for local development)

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. For local development with a server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

### File Structure
```
rayafilter/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── custom.css      # Custom styles
│   └── js/
│       └── main.js         # JavaScript functionality
├── sw.js                   # Service Worker (PWA)
└── README.md               # This file
```

## Customization

### Company Information
Update the following sections in `index.html`:
- Company address in the contact section
- Email and phone number
- Social media links
- Add actual client logos

### Branding
- Update color scheme in Tailwind config (primary, secondary, accent colors)
- Replace placeholder images with actual product images
- Add company logo

### Content
- Translate or modify text content as needed
- Add actual product specifications
- Include real client testimonials

## Technologies Used

- **HTML5**: Semantic markup and structure
- **Tailwind CSS**: Utility-first CSS framework
- **JavaScript (ES6+)**: Modern JavaScript features
- **Font Awesome**: Icon library
- **AOS**: Animate On Scroll library
- **Google Fonts**: Inter font family

## Performance Optimizations

- **Lazy Loading**: Images load only when needed
- **Critical CSS**: Inline critical styles
- **Minified Assets**: Compressed CSS and JS files
- **Responsive Images**: Optimized for different screen sizes
- **Service Worker**: Caching for offline functionality

## Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## SEO Features

- Semantic HTML structure
- Meta tags for social sharing
- Structured data markup
- Optimized images with alt text
- Clean URL structure

## Accessibility

- WCAG 2.1 AA compliant
- Keyboard navigation support
- Screen reader compatible
- High contrast mode support
- Reduced motion preferences

## Development

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding navigation link
3. Style with Tailwind classes or custom CSS
4. Add JavaScript functionality if needed

### Customizing Animations
- Modify AOS settings in `main.js`
- Add custom animations in `custom.css`
- Use CSS transforms for performance

### Form Integration
The contact form is currently set up for frontend display. To make it functional:
1. Set up a backend endpoint (PHP, Node.js, etc.)
2. Update the form action and method
3. Add proper validation and sanitization
4. Configure email sending functionality

## Deployment

### Static Hosting
- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **GitHub Pages**: Free hosting for static sites
- **AWS S3**: Scalable static hosting

### Custom Server
- Upload files to web server
- Ensure proper MIME types are configured
- Set up SSL certificate for HTTPS
- Configure caching headers

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Support

For support or questions about this website:
- Email: [your-email@domain.com]
- Phone: [your-phone-number]

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

---

**Built with ❤️ for PT. Raya Filter Konsep**