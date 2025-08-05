#  Heart Disease Detection using Feedforward Neural Network

This project predicts whether a patient has heart disease using a **Feedforward Neural Network (Multi-Layer Perceptron)** trained on medical records.  
It uses features like age, cholesterol, blood pressure, and ECG results to make predictions.

---

## Project Overview
Heart disease is a major global health concern.  
This project applies deep learning techniques to structured medical data to classify patients as **having** or **not having** heart disease.  
The model is trained and evaluated to achieve high accuracy in predictions.

---

## Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn  
- **Model Type:** Multi-Layer Perceptron (MLP)  

---

##  Dataset
- **Target Variable:** `target`  
  - `1` → Heart disease present  
  - `0` → No heart disease  
- **Features:** Age, Sex, Chest pain type, Blood pressure, Cholesterol, Fasting blood sugar, ECG results, Maximum heart rate, Exercise-induced angina, ST depression, Slope, Major vessels, Thalassemia.

---

## How It Works
1. Data preprocessing with feature scaling and train-test split.
2. Neural network architecture:
   - Dense layer (64 units, ReLU) → Dropout
   - Dense layer (32 units, ReLU) → Dropout
   - Output layer (Sigmoid activation for binary classification)
3. Model training with validation monitoring.
4. Performance evaluation using accuracy, classification report, and confusion matrix.
5. Visualization of training accuracy over epochs.

---

## Results
- **Accuracy:** ~85–90% on test data  
- Confusion matrix and classification report generated for detailed evaluation.

---

## Future Enhancements
- Hyperparameter tuning for improved accuracy  
- Integration with a user-friendly UI (Gradio/Streamlit) for live predictions  
- Testing on larger, more diverse datasets  
