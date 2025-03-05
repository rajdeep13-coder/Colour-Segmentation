# 🎨 Color Segmentation Tools

A collection of **OpenCV-based tools** for color-based image and video segmentation.

---

## 🚀 Features

### 🖼️ Image Segmentation (`img_segment.py`)
🔹 **Interactive image segmentation** using **HSV color space**  
🔹 **Real-time trackbars** for adjusting lower/upper HSV thresholds  
🔹 Displays **original image, mask, and segmented result**  

### 🎨 Color Palette (`palette.py`)
🔹 **RGB color palette generator**  
🔹 **Interactive trackbars** for color mixing  
🔹 **Visual feedback** of the selected color  

### 🎥 Video Segmentation (`segment.py`)
🔹 **Processes video frames** with adjustable HSV thresholds  
🔹 Shows **original video, mask, and segmented output**  

---

## 📌 Prerequisites
Ensure you have the following installed:
✅ **Python 3.x**  
✅ **OpenCV** → `pip install opencv-python`  
✅ **NumPy** → `pip install numpy`  

---

## 🔧 Installation
Clone the repository and install dependencies:
```bash
# Clone the repository
git clone https://github.com/GauravKarakoti/color-segmentation.git
cd color-segmentation

# Install dependencies
pip install -r requirements.txt
```

---

## 📖 Usage

### 🖼️ Image Segmentation
```bash
python img_segment.py
```
🔹 Adjust **trackbars** to set HSV thresholds  
🔹 Press **ESC** to exit  
🔹 Ensure `image1.webp` exists in the project directory or modify the filename  

### 🎨 Color Palette
```bash
python palette.py
```
🔹 Use **RGB trackbars** to mix colors  
🔹 Displays the resulting **color** in the window  

### 🎥 Video Segmentation
```bash
python segment.py
```
🔹 Adjust **trackbars** for real-time video processing  
🔹 Ensure `video1.mp4` exists or modify the video path  
🔹 Press **ESC** to exit  

---

## 🤝 Contributing
💡 Contributions are welcome! 🎉 Please see [`Contributing.md`](./Contributing.md) for guidelines.


---

## 🔗 Links 
📌 **Repository:** [GitHub](https://github.com/GauravKarakoti/color-segmentation)    
💬 **Feedback & Issues?** Open an issue on GitHub!

🚀 Happy Coding!

