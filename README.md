# 🌊 A Refined Deep Learning Method Using YOLO for Marine Debris Identification

## 📘 Overview

This project aims to automatically **detect and classify marine debris** such as plastic bottles, fishing nets, and face masks using **deep learning**.
It uses an improved **YOLOv11 (You Only Look Once)** model integrated with **attention mechanisms** like **Coordinate Attention** and the **Bottleneck Transformer** to increase detection accuracy, especially for small or transparent debris.

The system provides a **Flask-based web interface** where users can upload images or videos, and the model will process and display the detected debris with bounding boxes and confidence scores.

---

## 🎯 Objectives

* Detect and classify marine debris automatically from ocean or drone images.
* Improve accuracy and precision using enhanced YOLOv11 with attention mechanisms.
* Provide a real-time, user-friendly web interface for image and video uploads.
* Support environmental monitoring and marine pollution analysis.

---

## 🧠 Features

* Real-time debris detection from images and videos.
* Enhanced small-object detection using Coordinate Attention and Bottleneck Transformer.
* Flask-based web app for uploading, processing, and displaying results.
* Accurate detection even under reflections, shadows, and complex water backgrounds.

---

## 🧩 System Workflow

1. **Input:** User uploads ocean images/videos through the web app.
2. **Preprocessing:** Image enhancement using Adaptive Histogram Equalization.
3. **Segmentation:** Separation of debris regions using Fuzzy C-Means clustering.
4. **Detection:** YOLOv11 model detects and classifies debris with confidence scores.
5. **Output:** Processed results displayed on the web app with bounding boxes.

---

## ⚙️ Technologies Used

| Category                | Tools / Frameworks         |
| ----------------------- | -------------------------- |
| Programming Language    | Python                     |
| Deep Learning Framework | PyTorch (YOLOv11)          |
| Image Processing        | OpenCV                     |
| Web Framework           | Flask                      |
| Visualization           | Matplotlib, FFmpeg         |
| Environment             | Jupyter Notebook, Anaconda |

---

## 🚀 How to Run the Project

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/marine-debris-detection.git
   cd marine-debris-detection
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Web Application**

   ```bash
   python app.py
   ```

4. **Access the Web App**
   Open your browser and go to:
   `http://127.0.0.1:5000/`

5. **Upload an Image or Video**

   * Choose an ocean image/video file.
   * Click on **Upload & Detect**.
   * View detection results with bounding boxes and labels.

---

## 🧪 Results

* Achieved **92% mean Average Precision (mAP)** on test data.
* Improved performance for small and partially submerged debris.
* Efficient real-time detection for both images and videos.

---

## 🌱 Future Enhancements

* Integrate multispectral or thermal imaging for underwater detection.
* Deploy model on edge devices like drones for live monitoring.
* Add GPS tagging for debris location tracking.
* Expand dataset for more debris categories.

---

## 👨‍💻 Contributors

* **Sri Chaitanya Gurrala**

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
