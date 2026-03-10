# Iris Recognition using Optimized Gabor Filters

## Overview
This project implements an iris recognition system with optimized Gabor filter parameters using the CASIA-Iris-Thousand database.

## Pipeline Overview
The system runs in 4 sequential phases:

1. **Segmentation** — Detects pupil and iris boundaries using Hough Circle Transform
2. **Normalization** — Unwraps the iris region into a rectangle using Daugman's Rubber Sheet Model
3. **Feature Extraction** — Applies a Gabor wavelet filter bank and generates a binary IrisCode
4. **Matching** — Compares two IrisCodes using Hamming Distance

   
## Dataset
- CASIA-Iris-Thousand (20,000 images, 1,000 subjects)
- Download from: https://www.kaggle.com/datasets/sondosaabed/casia-iris-thousand

## Requirements
- MATLAB R2020b or later
- Image Processing Toolbox
- Statistics and Machine Learning Toolbox

## How to Run
1. Download dataset and place in `data/` folder
2. Run `main.m`

## Results
- Recognition accuracy: 82%
- EER: 17%

## SEGMENTATION:
<img width="1589" height="450" alt="segmentation_phase" src="https://github.com/user-attachments/assets/abe4042d-29ca-43ec-8647-e636a494c01b" />

## FEATURE EXTRACTION:
<img width="1554" height="985" alt="feature_extraction" src="https://github.com/user-attachments/assets/5bd0cfa9-102e-4cc8-8cd5-a12730723aad" />

## NORMALIZATION:
<img width="518" height="361" alt="normalization2_phase" src="https://github.com/user-attachments/assets/73994911-739e-4058-be90-0e7cf1c3a643" />

## IRIS CODE:
<img width="681" height="468" alt="feature_extraction_iris_code" src="https://github.com/user-attachments/assets/f39df503-bd4a-42f5-836b-420f648a5482" />

## TESTING:
<img width="1273" height="205" alt="real_image_result2" src="https://github.com/user-attachments/assets/6413114e-e927-4dd0-b154-662bdaafdadb" />

## Author
Eralba Spahija - Computer Engineering Student

## Research Paper
The full paper describing the methodology, experiments, and results can be found here: [CEN_535_Iris_Recognition.pdf](https://github.com/user-attachments/files/25867550/CEN_535_Iris_Recognition.pdf)


#

