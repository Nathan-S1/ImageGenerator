# ImageGenerator
Python-based Image Generator that utilizes libraries such as PIL and Matplotlib to create and manipulate images based on user inputs.

## Author
Nathan Shorez

---

## Project Overview
This project implements an image generator in Python that utilizes libraries such as PIL and Matplotlib to create and manipulate images based on user inputs. The objective is to generate custom images with filters, text overlays, and graphical elements.

---

## Key Components
- **Image Creation:** Generate images from scratch using drawing methods.
- **Image Manipulation:** Apply custom filters and transformations to existing images.
- **Text Overlays:** Add text to images with adjustable fonts and positioning.

---

## Dependencies
- Python 3.x
- PIL (Pillow)
- matplotlib
- argparse

To install dependencies:
```bash
pip install pillow matplotlib
```

---

## Execution
1. **Navigate to the src directory:**
   ```bash
   cd src/
   ```
2. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook image_generator.ipynb
   ```

---

## Example Usage
- Create an image with text overlay:
  ```bash
  python image_generator.py --text "Hello, World!" --output "output.png"
  ```

---
