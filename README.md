📝 Handwritten Character Recognition 

This project implements a Convolutional Neural Network (CNN) for recognizing handwritten English alphabets (A–Z) using the A–Z Handwritten Data dataset. The entire project is developed and run in Google Colab.

📁 Dataset
- Dataset: A–Z Handwritten Data.csv

- Source: The CSV file contains 372,450 labeled images of size 28x28 pixels for 26 English capital letters.

- Format: Each row in the CSV contains the label (0–25 representing A–Z) followed by 784 pixel values.

🚀 Technologies Used
- Python

- Google Colab

- TensorFlow / Keras

- NumPy & Pandas

- Matplotlib & Seaborn

- Scikit-learn


✅ Steps Performed
1.Data Preprocessing

- Normalization (scaling pixel values between 0 and 1)

- Reshaping to fit CNN input

- One-hot encoding of labels

2.Model Training

- Trained for 10+ epochs with batch size 128

- Adam optimizer & categorical_crossentropy loss

3.Evaluation

- Achieved >97% accuracy on test data

- Confusion matrix visualized

- Misclassified samples displayed

4.Visualization

- Predicted vs Actual labels on 10 random samples

- Confusion Matrix

- Misclassified Samples

5.Additional

- EarlyStopping callback added for efficient training



📊 Accuracy

- Final Test Accuracy: ~97%

📌 How to Run (Google Colab)

- Upload the dataset (A_Z Handwritten Data.csv) to Colab.

- Run all cells in the notebook sequentially.

- Visual outputs and predictions will be shown inline.

🔮 Future Improvements

- Use a larger/deeper CNN model

- Add support for lowercase letters or digits

-Deploy the model using a web app interface

🤝 Acknowledgements

- Dataset: Kaggle A–Z Handwritten Characters

- Libraries: TensorFlow, Keras, Librosa, Matplotlib, Seaborn

