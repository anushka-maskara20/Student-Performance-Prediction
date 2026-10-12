# Student Performance Prediction Using Machine Learning

## Project Overview
This project predicts student performance by classifying students into **Low, Medium, and High** categories based on their final mathematics grades. It explores how machine learning can help identify students who may need additional academic support.

## Dataset
- Source: [UCI Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)
- File: "student-mat.csv"
- Records: 395 students

## Setup Instructions
1. Download "student-mat.csv" from the dataset link above.
2. Open "IEEE_ML.ipynb" in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Upload the dataset if required and ensure the file path in the notebook is correct.
4. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

5. Run the notebook cells from top to bottom.

## Models Used
- Decision Tree
- K-Nearest Neighbors (KNN)
- Random Forest
- Gradient Boosting

## Results

 Model              Test Accuracy 
 Decision Tree        84.81% 
 KNN                  65.82% 
 Random Forest        88.61% 
 Gradient Boosting    87.34% 

Random Forest achieved the highest test accuracy of **88.61%**. Gradient Boosting achieved the highest mean 5-fold cross-validation accuracy of **89.54%**.

Models were evaluated using accuracy, confusion matrices, classification reports, and stratified cross-validation.

## Conclusion
Random Forest performed best on the separate test set, while Gradient Boosting achieved the best average cross-validation accuracy. This project provided practical experience in data preparation, machine learning model training, and performance evaluation. The predictions may help identify students who could benefit from academic support, but should be treated as guidance rather than definitive judgments.

