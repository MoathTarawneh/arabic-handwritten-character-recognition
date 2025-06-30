# Arabic Handwritten Character Recognition

This project focuses on classifying Arabic handwritten characters using a Convolutional Neural Network (CNN). The model is trained on a labeled dataset and implemented entirely in Jupyter Notebook. The repository includes the dataset, preprocessing steps, model training and evaluation, and a saved model for future inference.

==========================
📁 Contents of the Repository
==========================

- Arabic Handwritten Character Dataset.zip  
  Contains the full dataset including both images and CSV label files.  
  Dataset source: https://www.kaggle.com/datasets/mloey1/ahcd1

- About the Dataset.txt  
  A brief description of the dataset, including class structure and format.

- AI & ML Project.ipynb  
  The complete source code in Jupyter Notebook format. It includes preprocessing, CNN architecture, training, testing, and result visualization.

- AI & ML Project.html  
  A static HTML export of the notebook for easier viewing.

- best_model.keras  
  The trained model file in Keras format for direct use or fine-tuning.

==========================
🧠 Model Overview
==========================

- Architecture: Convolutional Neural Network (CNN)
- Input size: 32×32 grayscale images
- Output: 28 Arabic characters
- Optimizer: Adam
- Loss function: Categorical Crossentropy
- Accuracy: 96%

==========================
📜 How to Run
==========================

1. Clone the repository or download it as ZIP
2. Install required packages (use a Jupyter environment with TensorFlow, NumPy, etc.)
3. Open 'AI & ML Project.ipynb' in Jupyter Notebook
4. Run the notebook to train or evaluate the model

==========================
📖 License
==========================

This project is open-source. You can freely use and modify it for educational and research purposes.

