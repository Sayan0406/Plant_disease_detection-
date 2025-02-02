# 🌱 Plant Disease Detection 🔎🐛  

Plant Disease Detection is an advanced machine learning project leveraging **Convolutional Neural Networks (CNNs)** and deep learning to accurately identify and classify plant diseases. This tool provides **farmers and agricultural experts** with a quick and reliable diagnosis of plant health, enabling **timely intervention** and reducing potential crop losses.  

[🚀 **Live Demo**](https://github.com/Sayan0406/Plant_disease_detection-.git/)  

---

## 📂 Project Structure  

The repository includes the following essential components:  

- **`Plant_Disease_Detection.ipynb`** – Jupyter Notebook for model training.  
- **`main_app.py`** – Streamlit web application for disease prediction.  
- **`plant_disease_model.h5`** – Pre-trained model weights.  
- **`requirements.txt`** – List of necessary Python dependencies.  

---

## 🚀 Installation  

Follow these steps to set up and run the project locally:  

### 1️⃣ Clone the Repository  

```bash
git clone https://github.com/Sayan0406/Plant_disease_detection-.git
```

### 2️⃣ Navigate to the Project Directory  

```bash
cd Plant-Disease-Detection
```

### 3️⃣ Install Dependencies  

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Streamlit Web Application  

```bash
streamlit run main_app.py
```

---

## 🌿 Usage  

1. Run the Streamlit app.  
2. Open your browser and go to **[http://localhost:8501](http://localhost:8501)**.  
3. Upload an image of a **plant leaf**.  
4. The system will **analyze the image** and predict whether the plant is affected by any disease.  

---

## 🧠 Model Training  

The **CNN-based model** is trained using the **`Plant_Disease_Detection.ipynb`** notebook. The training dataset consists of various plant images categorized into different disease types. Once trained, the model weights are stored in **`plant_disease_model.h5`** for real-time predictions.  

---

## 🌐 Web Application  

The **`main_app.py`** script powers the **Streamlit-based web app**, allowing users to:  

✅ Upload plant images.  
✅ Get real-time disease predictions.  
✅ Take action based on AI-powered diagnosis.  

---

## 🛠️ Requirements  

Ensure you have the following Python packages installed:  

- `Keras==2.8.0`  
- `numpy==1.21.4`  
- `streamlit==1.18.0`  
- `opencv-python-headless==4.5.3`  
- `tensorflow==2.7.0`  

---

🚀 Start using **Plant Disease Detection** today to safeguard your crops and optimize agricultural productivity! 🌱💡
