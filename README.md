# ece5831-2024-final-project
# DEFECT DETECTION IN PCBs
This project focuses on automated fault detection in Printed Circuit Boards (PCBs) using two separate deep learning models: YOLOv8 and Faster R-CNN ResNet. These models independently detect and classify PCB faults, addressing common manufacturing challenges and improving inspection efficiency.  

---

## Project Overview  

### Motivation  
Printed Circuit Boards (PCBs) are critical to modern electronics, and ensuring their reliability is essential for manufacturing quality. Traditional inspection methods are slow and error-prone, making automated deep learning solutions a necessity for efficient fault detection.  

### Objectives  
- Develop and evaluate two independent deep learning models for PCB fault detection.  
- YOLOv8 focuses on real-time fault detection, while Faster R-CNN ResNet emphasizes fault classification accuracy.  
- Provide insights into the strengths and limitations of each model for PCB fault detection tasks.  

---

## Features  
- *Fault Types Detected*: Both models are trained to detect six common PCB faults:  
  1. Mouse Bite  
  2. Missing Hole  
  3. Open Circuit  
  4. Short  
  5. Spur  
  6. Spurious Copper  

- *Independent Models*:  
  - *YOLOv8*: A real-time object detection model ideal for high-speed applications.  
  - *Faster R-CNN ResNet*: A slower but more accurate model for detailed fault classification.  

- *Dataset*: A labeled dataset with images of PCBs and annotations for the six fault categories.  

---

## Resources  
The following resources provide an in-depth understanding of the project:  
- *Pre-recorded Presentation Video*: [https://youtu.be/TYggpieHB2o](#)  
- *Presentation Slides*: [https://docs.google.com/presentation/d/1KlMo_dcoHn0B7RtM7u4PYO1MqJWtjmiX/edit?usp=sharing&ouid=118045303379538944400&rtpof=true&sd=true](#)  
- *Project Report*: ece-5831-2024-final-project-Report.pdf in the repo
- *Dataset*: [https://drive.google.com/drive/folders/1q-z00fWdZ05wqOrA3a3dGQTY_WU32rHf?usp=sharing](#)  
- *Demo Videos*:  
  - *YOLOv8 Demo*: [https://youtu.be/MePYKm5_otI](#)  
  - *Faster R-CNN ResNet Demo*: [https://youtu.be/5oRi_X5i1fA](#)  

---

## Results  
- *YOLOv8*: Demonstrated high-speed fault detection with real-time capabilities.  
- *Faster R-CNN ResNet*: Achieved superior fault classification accuracy, suitable for detailed inspection tasks.  
- *Model Comparison*: Each model offers unique advantages, providing options depending on the specific needs of the inspection process.  

---

## How to Run the Project  

### Prerequisites  
- Python 3.8 or higher  
- Libraries: PyTorch, OpenCV, and other dependencies listed in requirements.txt
