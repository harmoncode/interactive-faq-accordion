# Interactive FAQ Accordion

A smooth accordion component for FAQ sections with elegant animations. Perfect for organizing frequently asked questions in a clean, interactive format.

## ✨ Features

- **Smooth Animations**: Fluid expand/collapse animations
- **Single/Multiple Open**: Choose between single or multiple open items
- **Keyboard Navigation**: Full keyboard accessibility
- **Responsive Design**: Works perfectly on all devices
- **Customizable**: Easy to customize colors, animations, and styling
- **Accessible**: Built with ARIA attributes and semantic HTML
- **Lightweight**: Pure CSS and JavaScript, no dependencies

## 🚀 Live Demo

[View on CodePen](https://codepen.io/harmoncode/pen/emNYajr)

## 📁 Files

- `index.html` - Main HTML structure
- `style.css` - All styling and animations
- `script.js` - JavaScript functionality

## 🛠️ Usage

### Basic Implementation

```html
<div class="accordion">
    <div class="accordion-item">
        <button class="accordion-header">
            <span>What is this?</span>
            <i class="fas fa-chevron-down"></i>
        </button>
        <div class="accordion-content">
            <p>This is the answer to your question.</p>
        </div>
    </div>
</div>
```

### JavaScript Initialization

```javascript
// Initialize accordion
const accordion = new Accordion('.accordion', {
    singleOpen: true,
    animationDuration: 300
});
```

## 🎨 Customization Options

- **Colors**: Customize background, text, and border colors
- **Animations**: Adjust animation duration and easing
- **Icons**: Change expand/collapse icons
- **Spacing**: Modify padding and margins
- **Typography**: Customize font sizes and weights

## ⚙️ Configuration

```javascript
const options = {
    singleOpen: true,        // Only one item open at a time
    animationDuration: 300,  // Animation duration in ms
    easing: 'ease-in-out',   // CSS easing function
    autoClose: true          // Auto close other items
};
```

## 📱 Browser Support

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- IE11+ ✅

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Created by

**HarmonCode** - [harmoncode.com](https://harmoncode.com)

---

⭐ If you find this useful, please give it a star! 