**PROJECT: Brain Tumor Segmentation with YOLO 11 and SAM2**

This project involves using advanced computer vision techniques to perform brain tumor segmentation using YOLO 11 and SAM2 models. In this project, object detection is done through YOLO 11 and its detected bounded box with coordinate values is given as input to the SAM2 Model which puts a mask on it. That’s how Segment Anything Model performs instance segmentation on the custom objects.
 
**IMPORTANT TERMS TO KNOW**

**YOLO 11 (You Only Look Once version11):**  

A state-of-the-art real-time object detection model that identifies multiple objects in an image with high speed and accuracy

**SAM 2 (Segment Anything Model 2):**

A segmentation model designed for precise object separation in an image.

**Segmentation:**

The process of partitioning an image into meaningful regions to detect and analyze objects.

**Steps To Follow:**

1-     Model trained over custom datasets (image+ annotation)

2-     Now custom dataset goes to YOLO 11 for Object detection

3-     Output of Object detection will be input of SAM2 Model (Instance Segmentation)



**YOLO DETECTED IMAGE**

<img width="385" alt="image" src="https://github.com/user-attachments/assets/89adb60f-75d7-4ff2-98ff-cb0e0b5d5651" />

**BOUNDED BOX COORDINATES**

<img width="477" alt="image" src="https://github.com/user-attachments/assets/cccf4722-b5cd-425c-a55f-548cd7485714" />

**OUTPUT: SAM2 DETECTED BRAIN TUMOR**
 
<img width="196" alt="image" src="https://github.com/user-attachments/assets/d33ee7ec-1ccc-40d9-9a27-a7f2b4cfd105" />
