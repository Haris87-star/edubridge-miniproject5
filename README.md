# EduBridge Mini Project 5

## Real-Time Image Classification & Object Detection

A computer vision application developed for **EduBridge Mini Project 5**, integrating Convolutional Neural Networks (CNN MobileNetV2) and YOLOv8 for dual-mode live webcam classification and object detection.

---

## 🚀 Features

- **Dual Mode Vision Pipeline**:
  - **MobileNetV2 (CNN)**: ImageNet-pretrained classification with real-time class name and confidence score overlays.
  - **YOLOv8 Object Detection**: Bounding-box detection powered by Ultralytics YOLOv8.
- **Interactive Controls**: Seamlessly switch inference engines at runtime using keyboard shortcuts.
- **Open Source Compliant**: Includes standard MIT License and educational Privacy Policy.

---

## 🎮 Keyboard Controls

| Key | Mode | Description |
|---|---|---|
| `m` | MobileNetV2 | Switches to ImageNet classification mode |
| `y` | YOLOv8 | Switches to YOLO object detection mode |
| `q` | Quit | Releases camera resources and exits the application |

---

## 📁 Repository Structure

```text
├── .gitignore               # Ignored files, virtual environments, caches
├── LICENSE                  # MIT License
├── PRIVACY_POLICY.md        # Project Privacy Policy
├── README.md                # Project documentation and guide
├── cnn_imagerec.py          # Real-time CNN & YOLO detection script
├── Screenshot ... .png      # Project demo and output screenshots
```

---

## 🛠️ Installation & Setup

### 1. Prerequisites
- Python 3.9+
- Webcam / Camera hardware

### 2. Setup Virtual Environment
```bash
python -m venv venv
# Windows:
.\venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install opencv-python numpy ultralytics tensorflow
```

### 4. Run the Application
```bash
python cnn_imagerec.py
```

---

## 📄 License & Privacy
- **License**: Distributed under the [MIT License](LICENSE).
- **Privacy Policy**: View our [Privacy Policy](PRIVACY_POLICY.md) regarding local processing of camera streams.
