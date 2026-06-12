# 🫁 PulmoDetect: COVID-19 Radiograph Diagnosis

PulmoDetect is a machine learning-based diagnostic support system designed for early detection of COVID-19 from chest X-ray images. The project leverages a hybrid CNN–SVM architecture, combining deep learning feature extraction with classical machine learning classification to improve predictive performance and reliability.

---

## 📌 Project Overview

Medical imaging plays a crucial role in assisting clinical diagnosis, especially during respiratory disease outbreaks such as COVID-19. PulmoDetect applies artificial intelligence to analyze chest radiographs and detect patterns associated with infection.

The system uses a Convolutional Neural Network (CNN) for automated feature extraction, followed by a Support Vector Machine (SVM) classifier for final prediction. This hybrid approach enhances accuracy, particularly when working with limited datasets.

The goal of this project is to demonstrate how AI can support healthcare professionals as a decision-support tool in medical image analysis.

---

## ⭐ Key Features

- Automated chest X-ray image classification  
- Hybrid CNN–SVM architecture for improved accuracy  
- Deep feature extraction using CNN  
- Classical machine learning classification using SVM  
- Image preprocessing and inference pipeline  
- Streamlit-based interactive web application  
- Medical report generation in Word format  



## 🛠️ Tech Stack

- Python  
- TensorFlow / Keras  
- Scikit-learn  
- NumPy  
- OpenCV  
- Streamlit  
- Plotly  
- python-docx  
---

---

## 📊 Model Performance

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 97.71% |
| Precision | 96.30% |
| Recall    | 94.74% |
| F1 Score  | 95.49% |


---

## 📂 Project Structure

```text
PulmoDetect-COVID-Radiograph-Diagnosis/
│
├── .gitignore
├── README.md
├── app.py
├── launch_app.bat
├── setup_pulmodetect.bat
└── requirements.txt
```

---

## 🚀 Steps to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Dhanyaa-shree/PulmoDetect-COVID-Radiograph-Diagnosis.git
cd PulmoDetect-COVID-Radiograph-Diagnosis
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Application

```bash
streamlit run app.py
```

### 4. Access the Application

Open your browser and navigate to:

```text
http://localhost:8501
```

### 5. Use PulmoDetect

* Upload a chest X-ray image.
* Click **Predict**.
* View the COVID-19 diagnosis result.
* Generate and download the medical report.
---


---

## 🚀 Future Enhancements

* Multi-class lung disease classification
* Explainable AI (Grad-CAM visualizations)
* Cloud deployment
* Integration with hospital information systems
* Enhanced report generation

---

## 👩‍💻 Author

**Dhanyaa Shree**

* GitHub: https://github.com/Dhanyaa-shree

---

## 📜 License

This project is developed for educational and research purposes.
