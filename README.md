# Healytic: AI-Powered Healthcare Assistant

**Healytic** is an intelligent healthcare support system powered by Machine Learning and Natural Language Processing (NLP). It predicts diseases with high accuracy based on user-provided symptoms and offers a comprehensive healthcare plan including medications, preventive measures, tailored diet plans, and optimized workout routines — all in real-time.

---

## 🧠 Features

- 🎯 **Accurate Disease Prediction**  
  Utilizes a **Random Forest** classifier trained on labeled medical data for precise symptom-to-disease mapping.

- 🗣️ **NLP-Based Symptom Analysis**  
  Processes natural language symptom input (e.g., “I feel short of breath and have a fever”) and maps it to structured features for diagnosis.

- 💊 **Personalized Medication Suggestions**  
  Recommends over-the-counter medications and treatment advice based on identified conditions.

- 🥗 **Tailored Diet Plans**  
  Suggests custom diet plans considering the diagnosed illness and user health profiles.

- 🏃 **Optimized Workout Recommendations**  
  Provides safe and effective exercises tailored to individual fitness goals and medical limitations.

- 📘 **Disease Insights**  
  Offers easy-to-understand explanations and preventive tips for predicted conditions.

- ⏱️ **Real-Time Response**  
  Enables quick diagnostics and instant healthcare guidance.

---

## 🏗️ System Architecture

1. **User Input**: Symptom entry through text interface.
2. **Symptom Parsing (NLP)**: Transforms unstructured text into symptom vectors.
3. **Disease Prediction Model**: Random Forest classifier predicts the disease.
4. **Module Outputs**:
    - Medication recommender
    - Diet plan generator
    - Workout plan optimizer
    - Preventive tips & education

---

## 🚀 Technologies Used

- **Python 3.x**
- **Scikit-learn** – Random Forest for classification
- **NLTK / spaCy** – Natural Language Processing
- **Pandas / NumPy** – Data manipulation
- **Matplotlib / Seaborn** – Visualization (optional for analysis)
- **Tkinter / Streamlit / Flask** – (Optional UI framework)

---

## 📂 Directory Structure
Healytic/
│
├── data/ # Preprocessed datasets (symptoms, diseases, medications, etc.)
├── models/ # Trained ML model (.pkl)
├── nlp/ # NLP preprocessing scripts
├── utils/ # Helper scripts (diet planner, medication logic, workout generator)
├── app.py # Main execution script
├── requirements.txt # Required packages
└── README.md # Project documentation

yaml
Copy
Edit
🔒 Disclaimer
Healytic is intended for educational and experimental purposes only. It is not a replacement for professional medical advice. Always consult a licensed healthcare provider for accurate diagnosis and treatment.

🙌 Acknowledgments
Thanks to open medical datasets and open-source contributors in the field of health informatics and artificial intelligence.

📬 Contact
Developer: Mubashir Ajaz
Email: [mubashirajaz17@gmail.com]

