# DCT-Lapped LPIPS Compression Ratio

This project explores a novel approach to audio compression by combining Discrete Cosine Transform (DCT) and Lapped Transform (LT) techniques with the Learned Perceptual Image Patch Similarity (LPIPS) metric. The aim is to optimize compression ratios while preserving perceptual audio quality.

## Overview

The project investigates how DCT and LT can be employed to compress audio signals efficiently and evaluates the quality of the compressed audio using the LPIPS metric. This approach helps in understanding the trade-offs between compression efficiency and perceived audio quality.

## Features

- **Audio Compression**: Utilizes DCT and LOT for effective audio compression.
- **Perceptual Quality Evaluation**: Measures perceptual audio quality using LPIPS.
- **Comparative Analysis**: Compares different compression techniques to find the optimal balance between compression and quality.

## Getting Started

To begin using this project, clone the repository and install the necessary dependencies. Run the main script to process audio files and evaluate compression performance. The results will be stored in the designated output directory.

## Directory Structure

- `data/`: Contains input audio files.
- `results/`: Stores results and output files.
- `src/`: Contains source code for compression algorithms and evaluation metrics.
- `main.py`: Script for running the compression and evaluation processes.

- `color/`: Contains source files for color images.
- `gray/`: Contains source files for grayscale images.
- `color-dct/`: Stores color images processed with DCT.
- `gray-dct/`: Stores grayscale images processed with DCT.
- `color-lapped/`: Contains color images processed with Lapped Orthogonal Transform (LOT).
- `gray-lapped/`: Contains grayscale images processed with Lapped Orthogonal Transform (LOT).

## Configuration

Before running the code, please modify the paths in the `path.py` file according to your source directories:

```python
PATH_COLOR = '/home/jupyter-64365/VC_Seminar_Project/color'
PATH_GRAY = '/home/jupyter-64365/VC_Seminar_Project/gray'
PATH_COLOR_DCT = '/home/jupyter-64365/VC_Seminar_Project/color-dct'
PATH_GRAY_DCT = '/home/jupyter-64365/VC_Seminar_Project/gray-dct'
PATH_COLOR_LAP = '/home/jupyter-64365/VC_Seminar_Project/color-lapped'
PATH_GRAY_LAP = '/home/jupyter-64365/VC_Seminar_Project/gray-lapped'
```

Ensure these paths match your local or remote directory structure.

## Getting Started

To get started with this project, clone the repository and install the necessary dependencies. Update the `path.py` file with the correct paths for your environment. Execute the main script to process the images and evaluate compression performance. Results will be saved in the designated output directories.

