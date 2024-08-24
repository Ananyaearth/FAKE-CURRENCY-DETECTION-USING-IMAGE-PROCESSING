# FAKE-CURRENCY-DETECTION-USING-IMAGE-PROCESSING
Detect counterfeit currency using image processing. Analyzes features like transparent strips &amp; patterns, comparing real vs. fake notes to determine authenticity.:

## Overview

This project aims to detect counterfeit currency notes using image processing techniques. It loads images of real and fake currency notes, applies various image processing operations such as thresholding and morphological operations, and then analyzes features to determine the authenticity of the currency.

## Description

The project utilizes computer vision libraries like OpenCV and NumPy to process the images of currency notes. It extracts specific regions of interest, such as the transparent strip and certain patterns, and compares them between real and fake notes. The correlation coefficient is calculated to assess the similarity between corresponding regions.

## Files

- **fakecurrency.ipynb**: Jupyter Notebook containing the Python code for the fake currency detection project.

- **real.jpg**: Image file containing a sample of a real currency note.

- **fake.jpg**: Image file containing a sample of a fake currency note.

## Usage

1. **Run the Notebook**: Open and run the `fakecurrency.ipynb` notebook using Jupyter or any compatible environment.

2. **Load Images**: Ensure that the `real.jpg` and `fake.jpg` images are placed in the same directory as the notebook or provide the correct file paths.

3. **Execute Code Cells**: Run each code cell in the notebook sequentially to perform image processing and analysis.

4. **Interpret Results**: The notebook will output the analysis results, indicating whether the currency is determined to be legitimate or fake based on the correlation coefficient and other factors.

## Dependencies

- Python 3.x
- OpenCV
- NumPy
- Matplotlib

## Contribution

Contributions to the project are welcome! Feel free to fork the repository, make improvements, and submit pull requests.

---
