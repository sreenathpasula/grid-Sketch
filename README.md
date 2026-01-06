# grid-Sketch
<parameter name="content"># Etch-a-Sketch 🎨

A classic Etch-a-Sketch drawing application built with vanilla JavaScript, HTML, and CSS.

![Etch-a-Sketch Preview](https://via.placeholder.com/800x400?text=Etch-a-Sketch+Preview)

## Features

- **Draw freely** - Hover over grid cells to draw
- **Change grid size** - Customize the grid from 8x8 to 100x100
- **Color picker** - Choose any color for your drawings
- **Random colors** - Generate random colors while drawing
- **Eraser tool** - Erase parts of your drawing
- **Reset sketch** - Clear the entire canvas

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build process required

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/etch-a-sketch.git
```

2. Navigate to the project directory:
```bash
cd etch-a-sketch
```

3. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

## Project Structure

```
etch-a-sketch/
├── index.html      # Main HTML file
├── style.css       # Styling and layout
├── js/
│   └── script.js   # Application logic
└── README.md       # This file
```

## How to Use

1. **Drawing**: Simply hover your mouse over the grid cells to draw
2. **Change Grid Size**: Click the button and enter a number between 8-100
3. **Select Color**: Use the color picker to choose your drawing color
4. **Random Color**: Click to enable random colors on hover
5. **Eraser**: Click to switch to eraser mode (draws with background color)
6. **Reset Sketch**: Click to clear the entire grid

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)** - Vanilla JavaScript for interactivity

## Customization

### Changing Default Grid Size

Edit `js/script.js` and modify the last line:
```javascript
// Change 16 to your preferred default size
makeGrid(16, 16);
stylingItems();
```

### Adding New Colors

You can add more color presets by creating additional buttons in the JavaScript file.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the classic Etch-a-Sketch toy
- Built as a learning project for web development
- Uses [MiniReset.css](https://github.com/jgthms/minireset.css) for consistent styling
</parameter>
