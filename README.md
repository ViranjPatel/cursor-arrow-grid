# Cursor Following Arrow Grid

An interactive web application featuring a grid of arrows that dynamically follow your cursor movement. Each arrow rotates and scales based on its distance from the cursor, creating a mesmerizing visual effect.

## ✨ Features

- **Real-time Cursor Tracking**: Arrows continuously orient themselves toward your cursor
- **Dynamic Scaling**: Arrows closer to the cursor appear larger
- **Smooth Animations**: Fluid transitions using CSS transforms and requestAnimationFrame
- **Responsive Design**: Adapts to different screen sizes (desktop, tablet, mobile)
- **Interactive Effects**: Click ripples and hover animations
- **Custom Cursor**: Glowing cursor with pulse animation
- **Performance Optimized**: 60fps smooth animations

## 🚀 Live Demo

[View Live Demo](https://viranjpatel.github.io/cursor-arrow-grid)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/ViranjPatel/cursor-arrow-grid.git
cd cursor-arrow-grid
```

2. Open `index.html` in your browser or serve it locally:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

3. Navigate to `http://localhost:8000` in your browser

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🎨 Customization

### Grid Size
Modify the CSS grid in the `.container` class:
```css
.container {
    grid-template-columns: repeat(20, 1fr); /* 20 columns */
    grid-template-rows: repeat(15, 1fr);    /* 15 rows */
}
```

### Arrow Appearance
Customize arrow style in the `.arrow::before` selector:
```css
.arrow::before {
    border-left: 8px solid transparent;
    border-right: 8px solid transparent;
    border-bottom: 20px solid rgba(255, 255, 255, 0.8);
}
```

### Animation Speed
Adjust transition duration:
```css
.arrow {
    transition: transform 0.1s ease-out; /* Change 0.1s to desired speed */
}
```

## 🔧 Technical Details

- **Pure JavaScript**: No external dependencies
- **CSS Grid**: Responsive grid layout
- **Transform**: Hardware-accelerated animations
- **RequestAnimationFrame**: Smooth 60fps updates
- **Event Listeners**: Efficient mouse tracking

## 📁 Project Structure

```
cursor-arrow-grid/
├── index.html          # Main HTML file
├── README.md           # This file
├── package.json        # Project configuration
└── LICENSE            # License file
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by interactive cursor-following designs
- Built with vanilla JavaScript for maximum compatibility
- CSS Grid for responsive layout

## 🐛 Known Issues

- Performance may vary on older devices
- Cursor visibility might be affected by browser settings

## 🔮 Future Enhancements

- [ ] Color themes
- [ ] Particle effects
- [ ] Sound integration
- [ ] Touch device support improvements
- [ ] Arrow trail effects

---

**Enjoy the mesmerizing arrow grid!** 🎯