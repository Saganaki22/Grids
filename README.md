# Grids

A creative photo effect generator that transforms your images with grid-based visual effects in the browser.

![grids](https://github.com/user-attachments/assets/fd2b0f4b-25b3-4c12-82e5-eaa871b06f17)


## ✨ Features

- **Browser-based**: No installation required - works directly in your web browser
- **Real-time previews**: See changes instantly as you adjust settings
- **Multiple effect types**:
  - 🔮 **Kaleidoscope**: Creates mesmerizing fractal-like patterns
  - 🪞 **Mirror**: Reflects sections of your image in different directions
  - 🔄 **Invert**: Reverses the colors in selected grid cells
  - 💎 **Diamonds**: Applies a diamond-shaped gradient pattern
  - 🧩 **Pixelate**: Creates blocky, retro-style pixel art effects
  - 🌀 **Vortex/Twirl**: Swirls the image around the center of each grid cell
  - 🔍 **Edge Detection**: Highlights the contours and edges in your image
  - 🏺 **Sepia/Vintage**: Applies a warm, nostalgic tone for an aged photo look
  - 🎲 **Random Mix**: Combines different effects for unique results
- **Customizable settings**:
  - Grid size adjustment
  - Effect intensity control
  - Contrast enhancement
  - Optional grid lines
- **Drag-and-drop** file uploads
- **High-quality exports** as PNG files

## 🚀 Getting Started

### Online Version

Visit [DEMO](https://drbaph.is-a.dev/Grids/) to use Grids online without installation.

### Local Installation

1. Clone the repository:
```bash
git clone https://github.com/Saganaki22/Grids.git
```

2. Navigate to the project directory:
```bash
cd Grids
```

3. Open the `index.html` file in your web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

## 💻 Usage

1. **Upload an image** by dragging and dropping it onto the upload area or clicking to browse
2. **Adjust the grid size** using the slider to create smaller or larger effect cells
3. **Select an effect type** from the dropdown menu
4. **Fine-tune your effect** with the intensity and contrast sliders
5. Toggle grid lines on/off as desired
6. **Download** your processed image

## ⚙️ Technical Details

Grids is built with pure HTML, CSS, and JavaScript with no external dependencies. The application uses:

- HTML5 Canvas API for image manipulation
- CSS Grid for responsive layout
- Modern JavaScript (ES6+) for real-time image processing
- Custom-built image processing algorithms

All processing happens locally in your browser - your images are never uploaded to a server.

## 🖼️ Examples

Here are some examples of effects you can create with Grids:

- **Kaleidoscope Effect**: Creates mirror-image patterns radiating from the center
- **Vortex Effect**: Creates a swirling distortion centered in each grid cell
- **Edge Detection**: Transforms your image into a line drawing highlighting edges
- **Random Mix**: Creates a collage-like effect with varied treatments in each grid cell

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Add your changes
4. Commit your changes: `git commit -m 'Add some amazing feature'`
5. Push to the branch: `git push origin feature/amazing-feature`
6. Open a Pull Request

### Development Ideas

- Add more effect types
- Implement undo/redo functionality
- Add animation capabilities
- Create effect presets
- Add batch processing for multiple images

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by creative image processing techniques and pixel art
