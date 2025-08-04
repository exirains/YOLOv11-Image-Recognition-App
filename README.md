<div align="center">
  <h1>🖥️ YOLOv11 Image Recognition App</h1>
  <p>Real time object detection with camera integration and image processing</p>

  <div align="center">
  <img width="800" height="750" alt="AppScreenshot" src="https://github.com/user-attachments/assets/d1acd68b-ac90-44fb-944a-8c7c7665d6e4" />
    
  *a screenshot of the app*
</div>

<div align="left">
  
**_🌟 Features_**
  
**🎥 Camera Mode**  
- Real-time object detection using webcam  
- Clean resource management  
- Smooth start/stop transitions  

**🖼️ Image Processing**  
- Upload JPG/PNG images for analysis  
- Automatic camera release when uploading  
- Loading animations during processing  

**🎨 UI/UX**  
- Modern CustomTkinter interface  
- Dark/light mode support  
- Responsive design  

## 🛠 Tech Stack
| Category        | Technologies Used               |
|-----------------|---------------------------------|
| **AI Model**    | YOLOv11 (Ultralytics)           |
| **Computer Vision** | OpenCV • PIL                |
| **GUI**         | CustomTkinter                   |
| **Core**        | Python 3.10+ • Threading        |

## ⚙️ Setup
```bash
# Clone repository
git clone https://github.com/exirains/YOLOv11-Image-Recognition-App.git

# Install dependencies
pip install ultralytics pyqt5 opencv-python pillow numpy

# Run application
python yolo_app.py
