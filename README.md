🌾 Rice Leaf Disease Detection Using Deep Learning

A deep learning-based computer vision project to classify rice leaf diseases using image classification and transfer learning.

📌 Project Overview

Rice crops are affected by several diseases that can reduce crop quality and agricultural productivity. This project uses deep learning techniques to identify rice leaf diseases from images.

The system classifies rice leaf images into three categories:

* Bacterial Leaf Blight
* Brown Spot
* Leaf Smut

Multiple deep learning models were developed and evaluated to identify the most suitable model for classification.

🎯 Objectives

* Perform exploratory data analysis (EDA) on the rice leaf image dataset.
* Preprocess and prepare images for deep learning.
* Apply data augmentation to improve model generalization.
* Develop and evaluate multiple deep learning models.
* Compare model performance and select the best-performing model.
* Predict rice leaf diseases from new images.

📂 Dataset

The dataset contains images belonging to three disease classes.

Disease Class	Number of Images
Bacterial Leaf Blight	40
Brown Spot	40
Leaf Smut	39
Total	119

The dataset contains images of rice leaves affected by different diseases.

🧠 Models Implemented

The following models were evaluated:

* Custom CNN
* MobileNetV2
* ResNet50
* EfficientNetB0

Transfer learning was explored using pretrained architectures.

📊 Model Performance

Model	Test Accuracy
Custom CNN	33.33%
MobileNetV2	88.89%
ResNet50	38.89%
EfficientNetB0	33.33%

🏆 Best Model

MobileNetV2 achieved the highest test accuracy of 88.89% and was selected as the best-performing model among the evaluated models.

The model correctly classified 16 out of 18 test images.

MobileNetV2 Classification Results

Disease	Precision	Recall	F1-Score
Bacterial Leaf Blight	1.00	1.00	1.00
Brown Spot	1.00	0.83	0.91
Leaf Smut	0.86	1.00	0.92

Overall Test Accuracy: 94.44%

Note: Results may vary depending on data splitting, training configuration, and random initialization. The dataset and test set are relatively small, so further validation using a larger dataset is recommended.

🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* OpenCV
* Jupyter Notebook

📁 Project Structure

Rice-Leaf-Disease-Detection/
│
├── Dataset/
│   ├── Bacterial leaf blight/
│   ├── Brown spot/
│   └── Leaf smut/
│
├── models/
│   └── mobilenetv2_normal.keras
│
├── Rice_Leaf_Disease_Detection_.ipynb
├── README.md
└── .gitignore

🚀 How to Run

1. Clone the repository

git clone https://github.com/chaitanyapatil1-a11y/Rice-Leaf-Disease-Detection.git

2. Navigate into the project

cd Rice-Leaf-Disease-Detection

3. Install dependencies

pip install tensorflow numpy pandas matplotlib seaborn scikit-learn opencv-python jupyter

4. Open the Jupyter Notebook

jupyter notebook

Open Rice_Leaf_Disease_Detection_.ipynb and run the notebook cells.

🔮 Future Improvements

* Increase dataset size.
* Collect more diverse rice leaf images.
* Improve model generalization.
* Deploy the model using Streamlit.
* Develop a real-time disease prediction application.
* Explore additional rice diseases.

👨‍💻 Author

Chaitanya Patil

B.Tech – Artificial Intelligence and Machine Learning

⭐ If you find this project interesting, feel free to explore the repository!