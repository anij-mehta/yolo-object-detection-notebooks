# 🧠 YOLO-Based Object Detection Notebooks

## 📌 Table of Contents
- [About the Project](#-about-the-project)
- [Tech Stack](#-tech-stack)
- [Core Components](#-core-components)
- [Database Design](#-database-design)
- [Setup Instructions](#-setup-instructions)
- [How It Works](#-how-it-works)
- [Screenshots](#-screenshots)
- [Future Enhancements](#-future-enhancements)
- [Contact](#-contact)

## 📖 About the Project

This repository contains a collection of YOLO-based Jupyter notebooks for real-time object detection tasks including:
- Counting number of **people** in live video and images using YOLOv5, YOLOv7, and YOLOv8.
- Detecting **potholes** in roads.
- Counting **cars** in static images.

The goal is to build accurate, real-time, and customizable detection systems using different YOLO versions.

## 🛠️ Tech Stack

- Python 3.x
- OpenCV
- PyTorch / Torchvision
- YOLOv5, YOLOv7, YOLOv8
- Ultralytics YOLO models
- Jupyter Notebook

## 🧩 Core Components

| Notebook           | Task                                    |
|--------------------|------------------------------------------|
| `v5person.ipynb`   | People detection using YOLOv5            |
| `v7person.ipynb`   | People detection with live video using YOLOv7 |
| `v8person.ipynb`   | People detection using YOLOv8 (Ultralytics) |
| `pothole.ipynb`    | Pothole detection in roads               |
| `car_counter.ipynb`| Car counting in static images            |

## 🗃️ Database Design

This project uses pre-trained weights and public datasets:

- **People Detection:** COCO dataset (person class only)
- **Pothole Detection:** Pre-trained weights or custom data (can be extended using Roboflow datasets)
- **Car Counting:** ImageNet/COCO pre-trained weights

Custom datasets can be integrated easily with `YOLOv8` training utilities.

## ⚙️ Setup Instructions

1. Clone the repository:
   
   ```bash
   git clone https://github.com/yourusername/yolo-notebooks.git
   cd yolo-notebooks
   ```
   
3. Install dependencies:
   
   ```bash
   pip install -r requirements.txt
   ```

4. Open notebooks using Jupyter:

    ```bash
    jupyter notebook
    ```

Ensure your system has CUDA/GPU support for real-time detection.

## 🧪 How It Works

Each notebook:

    Loads the appropriate YOLO version

    Reads input from image/video/live webcam

    Performs detection and draws bounding boxes

    Displays object count (for people or cars)

The v7person.ipynb includes live counting display on the video frame.

## 🖼️ Screenshots
People Detection (YOLOv7)

Pothole Detection

Car Counting

## 🚀 Future Enhancements

    Deploy web-based UI using Streamlit or Flask

    Add support for YOLO-NAS and RT-DETR

    Integrate custom training pipelines

    Export detections to CSV or database

## 📬 Contact

Anij Mehta<br>
🔗 [GitHub](https://github.com/anij-mehta)<br>
🔗 [LinkedIn](https://www.linkedin.com/in/anij-mehta)
