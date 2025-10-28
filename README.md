# BDMS Talk 2025 - McKinsey Style Presentation

A professional HTML presentation built with McKinsey's signature design style, featuring a clean blue color scheme and modern layout.

## Features

- **McKinsey Blue Color Scheme**: Professional blue gradient and styling matching McKinsey & Company brand
- **6 Professional Slides**: Title, Agenda, Key Message, Strategic Framework, Expected Impact, and Next Steps
- **Interactive Navigation**: 
  - Arrow buttons for next/previous slides
  - Keyboard navigation (Arrow keys, Space, Home, End)
  - Touch/swipe support for mobile devices
  - Progress bar showing presentation progress
- **Responsive Design**: Adapts to different screen sizes
- **Smooth Animations**: Slide transitions and hover effects
- **Print-Ready**: Optimized for printing all slides

## How to Use

### Opening the Presentation

1. **Simple Method**: Open `index.html` directly in any modern web browser
2. **With Local Server** (recommended):
   ```bash
   python3 -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser

### Navigation Controls

- **Next Slide**: Click → button, press Right Arrow, Down Arrow, or Space
- **Previous Slide**: Click ← button, press Left Arrow or Up Arrow
- **First Slide**: Press Home key
- **Last Slide**: Press End key
- **Fullscreen**: Double-click anywhere on the presentation
- **Touch Devices**: Swipe left/right to navigate

## File Structure

```
├── index.html    # Main presentation HTML
├── styles.css    # McKinsey-style CSS with blue color scheme
├── script.js     # JavaScript for navigation and interactivity
└── README.md     # This file
```

## Customization

### Colors

The presentation uses CSS variables for easy customization:

```css
--mckinsey-blue: #0073cf;
--mckinsey-dark-blue: #005a9c;
--mckinsey-light-blue: #e6f2ff;
```

### Content

Edit `index.html` to modify slide content. Each slide follows this structure:

```html
<div class="slide" id="slide-X">
    <div class="slide-content">
        <h2 class="slide-title">Your Title</h2>
        <!-- Your content here -->
    </div>
    <div class="slide-footer">
        <div class="slide-number">X</div>
    </div>
</div>
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

MIT License - Feel free to use and modify for your presentations.