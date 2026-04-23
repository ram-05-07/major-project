"""
🧠 Quantum Dementia Classification (QDC)

📌 Project Overview:
This project focuses on early prediction of dementia using Quantum Machine Learning (QML) techniques.
A Quantum Support Vector Classifier (QSVC) is implemented and compared with a classical SVM model
to improve prediction accuracy and efficiency. The model uses clinical and cognitive features to
classify whether a person is affected by dementia.

🎯 Objective:
- Develop an efficient model for early dementia prediction
- Use Quantum Machine Learning (QSVM/QSVC) for better accuracy
- Compare performance with Classical SVM
- Reduce computational complexity while improving results

⚙️ Technologies Used:
- Python
- Qiskit (Quantum Computing)
- Scikit-learn
- NumPy & Pandas
- Matplotlib

📂 Dataset:
- The dataset (dems.csv) contains clinical and cognitive features
- Target column: Group (Demented / Non-Demented)

🧠 Methodology:
- Data Loading
- Data Preprocessing (cleaning & normalization)
- Feature Selection
- Train-Test Split
- Quantum Feature Mapping using Qiskit
- Train QSVC Model
- Train Classical SVM (for comparison)
- Evaluate using: Accuracy, Precision, Recall, F1-score

📊 Results:
- QSVC (Quantum Model) achieved ~95% accuracy
- Classical SVM achieved ~57% accuracy
- Quantum model captures complex patterns more effectively

📈 Graphs & Analysis:
- Accuracy comparison graphs
- Feature map performance analysis
- Model performance comparison (SVM vs QDC)

✨ Key Features:
- Quantum feature mapping using Qiskit
- Comparison with classical ML model
- Visualization of results
- Efficient and scalable approach

📌 Conclusion:
The proposed QDC model provides:
- Higher accuracy than classical methods
- Better handling of complex data relationships
- Faster and efficient prediction

🔮 Future Work:
- Use real quantum hardware instead of simulation
- Apply deep learning + quantum hybrid models
- Improve dataset size and features

🚀 HOW TO RUN (Google Colab):
1. Open notebook in Google Colab
2. Upload 'QSVC CODES.ipynb'
3. Upload dataset using:
   from google.colab import files
   files.upload()
4. Install libraries:
   !pip install qiskit scikit-learn matplotlib pandas numpy
5. Run all cells

✅ Expected Output:
- QSVC accuracy (~95%)
- SVM accuracy (~57%)
- Graphs comparing models
- Performance metrics (Precision, Recall, F1-score)

👩‍💻 Author:
S. Aisha Siddika
B.Tech – Computer Science & Engineering
"""
