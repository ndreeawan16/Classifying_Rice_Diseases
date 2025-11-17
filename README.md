🌾 Rice Leaf Disease Classification

📌 Overview
This project focuses on classifying rice leaf diseases using a simplified CNN architecture. Previous research using ResNet101 achieved 100% accuracy but suffered from high loss and overfitting. This study improves the model by reducing architectural complexity and comparing two simplified models with the ResNet101 baseline.

🎯 Key Findings
Simplified architecture achieves 100% accuracy with 2.91% loss.
Overfitting from the previous model is significantly reduced.
Proper layer arrangement is highly effective even with a small dataset.

🔧 Technologies
Python

TensorFlow / Keras

NumPy, Pandas

Matplotlib

🚀 Run the Model
git clone https://github.com/yourusername/Classifying_Rice_Diseases.git
cd Classifying_Rice_Diseases
pip install -r requirements.txt
python train.py

📚 Conclusion
Simplifying the model architecture leads to more stable predictions and better loss performance, proving that model complexity must align with dataset size.
