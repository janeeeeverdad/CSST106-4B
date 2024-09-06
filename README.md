# Table of Contents

Welcome! Here are some compilation of activities and project that I created.

## 1.Introduction to Computer Vision and Image Processing
https://github.com/user-attachments/assets/7a39bb6c-9694-4c8f-8540-1e1532d4ecc7

**Computer Vision**
> A field of computer science that focuses on enabling computers to identify, interpret, and understand the visual world. It seeks to replicate human vision by converting raw pixel data into a high-level understanding of objects.

**Roles of Image Processing in AI**

- **Preprocessing:** To enhance the quality of the input, raw images are prepared for analysis. Common tasks include noise reduction, contrast adjustment, resizing, and color correction. 

- **Feature Extraction:** To help identify and isolate important features within an image, such as edges, corners, textures, and patterns. These are essential to classify objects, detect anomalies, or recognize faces.

- **Segmentation:** is the process of dividing an image into meaningful regions, such as identifying individual objects or boundaries within a scene. 

- **Edge Detection:** Identifying the edges within an image is for understanding the structure and geometry of objects.

**Three Core Techniques**

- **Image Filtering**- Enhances certain features in an image. Filters can smooth out noise, sharpen edges, or detect specific features like edges or corners.
**Example:** In trash segregation systems, filters are used to enhance the visibility of objects (like bottles or cans) by reducing image noise.

- **Edge Detection**- identifies the boundaries between different regions in an image, which is important for object detection and recognition tasks.
**Example:** In trash segregation, edge detection helps the system identify the outlines of recyclable materials like plastics or metals.

- **Image Segmentation**- divides an image into meaningful regions, for understanding the image's content and isolating areas of interest.
**Example:** In trash segregation, it is for separating different types of waste within an image, such as classifying plastics from paper or glass.

**Case Study (Real-World Application)**
>**Automatic Trash Segregation**- is a real-world application of computer vision that automates the sorting of waste materials into categories like plastic, glass, paper, and organic waste. This technology is being implemented in smart recycling systems to increase waste management, reduce human error, and minimize environmental impact.

**Use of Image Processing in Trash Segregation**
- **Image Enhancement**: Captured images of waste proceeds to do image processing techniques, such as filtering, which improve the quality of these images by reducing noise and enhancing contrast, making it easier to identify different waste items.
- **Object Detection and Classification**: Edge detection helps in recognizing boundaries of objects, while Segmentation separates different types of waste into distinct regions of interest. To classify items into categories like plastics, paper, metals, or glass.
- **Feature Extraction and Classification**: Extract features such as shape, color, and texture. These features are used to classify the waste accurately.  The system might use color information to distinguish between glass and plastic or shape analysis to differentiate between bottles and cans.

**Challenges Addressed:**
- **Accuracy in Classification:** Image processing improves the accuracy of waste classification by providing clear, detailed images for AI analysis. Techniques like filtering and edge detection help reduce errors caused by image noise and overlapping objects.
- **Handling Diverse Waste Types:** Waste comes in various forms and conditions. Image segmentation and feature extraction enable the AI to handle diverse types of waste by focusing on specific attributes relevant to classification.
- **Real-time Processing:** Image processing techniques ensure that the AI system can analyze and classify waste quickly, which is essential for real-time applications in waste management facilities.

**Implementation:**
![Screenshot 2024-09-06 233641](https://github.com/user-attachments/assets/f4004f0b-d0e4-427a-b027-cf962b131753)

> **Conclusion:** In conclusion, image processing plays a crucial role in AI systems that rely on visual data, as it transforms raw images into structured ones that AI can interpret accurately. Techniques like filtering, edge detection, and segmentation refines the visual inputs, that leads to better feature extraction and classification. Preprocessing steps ensures cleaner data and minimizing errors in decision-making. These methods are useful for real-time applications, enabling AI to process information quickly and accurately.

> **Reflection:** The activity of understanding and implementing image processing provided insights into the practical application of techniques like filtering, edge detection, and segmentation. It demonstrated how image processing integrates with AI systems, to address real-world challenges such as waste sorting and classification. 





