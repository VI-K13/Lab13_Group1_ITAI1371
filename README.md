# Lab 13 – Building ML Pipelines

**Course:** ITAI 1371 – Machine Learning  
**Group:** Group 1  
**Team Members:** Viktoriya Kurmisheva, Tien Manh Nguyen, Zaid Alayedy

## Project Overview

This lab explores how Scikit-learn Pipelines can simplify machine learning workflows and reduce the risk of data leakage. We used the Titanic dataset to compare a traditional manual preprocessing approach with a Pipeline that combines data preparation and model training into one workflow.

## Lab Activities

- Loaded and prepared the Titanic dataset for classification.
- Applied manual preprocessing using StandardScaler and OneHotEncoder.
- Trained and evaluated a Random Forest Classifier.
- Created numerical and categorical preprocessing pipelines using SimpleImputer, StandardScaler, and OneHotEncoder.
- Combined preprocessing and model training using `make_column_transformer` and `make_pipeline`.
- Compared both approaches and discussed data leakage, reproducibility, and model deployment.

## Results

Both approaches achieved an accuracy of **82.68%** on the test dataset.

The Pipeline approach organized the preprocessing and training steps into a single workflow, making the code easier to maintain and reducing the risk of mistakes when processing new data.

## Tools and Technologies

Python, Google Colab, Pandas, NumPy, Scikit-learn, and the Titanic Dataset.

## Project Files

The repository includes the completed Jupyter Notebook and will include its PDF export, Reflection Journal, and Team Member Contribution Journal.

## Conclusion

This lab helped our group understand why Pipelines are useful for building reliable machine learning applications. We learned that organizing preprocessing and model training into one workflow can reduce errors, prevent data leakage, and make models easier to reuse and deploy.
