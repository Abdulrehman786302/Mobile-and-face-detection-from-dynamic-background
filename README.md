# Mobile and Face Detection from Dynamic Background

This project implements YOLOv5 for detecting cell phones and faces in images captured from dynamic backgrounds. The dataset consists of custom annotated images with segmentation and bounding box labels in Pascal VOC format.

---

## Project Overview

We aimed to develop a robust detection system for cell phones and faces by training YOLOv5 on our own dataset. The dataset includes diverse images captured under various conditions, with manual annotations for precise detection.

---

## Dataset

- **Seen1 Folder:** Contains the original images.
- **Annotations Folder:** Contains Pascal VOC XML files corresponding to each image, which include bounding box annotations for cell phones and faces.

---

## Methodology

1. **Image Annotation:** Images were manually annotated using Pascal VOC XML format.
2. **Training:** YOLOv5 was trained using these annotations to detect cell phones and faces.
3. **Testing:** The trained model was tested on a separate set of images to evaluate detection performance.

---

## How to Use

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
```
