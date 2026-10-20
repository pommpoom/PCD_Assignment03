# Assignment 03: Image Segmentation and Morphological Processing

**Name:** Erlangga Mandala Putra  
**Student ID:** 25/554848/PA/23244

Manual implementation of Otsu thresholding, erosion, dilation,
opening, and closing for Digital Image Processing Assignment 03.

## Files
- `PCD_Assignment03.ipynb`: Code, outputs, comparisons, and discussion.
- `input_text.png`: Input image.

## How to Run
1. Open `PCD_Assignment03.ipynb` in Google Colab.
2. Run the cells from top to bottom.
3. Upload `input_text.png` when prompted.

## Comparison
The notebook compares segmentation without morphology against
individual morphological operations and opening followed by closing.
Square structuring elements of 9×9 and 15×15 are compared.

## Implementation Notes
The segmentation and morphology algorithms are implemented manually.
NumPy supports basic array operations, Pillow loads the image,
and Matplotlib displays the results.

The input is an AI-generated synthetic image with intentional
noise, holes, and broken strokes.
