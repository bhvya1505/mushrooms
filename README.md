# mushrooms
A Machine Learning Web App using Streamlit and Python

In this project we attempt to create an interactive web application using Streamlit and Python. Here we train Logistic Regression, Random Forest, and Support Vector Classifiers using scikit-learn on the [mushrooms.csv](https://www.kaggle.com/uciml/mushroom-classification) data set from UCI Machine Learning repository and plot evaluation metrics for binary classification algorithms.

Open the CSV file and rename the first column from 'class' to 'type' before you begin with the code.

Install Streamlit using pip as:
```
pip install streamlit
```
Run the file app.py using streamlit:
```
streamlit run app.py
```
You can now view your Streamlit app in your browser.

Streamlit changes the web application dynamically as we modify and save the app.py file. Thus, we need not run the file each time we modify.
