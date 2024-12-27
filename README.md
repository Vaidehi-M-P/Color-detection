# Color Detection with OpenCV

This project detects the color of a pixel in an image when you double-click on it. It uses OpenCV for image processing and pandas to read a CSV file containing a list of colors and their corresponding RGB values. The goal is to display the name and RGB values of the color at the clicked point in the image.

## Features
- Load an image and display it in a window.
- Detect the color of a pixel when you double-click on it.
- Display the color name and its RGB values.
- Adjust text visibility based on the brightness of the color.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- pandas

You can install the required libraries using `pip`:

```bash
pip install opencv-python pandas
```

## How to Use

1. Place the image you want to analyze in the specified directory (e.g., colorpic.jpg).
2. Run the script. A window will open with the image displayed.
3. Double-click on any pixel in the image. The name and RGB values of that color will be displayed at the top-left corner of the window.
4. The text color will adjust depending on the brightness of the detected color to ensure visibility. For light colors, the text will be black.
5. Press Esc to exit the program.
