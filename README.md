# 🛰️ Dam Crack Detection Using UAV and YOLOv10

## 👤 Author
Kannan A, 
M.Tech Big Data Analytics,
VIT Chennai  
Guided by Dr. Maheswari S.

---

## 📌 Project Overview
This project implements a deep learning-based crack detection system for dam surfaces using the YOLOv10 object detection algorithm. The objective is to detect and classify cracks from aerial imagery, simulating UAV-based inspections. The model was trained using the publicly available [SDNET2018 dataset](https://www.kaggle.com/datasets/aniruddhsharma/structural-defects-network-concrete-crack-images) and deployed on Google Colab for model training and evaluation.

---

## 🚁 Dataset Used
- **Name**: Structural Defects Network (SDNET2018)  
- **Source**: [Kaggle - SDNET2018 Dataset](https://www.kaggle.com/datasets/aniruddhsharma/structural-defects-network-concrete-crack-images)  
- **Description**: The dataset contains over 56,000 annotated concrete surface images with and without cracks. It includes various surface textures (painted, unpainted, rough, smooth) and lighting conditions.

---

## 🔧 Technologies & Tools
- Python 3.x  
- Google Colab  
- YOLOv10 (manually uploaded)  
- PyTorch  
- OpenCV  
- LabelImg (for optional custom annotation)

---

## 📂 Project Structure

📁 dam-crack-detection/
├── dam_crack_detection_yolov10.ipynb # Main Colab notebook
├── README.md # Project documentation
├── yolov10/ # YOLOv10 model files (if added)
└── datasets/ # Sample or test images (optional)


---

## ⚙️ Steps Performed
1. Defined objectives such as crack types, detection accuracy, and UAV simulation.
2. Reviewed literature on UAV-based dam crack detection and YOLO applications.
3. Used SDNET2018 dataset for training and testing purposes.
4. Preprocessed images (resizing, normalization, noise reduction).
5. Annotated data using LabelImg (optional; dataset already contains labeled images).
6. Configured and trained YOLOv10 using Google Colab.
7. Validated model on a test split and fine-tuned hyperparameters.
8. Evaluated model performance using precision, recall, and mAP.
9. Achieved a precision of 93% on test data.
10. Tested the model on unseen images to verify detection performance.

---

## ✅ Results
The YOLOv10-based deep learning model achieved a **precision of 93%**, demonstrating strong capability in detecting structural cracks in concrete images. The model proved robust across varying conditions, surface textures, and crack types, making it suitable for integration in UAV-based inspection systems for dams and other infrastructure.

---

## 🚀 How to Use
1. Clone or download this repository.
2. Open `dam_crack_detection_yolov10.ipynb` in Google Colab.
3. Upload or link the SDNET2018 dataset.
4. Install dependencies:
   ```bash
   !pip install -r requirements.txt

Run the notebook step-by-step to train, validate, and test the model.

📌 Dataset Credits
Dataset: SDNET2018 - Structural Defects Network
Provided by: Aniruddh Sharma on Kaggle

📃 License & Usage
This project is for educational and research purposes only. Please follow dataset and YOLOv10 licensing terms for any reuse or redistribution.

📬 Contact
For questions or feedback, please raise an issue in the GitHub repository or contact via institutional email if applicable.


---

✅ You can **copy and paste** this into your GitHub repository’s `README.md` file. Let me know if you’d like it as a downloadable file too.



