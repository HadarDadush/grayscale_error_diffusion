# Grayscale Error Diffusion (6-Level Quantization)

This project performs error diffusion dithering on grayscale images using 6 fixed gray levels.

## Purpose

The main goal is to reduce the grayscale image to 6 predefined intensity levels  
([0, 51, 102, 153, 204, 255]) using Floyd–Steinberg error diffusion, while preserving visual quality.

## Structure

- **grayscale_error_diffusion.py**: Main Python script that performs:
  - Loading a grayscale image
  - Quantization to 6 gray levels
  - Error diffusion across pixels
  - Displaying original vs. quantized images
  - Saving the quantized image as a new PNG file

## Usage

1. Run the script:
2. Enter the name of a grayscale image file (e.g. `gradient.png`).
3. The program will:
- Show the original and quantized images side by side.  
- Save the quantized result as `quantized_output.png`.

## Requirements

Make sure you have the following Python packages installed:

- `numpy`
- `matplotlib`
- `imageio`
- `opencv-python`

You can install them using:
pip install numpy matplotlib imageio opencv-python
