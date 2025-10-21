# Pest_ID
By: Nicholas Kochanski (nkochanski),
Ryan McDonnell (ryanmcd03), 
Trent Thompson (TrentThompson1)

## 🦗 Description

This project uses machine learning techniques to identify 12 different agricultural pests.
It trains on 4,395 images of 12 different pests ranging from snails to moths, and then 
classifies the 1,099 images from the testing set. Our hope is that it may be used as an 
**accessable tool** for small scale farmers to identify pests so that they may take quicker and 
more informed actions.

**Dataset**: [Agricultural Pests Dataset (Kaggle)](https://www.kaggle.com/datasets/gauravduttakiit/agricultural-pests-dataset?resource=download&select=test)

## ⚙️ Requirements

To install the requirements, run:

```bash
pip install -r requirements.txt
```

**requiremments.txt** includes:

- tensorflow>=2.15.0
- numpy>=1.25.0
- pandas>=2.1.0
- scikit-learn>=1.3.0
- matplotlib>=3.8.0
- opencv-python>=4.8.0
- jupyter>=1.0.0

## 📁 Project Structure
Pest_ID/

├── .ipynb_checkpoints     # **Temporary backup folder**

├── test  📁               # **Folder containing testing data**

├── train 📁               # **Folder containing training data**

├── data_proc.ipynb        # **Notebook for data processing, testing, and training**

├── README.md              # **Project overview and setup instructions**

├── model.ipynb            # **Contains the model to be utilized**

└── requirements.txt       # **Dependencies**

## ⏳ Current Progress
- Loaded and preprocessed the dataset ✔️
- Completed initial training/testing ✔️
- Preliminary analysis shows improvement in accuracy ✔️
- Fine tune the model 🔜
- Evaluate the results 🔜
- Implement feature that allows users to upload photos to be ID'd 🔜

## 🤝 Acknowledgments

This project was created for ECE-4424/CS-4824 at Virginia Tech in Fall '25
