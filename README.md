# ai-driven-disease-classification
AI-Driven Symptom Based Disease Classification

🧠 AI-Driven Symptom-Based Disease Classification
📌 Overview
This project presents an AI-driven system for disease classification based on symptoms, developed as part of our Bachelor's thesis. The system leverages machine learning techniques to classify patient-reported symptoms into probable diseases. To demonstrate real-world applicability, we also developed a mobile application with a React Native frontend and a Python backend.

📊 Dataset
The dataset was sourced from Mendeley Data. We worked on 10 selected diseases relevant for early-stage symptom-based classification. Data was augmented and preprocessed to handle imbalance, encode symptoms, and improve training quality.
For evaluation, we curated a new test set using reliable healthcare resources, including:
1. World Health Organization (WHO)
2. Cleveland Clinic
3. Centers for Disease Control and Prevention (CDC)
4. MedlinePlus
5. Mayo Clinic

🛠️ Methodology
1. Data Preprocessing
- Symptom encoding
- Handling missing values
- Data augmentation to address class imbalance

2. Model Training
- Machine learning classifiers trained on symptom features
- Performance compared across multiple models
- Final selection based on accuracy and F1-score

3. Model Evaluation
- Independent testing on the newly created test set
- Results validated against trusted medical sources

📱 Application Development
To ensure accessibility and practical usage, we developed a mobile application:

1. Frontend: React Native
2. Backend: Python (Flask/FastAPI for inference API)
3. Features: Users can input symptoms, and the app predicts the most likely disease.

📈 Results
1. The system demonstrated strong classification performance across the selected diseases.
2. Independent testing confirmed its robustness and potential as a clinical decision support tool.
3. Full experimental results, metrics, and evaluation details are documented in the Thesis.

🔮 Future Work
1. Expanding dataset coverage beyond 10 diseases.
2. Integrating NLP for symptom input in natural language.
3. Deploying the model as a cloud-based API for wider scalability.
4. Enhancing the mobile app with multi-language support.
