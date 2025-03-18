# BRUHIFF Web Version
**B**lazingly **r**apid **u**ncompressed **h**arebrained Image File Format.

This is a web-based implementation of the BRUH image format converter.

## Features
- Convert standard image files (PNG, JPG, etc.) into `.bruh` format.
- Save and download the converted `.bruh` file.
- Load and display `.bruh` files in a canvas.

## How to Use

### Convert an Image to BRUH Format
1. Open the webpage.
2. Click on the **Choose File** button to select an image file.
3. Click **Convert to Bruh** to generate a `.bruh` file.
4. A **Download .bruh** link will appear. Click to save the file.

### Display a BRUH File
1. Open the webpage.
2. Click on the **Choose File** button under **Display a .bruh File**.
3. Click **Display** to render the image on the canvas.

## Technical Details
- Uses an HTML5 `<canvas>` to read and manipulate image data.
- Converts RGB pixel data to a hex-based encoding.
- Encodes image dimensions at the beginning of the `.bruh` file.
- Decodes `.bruh` files and renders them back onto the `<canvas>`.

## Limitations
- No transparency support.
- Large images may result in very large `.bruh` files.
- Encoding and decoding operations may be slow for large images.

## Future Improvements
- Optimize file format for smaller file sizes.
- Improve decoding speed.
- Support transparency.
- Add drag-and-drop functionality for convenience.

