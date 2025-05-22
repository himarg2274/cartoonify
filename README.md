# Cartoonify - Convert Photos to Cartoons using OpenCV

Cartoonify is a Python-based project that converts real-world images into cartoon-style illustrations using computer vision techniques. It uses a combination of edge detection, color quantization, and image smoothing to generate stylized images that resemble cartoons.

## Features

- Converts real images into cartoon-style visuals
- Edge detection using adaptive thresholding and Canny filters
- Color simplification with K-Means clustering
- Noise reduction using bilateral filtering
- Supports common image formats like JPG and PNG

## Demo

Input Image:  
![Untitled](https://github.com/user-attachments/assets/8b903079-649c-4f08-bd98-06cf8ae2abdc)


Cartoonified Output:  
![Untitled](https://github.com/user-attachments/assets/ed1870f3-357e-4a50-92b9-8a5371a48579)


## Technologies Used

- Python 3.x
- OpenCV
- NumPy
- Matplotlib (for visualization)

## Project Structure

Cartoonify/
│
├── example/ # Example input and output images
│ ├── original.jpg
│ └── cartoonified.jpg
│
├── cartoonify.py # Main script
├── README.md # Documentation
└── requirements.txt # Python dependencies

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Cartoonify.git
cd Cartoonify
```
```bash
pip install -r requirements.txt
```
```bash
filename = "your_image.jpg"
```
```bash

python cartoonify.py
```
