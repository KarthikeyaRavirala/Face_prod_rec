# 🧴 Face Skin Recommendation System

An AI-powered system that analyzes facial skin using images and user input to recommend personalized skincare routines. It leverages deep learning, dermatological data, and environmental awareness to deliver smart, tailored skincare advice.

---

## 💡 Project Objective

To develop a multimodal skincare recommendation system that combines facial image analysis and lifestyle data to provide users with personalized skincare suggestions. This system is ideal for personal beauty apps, virtual dermatologists, and AI-driven e-commerce integrations.

---

## 🚀 Features

* 🔍 Skin concern detection (e.g., acne, dryness, pigmentation)
* 📷 Image-based skin analysis using deep learning
* 📝 User questionnaire for lifestyle & allergy inputs
* 🌍 Environment-aware recommendations (UV, humidity, pollution)
* 🧴 Personalized product and routine suggestions
* 💬 Integrated chatbot for skincare guidance

---

## 🧪 Tech Stack

| Domain           | Tools & Technologies                       |
| ---------------- | ------------------------------------------ |
| Frontend         | React.js / React Native                    |
| Backend API      | FastAPI / Flask                            |
| Machine Learning | TensorFlow / PyTorch, OpenCV, Scikit-learn |
| Deployment       | AWS EC2 / Firebase / Render                |
| Database         | PostgreSQL / MongoDB / Firebase Firestore  |
| Storage          | Firebase Storage / AWS S3                  |
| Annotation       | Label Studio / Roboflow                    |

---

## 🧬 Models Used

* **CNN (ResNet/EfficientNet)** – For facial image feature extraction and skin condition classification
* **U-Net / DeepLabV3+** – Optional skin segmentation for precise region analysis
* **MLP / Random Forest** – For interpreting questionnaire-based inputs
* **Multimodal Fusion Model** – Combines image and lifestyle features for holistic recommendations

---

## 📷 System Architecture

```
User Input (Image + Survey)
        ↓
Frontend (React.js / Mobile App)
        ↓
Backend API (FastAPI/Flask)
        ↓
Preprocessing (OpenCV + Data Cleaning)
        ↓
ML Models (CNN + Tabular + Fusion Layer)
        ↓
Recommendation Engine (Product Matching + Advice)
        ↓
Output to User (Routine, Product, Feedback)
```

---

## ⟳ System Workflow

1. **User Input**: Upload face image + answer lifestyle questionnaire
2. **Preprocessing**: Normalize images, clean survey data
3. **Feature Extraction**:

   * CNN model extracts visual skin features
   * MLP analyzes user data
4. **Model Inference**:

   * Skin conditions detected
   * Combined with profile & environment info
5. **Personalized Recommendation**:

   * Skincare products
   * Daily routine suggestions
6. **Optional Feedback Loop**: User satisfaction stored for model fine-tuning

---

## 📊 Evaluation Metrics

| Model Type      | Metrics Used                              |
| --------------- | ----------------------------------------- |
| Skin Detection  | Accuracy, Precision, Recall, F1-Score     |
| Segmentation    | IoU, Dice Coefficient                     |
| Recommendations | Precision\@k, NDCG, User Feedback Ratings |
| Overall UX      | Mean Opinion Score (MOS), Retention Rate  |

---

## 📦 Datasets & Resources

* 🧪 [HAM10000 (Skin Lesion)](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000)
* 🧴 [Fitzpatrick17k (Skin Tone Diversity)](https://github.com/microsoft/FaceSynthetics)
* 🌐 [BCN20000 (Skin Diagnosis)](https://bcn20000.eurecat.org/)
* 📁 WHO Guidelines on Dermatological Health
* 🛠️ Labeling Tools: Label Studio, Roboflow

---

## 🔮 Future Improvements

* 📱 Real-time mobile deployment (using TFLite / ONNX)
* 🧠 GPT-powered skincare assistant chatbot
* 🌎 Global skin tone calibration & ethnic bias reduction
* 📊 Skincare diary & progress tracking calendar
* 💬 Voice-enabled recommendations

---

## 👨‍💻 How to Run the Project

### 📁 Setup

```bash
git clone https://github.com/yourusername/face-skin-recommendation.git
cd face-skin-recommendation
pip install -r requirements.txt
```

### 🚀 Launch Backend

```bash
cd backend
uvicorn main:app --reload
```

### 🗅️ Launch Frontend

```bash
cd frontend
npm install
npm start
```

---

## 🤝 Contributing

Pull requests and issue reports are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 👤 Author

**Buddy** – AI Developer | Passionate about skincare, ethics & innovation
📧 Contact: [your@email.com](mailto:your@email.com)
🌐 Portfolio: [yourportfolio.com](https://yourportfolio.com)
🔗 [LinkedIn](https://linkedin.com/in/yourprofile)

---

## 📄 License

MIT License – feel free to use, adapt, and grow with this project.
