# Color Segmentation Tools

A collection of OpenCV-based tools for color-based image and video segmentation.

## Features

- `img_segment.py`: Interactive image segmentation using HSV color space
  - Real-time trackbars for adjusting lower/upper HSV thresholds
  - Displays original image, mask, and segmented result
- `palette.py`: RGB color palette generator
  - Interactive trackbars for color mixing
  - Visual feedback of selected color
- `segment.py`: Video segmentation tool
  - Processes video frames with adjustable HSV thresholds
  - Shows original video, mask, and segmented output

## Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/color-segmentation.git
cd color-segmentation
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
## Usage
### Image Segmentation
```bash
python img_segment.py
```
- Adjust trackbars to set HSV thresholds
- Press ESC to exit
- Ensure `image1.webp` exists in project directory or modify filename

### Color Palette
```bash
python palette.py
```
- Use RGB trackbars to mix colors
- Displays resulting color in window

### Video Segmentation
```bash
python segment.py
```
- Adjust trackbars for real-time video processing
- Ensure `video1.mp4` exists or modify video path
- Press ESC to exit

## Contributing
Contributions are welcome! Please see [Contributing.md](https://github.com/GauravKarakoti/Colour-Segmentation/blob/main/Contributing.md) for guidelines.
