# Clutch-Rivet-Detection

Clutch plates are critical components in automotive and industrial machinery, and identifying the proper placement of rivets both head and tail is essential in real-world manufacturing and quality assurance scenarios. 

---
## Project Overview

Incorrect or missing rivets can lead to structural failures, reduced performance, and safety issues. This project focuses on detecting and classifying rivet conditions using a computer vision model trained on clutch plate images, aiming to automate inspection and ensure production reliability

- `Absence_Head`
- `Absence_Tail`
- `Head_Rivet`
- `Tail_Rivet`

## 📂 **Dataset**

- **Source**: Annotated on ROBOFLOW, exported in YOLO format.
- **Frames**: ~46, frame-by-frame annotated, applied  10 albumentations on each image which gave around 500 plus images
- **Classes**: 4 industrial parts.
  
<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/3b6b9ffd-ef7d-438f-b80b-819e946fcc57" width="300"/>
  <img src="https://github.com/user-attachments/assets/ef590675-a1f3-40ad-b7c4-83374b4d6015" width="300"/>
  <img src="https://github.com/user-attachments/assets/5dc7b0cf-a969-420c-8de6-9d9655462afa" width="300"/>
  <img src="https://github.com/user-attachments/assets/b464e190-fab2-4dc5-ae43-4811c2f1c12a" width="300"/>
  
</p>

 <br>


