# 🌱 Plant Disease Detection using CNN & Transfer Learning

This project detects **plant leaf diseases** from images using **Deep Learning (CNN + Transfer Learning with MobileNetV2)**.  
It is trained on the **PlantVillage dataset** and can classify multiple plant diseases such as **Potato, Tomato, and Pepper diseases**.

---

## 📂 Project Structure
plant-disease-detection/
│── data/ # dataset folder (PlantVillage via Kaggle)
│── models/ # saved trained models
│── notebooks/ # Jupyter notebooks for experiments
│── src/ # source code (training, prediction)
│── requirements.txt # dependencies list
│── README.md # project documentation
│── .gitignore # ignore unnecessary files

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

git clone https://github.com/your-username/plant-disease-detection.git
cd plant-disease-detection

2️⃣ Install Requirements

pip install -r requirements.txt

3️⃣ Download Dataset (PlantVillage)

You can download the dataset using Kaggle API:
kaggle datasets download -d plantvillage/plantvillage-dataset
unzip plantvillage-dataset.zip -d data/


🚀 Training the Model

4️⃣ Run Preprocessing Notebook

notebooks/data_preprocessing.ipynb
This will:

Load the dataset

Split into train/validation

Normalize images

Apply augmentation

5️⃣ Train Custom CNN Model

notebooks/model_building.ipynb
Here you can:

Build and train a Convolutional Neural Network (CNN)

Save the trained model into models/

6️⃣ Train with Transfer Learning

notebooks/transfer_learning.ipynb
Uses MobileNetV2 as a pretrained backbone

Improves accuracy and reduces training time

📊 Results

✅ Custom CNN trained up to ~85% accuracy

✅ Transfer Learning (MobileNetV2) boosted performance >90%

📈 Training & Validation accuracy/loss graphs included in notebooks

🔮 Future Work
Deploy model with Streamlit / Flask for live prediction

Convert model to TensorFlow Lite for mobile app usage

Extend dataset with more crops

👨‍💻 Author
Developed by Rishav Nagpal

📌 GitHub: your-username

💼 Freelancer Gig: Plant Disease Detection Model (CNN + Transfer Learning)
