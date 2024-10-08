# Assignment 2 Computer Vision

## Description

This code repo holds the code and files for assignment 2 of computer vision

## How to run code

### Prerequisites

The following terminal commands work for Mac OS. Please try to find the same working commands for your OS of choice

1. Create python virtual env. If using native python: `python3 -m venv env`
2. Activate virtual env: `source env/bin/activate`
3. Install libraries: `python -m pip install -r requirements.txt`
4. Pre-process dataset running: `python pre_process_dataset.py`

### Image operations

#### Morphological Image Processing

1. Dilation: `python morphological_image_processing/dilation.py`
![alt text](morphological_image_processing/dilation.png)
2. Erosion: `python morphological_image_processing/erosion.py`
![alt text](morphological_image_processing/erosion.png)
3. Opening: `python morphological_image_processing/opening.py`
![alt text](morphological_image_processing/opening.png)
4. Closing: `python morphological_image_processing/closing.py`
![alt text](morphological_image_processing/closing.png)
5. Difference: `python morphological_image_processing/difference.py`
![alt text](morphological_image_processing/difference.png)
