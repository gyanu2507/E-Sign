# Signature Canvas

This project is a web-based signature canvas that allows users to create, customize, and save their signatures. The canvas provides options to change text color, background color, and font size. Users can clear the canvas, save their work, and retrieve saved signatures.

## Features

- **Color Picker for Text**: Choose a custom color for your signature text.
- **Background Color Picker**: Customize the canvas background color.
- **Font Size Selector**: Select the font size for your signature.
- **Clear Canvas**: Clear the canvas to start over.
- **Save and Download**: Save your signature and download it as a PNG file.
- **Retrieve Saved Signature**: Retrieve the last saved signature from local storage.

## Getting Started

### Prerequisites

To run this project, you need a modern web browser that supports HTML5 and JavaScript.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/gyanu2507/E-Sign
    ```

2. Navigate to the project directory:
    ```sh
    cd signature-canvas
    ```

3. Open the `index.html` file in your preferred web browser.

### Usage

1. **Text Color Picker**: Select a color to use for the signature text by clicking on the color input under "Text color picker."
2. **Background Color Picker**: Select a background color for the canvas by clicking on the color input under "Background."
3. **Font Size Selector**: Choose the desired font size for your signature from the dropdown menu under "Font size."
4. **Draw Signature**: Click and drag on the canvas to draw your signature.
5. **Clear Button**: Click "Clear" to clear the canvas.
6. **Save & Download**: Click "Save & download" to save the current signature to local storage and download it as a PNG file.
7. **Retrieve Saved Signature**: Click "Retrieve saved signature" to load the last saved signature from local storage.

### File Structure

```
signature-canvas/
├── index.html
├── favicon.png
└── README.md
```

### Customization

To customize the project, you can modify the `index.html` file and update the styles within the `<style>` tag. For example, you can change the default canvas size, default colors, and layout.

### Dependencies

- [Bootstrap 4.5.0](https://getbootstrap.com/docs/4.5/getting-started/introduction/): Used for styling form controls.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- The project uses Bootstrap for styling the form elements.
