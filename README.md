# 👨‍💻 Tejas Ramekar  

Computer Vision Engineer | Geospatial AI | Object Detection | Backend Development  

---

## 🌐 About Me  

I am a Computer Vision Engineer with experience in **geospatial computer vision, object detection, video processing, and backend systems**.  
I focus on designing streamlined workflows, optimizing pipelines, and deploying end-to-end systems that drive **real-world operational improvements**.  

---

## 💼 Professional Experience  

### **Computer Vision Engineer**  
**Indrones Solutions Pvt. Ltd., Mumbai**  
*Aug 2022 – Present*  

- Implemented practical and creative approaches in **geospatial computer vision, object detection, and video processing**.  
- Designed streamlined workflows and optimized pipelines to achieve impactful operational improvements.  

#### 🚀 Key Projects  

**1. Power Distribution Pole Defect Detection**  
*Python, OpenCV, PyTorch, Depth Anything v2, Rasterio, KML Parsing, Drone Imagery Processing*  
- Designed and implemented an **end-to-end computer vision pipeline** for automated QC and defect detection in power distribution poles using drone imagery.  
- **Data Processing & QC:** Clustered 8 GPS-encoded images per pole using drone intrinsics/extrinsics; mapped clusters to **KML GPS coordinates** to validate coverage & completeness.  
- **Damage Detection:**  
  - Built a YOLO-based detection model (**85% mAP**) for pole components (insulators, cross arms, poles, top cleats).  
  - Designed an **ensemble classifier** (ViT-Base + EfficientNet + ResNet-50) with **92% accuracy** for damage detection.  
- **Vegetation Detection:** Developed a hybrid algorithm using **Depth Anything v2 + HSV masking + geometric filtering** to detect vegetation within a distance threshold.  
- **Pole Tilt Analysis:** Applied **rembg + GrabCut segmentation**, extracted contours, and computed tilt angles using Euclidean geometry.  
- **Reporting:** Generated structured **JSON outputs + visual reports** with KML-mapped pole IDs, defect snapshots, vegetation analysis, and tilt data.  
- **Impact:** Delivered a scalable, modular, and multi-model pipeline ready for deployment. Future plan: **YOLO Pose-based tilt estimation**.  

---

**2. Geospatial Change Detection**  
*Python, OpenCV, PyTorch, Ultralytics, Rasterio*  
- Designed a robust pipeline for **object-based change detection in geospatial datasets**.  
- Implemented a **multi-processing gridding approach** (Rasterio + Shapely) → **10x faster** preprocessing.  
- Converted polygons → pixel coordinates → masks/bboxes for **U-Net & YOLOv8 experiments**.  
- Trained YOLOv8 on **9 classes**, achieving strong change detection results.  
- Built a custom algorithm to classify changes as *appeared, disappeared, unchanged, increased, decreased*.  
- Reprojected results back to **geospatial coordinates** for **map-based visualization**.  

**3. Object Detection on Live Stream**  
*Python, OpenCV, FFmpeg, AWS*  
- Deployed an **NGINX RTMP server** on AWS EC2 for real-time video ingestion.  
- Integrated **YOLOv8 Nano** for object detection on live streams.  
- Streamed processed frames to AWS IVS with **FFmpeg + NVENC hardware acceleration** → **40% faster** streaming.  

**4. Video Processing Application for Drone Flights**  
*Python, OpenCV, Flask, AWS*  
- Built an **end-to-end video processing pipeline** to concatenate drone flights with embedded geo-data.  
- Synced videos with metadata using **regex-based parsing algorithm**.  
- Backend deployed with **Flask + NGINX + EC2**.  
- Integrated **PostgreSQL + SQLAlchemy ORM** for structured data storage.  
- Automated manual workflow → **66% time reduction**, **3x efficiency improvement**.  

---

## 🎓 Education  

**University of Mumbai**  
*Bachelor’s in Computer Engineering (2017 – 2021)*  

---

## 🛠 Technical Skills  

- **Programming:** Python, OOP, Multiprocessing  
- **Frameworks & Libraries:** PyTorch, OpenCV, Flask, NumPy, Pandas, Matplotlib, Ultralytics, Rasterio  
- **Tools:** NGINX, FFmpeg, Exif, PostgreSQL, AWS (EC2, RDS, S3), Git, Postman, Bitbucket  
- **Technologies:** Object Detection, Image Segmentation, Geospatial Analysis, Backend Development  

---

## 📜 Certifications  

- Deep Neural Networks with PyTorch (Coursera)  
- Machine Learning with Python (Coursera)  

---

## 🏆 Awards & Recognition  

- **Challenger Award** – Indrones (2024)  
- **Skybound Innovator Award** – Indrones (2025)  
- **Eminent Speaker Award** – Pipetech (2025)  

---

## 📂 Projects  

### 🔹 CNN Transfer Learning with Deployment *(May 2022)*  
- Dogs-vs-Cats classification using **ResNet-18 transfer learning**.  
- Built with **PyTorch** and deployed on **Heroku** with a **Streamlit interface**.  
- [Training Notebook](https://www.kaggle.com/code/wasdac/dogs-vs-cats-transfer-learning) | [Live Demo](https://dogs-vs-cats-inference.herokuapp.com/)  

### 🔹 Hand Cricket Using Mediapipe *(Apr 2022)*  
- Interactive **computer cricket game** using **hand gesture recognition** with Mediapipe + OpenCV.  
- [GitHub Repo](https://github.com/wasdac9/hand-cricket)  

### 🔹 Aadhaar Card Details Extraction *(Feb 2022)*  
- Extracted Aadhaar details using **OpenCV + Tesseract OCR**.  
- Automated KYC-style validation pipeline.  
- [GitHub Repo](https://github.com/wasdac9/aadhaar-ocr)  

### 🔹 Vaccine Certificate Dates Validation *(Jan 2022)*  
- Automated **vaccine date validation** from certificates using **OCR + GUI pipeline**.  
- [GitHub Repo](https://github.com/wasdac9/Vaccine-Certificate-DateValidation)  

### 🔹 AI Powered Computer *(2020–2021, Final Year Project)*  
- Controlled computer functions via **YOLOv3 hand gestures + speech recognition**.  
- Modules: **Mouse control, Application control, Audio commands**.  
- Published in *STM Journal of Image Processing and Pattern Recognition Progress (Vol 08, Issue 01)*.  

---

## 🌍 Languages  

- English | Hindi | Marathi  

---

## 🎮 Hobbies  

- Movies | Video Games | Travelling  

---

## 🔗 Links  

- **GitHub:** [github.com/wasdac9](https://github.com/wasdac9)  
- **Kaggle:** [kaggle.com/wasdac](https://www.kaggle.com/wasdac)  
- **LinkedIn:** [linkedin.com/in/tejas-ramekar](https://www.linkedin.com/in/tejas-ramekar)  

---
