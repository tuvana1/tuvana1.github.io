# Personal Website - Apple UI Design

A clean, minimalist personal website built with Apple's UI design principles. Features a floating navigation bar, smooth animations, and responsive design.

## Features

- **Apple-inspired Design**: Clean typography, subtle shadows, and minimalist aesthetic
- **Floating Navigation**: Glassmorphism navigation bar with backdrop blur
- **Smooth Animations**: Subtle hover effects and scroll-triggered animations
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Accessibility**: Keyboard navigation and focus states
- **Modern CSS**: Uses CSS Grid, Flexbox, and modern CSS features

## File Structure

```
personal website/
├── index.html          # Main HTML structure
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Local development**: Use a local server for best experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

## Customization

### Personal Information

Edit `index.html` to update your personal details:

```html
<!-- Update name -->
<h1 class="name">Your Name</h1>

<!-- Update tagline -->
<p class="tagline">
    Your tagline here with <span class="highlight">highlighted</span> text.
</p>

<!-- Update experience -->
<p class="experience">Previously @ Your Company + other experience</p>
```

### Colors and Styling

Modify `styles.css` to customize the design:

```css
/* Primary colors */
:root {
    --primary-color: #007aff;      /* Apple blue */
    --text-color: #1d1d1f;         /* Dark gray */
    --highlight-color: #8e44ad;    /* Purple accent */
    --background-color: #ffffff;    /* White background */
}
```

### Social Links

Update the social links in `index.html`:

```html
<div class="social-links">
    <a href="https://linkedin.com/in/yourprofile" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="mailto:your.email@example.com" class="social-link">
        <i class="fas fa-envelope"></i>
    </a>
</div>
```

### Resume Download

Update the download functionality in `script.js`:

```javascript
downloadBtn.addEventListener('click', function() {
    // Replace with your actual resume file
    window.open('path/to/your/resume.pdf', '_blank');
});
```

## Design Principles

This website follows Apple's design philosophy:

1. **Clarity**: Clean typography and generous white space
2. **Deference**: Content-focused design with subtle UI elements
3. **Depth**: Layered elements with appropriate shadows and blur effects
4. **Accessibility**: High contrast ratios and keyboard navigation
5. **Responsiveness**: Fluid layouts that adapt to different screen sizes

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance

The website is optimized for performance:
- Minimal JavaScript
- Efficient CSS animations
- Optimized font loading
- Responsive images (when added)

## Deployment

You can deploy this website to any static hosting service:

- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Connect your repository to Vercel
- **AWS S3**: Upload files to an S3 bucket with static website hosting

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to submit issues and enhancement requests!

---

Built with ❤️ following Apple's design principles 