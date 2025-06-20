🌾 Early Rice Leaf Disease Detection
An AI-powered system for early detection of rice leaf diseases using machine learning and deep learning hybrid models. This project empowers farmers and researchers to diagnose crop diseases at an early stage, enabling timely intervention and minimizing yield loss.

🔍 Overview
This project focuses on identifying diseases in rice leaves using image-based analysis. It integrates classical machine learning and modern deep learning approaches to enhance detection accuracy.

✨ Key Features:

Accepts image input of rice leaves

Predicts the type of disease (or healthy)

Displays prediction probability in percentage

Combines handcrafted and deep features for better performance

🧠 Models Used
🎯 Baseline Model: Random Forest
Trained on extracted features (e.g., color, texture)

Good interpretability and fast prediction

🔬 Deep Feature Models:
VGG16 / VGG19 + SVM
Pre-trained VGG networks used to extract image features

SVM classifier trained on these deep features for disease classification

🌀 Wavelet Model: FBEWT + Random Forest
Features extracted using Fixed Boundary Empirical Wavelet Transform (FBEWT)

Combined with Random Forest for enhanced robustness

🖼️ Input Format
Input: Rice leaf image (.jpg, .png, etc.)

Output:

Predicted Disease Name

Probability (%)
Example:
Prediction: Bacterial Blight (92.3%)

🌿 Disease Classes
Supports classification of the following (based on the Paddy Doctor Dataset):

Bacterial Blight

Brown Spot

Leaf Blast

Healthy

📊 Evaluation Metrics
Accuracy, Precision, Recall, F1-score

Confusion Matrix

ROC-AUC Score

📚 Dataset
Paddy Doctor Dataset

Collected from real rice fields

Contains labeled images for four categories

📌 You can also augment this with synthetic images using GANs for future improvements.

📈 Future Enhancements
Add multi-language support (e.g., Hindi chatbot)

Integrate location-based risk mapping

Enable mobile camera input (via web app)
