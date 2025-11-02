🧠 ZFN Algorithm for EEG-Based Emotion Recognition

Created by LAO and BRP — 2025

This repository contains the implementation of the Zero-Dimension Feature Network (ZFN) algorithm, developed for multi-class emotion recognition using EEG signals.
The project includes model architecture, training scripts, and evaluation procedures.

📊 Dataset Information

This study uses the publicly available SEED EEG Dataset (SJTU Emotion EEG Dataset) developed by the Brain-Computer Interface and Machine Intelligence (BCMI) Laboratory,
Shanghai Jiao Tong University (SJTU) — [Zheng & Lu, 2015].
🔗 http://bcmi.sjtu.edu.cn/home/seed/

Please ensure compliance with the dataset’s usage policy when downloading or using it for research purposes.

⚙️ Implementation

Frameworks: TensorFlow 2.12, Keras 2.9, NumPy, Scikit-learn
Environment: Google Colab / Python 3.10
Optimizer: Adam (learning rate = 0.001)
Regularization: Early stopping and dropout applied
📈 Key Features

Squeeze-based dimensionality reduction
Three dense layers with ReLU activation
Dropout (30%) to mitigate overfitting
Softmax output layer for three-class emotion classification (positive, neutral, negative)
📬 Contact

For questions or collaborations, please contact:
📧 laoktaviana@gmail.com
