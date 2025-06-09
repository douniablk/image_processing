# Image Processing TPs (Travaux Pratiques)

## Description

This repository contains a series of practical assignments (TP01–TP07) for image processing, covering fundamental techniques such as contrast enhancement, histogram equalization, noise reduction, edge detection, and segmentation. Each TP is implemented in a Jupyter Notebook and uses Python libraries such as NumPy, Matplotlib, Pillow, and OpenCV.

## Project Structure

```
tp01.ipynb   # Contrast stretching
tp02.ipynb   # Global histogram equalization
tp03.ipynb   # Local histogram equalization (CLAHE) & entropy analysis
tp04.ipynb   # Noise reduction: exponential low-pass & Wiener filter
tp05.ipynb   # Salt & pepper noise reduction with manual median filter
tp06.ipynb   # Kirsch edge detection & Otsu thresholding
tp07.ipynb   # Closed contour detection & segmentation (Kirsch + Otsu + morphology)
test.ipynb   # Prewitt edge detection (test notebook)
pics/
    bananapic.jpg
    blurred1.jpg
    blurred2.jpg
    cameraman.jpg
    myimage.jpg
```

## Requirements

- Python 3.x
- numpy
- matplotlib
- pillow
- opencv-python
- scipy (for some TPs)

Install dependencies with:
```sh
pip install numpy matplotlib pillow opencv-python scipy
```

## Usage

1. Place your images in the `pics/` directory.
2. Open any notebook (e.g., `tp01.ipynb`) in Jupyter Notebook or VS Code.
3. Run the cells to execute the image processing pipeline for each TP.
4. Modify the image path in the code if you want to use a different image.

## Overview of TPs

- **TP01:** Contrast stretching to enhance image visibility.
- **TP02:** Global histogram equalization for contrast improvement.
- **TP03:** Local histogram equalization (CLAHE) and entropy analysis.
- **TP04:** Noise reduction using exponential low-pass filter and Wiener filter in the frequency domain.
- **TP05:** Manual median filtering for salt & pepper noise reduction.
- **TP06:** Edge detection using the Kirsch operator and automatic thresholding with Otsu's method.
- **TP07:** Detection and segmentation of closed contours using Kirsch, Otsu, and morphological analysis.
- **test.ipynb:** Example of Prewitt edge detection.

## Author

belkacem dounia, IAA G2

---

*Each notebook contains explanations, code, and visualizations for the corresponding image processing technique.*