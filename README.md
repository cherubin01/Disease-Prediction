Disease Prediction from Symptoms
This project explores the use of machine learning algorithms to predict diseases from symptoms.

Algorithms Explored
The following algorithms have been explored in the code:

Naive Bayes
Decision Tree
Random Forest
Gradient Boosting
Dataset
Source-1
The dataset for this problem used with the main.py script is downloaded from Kaggle.

This dataset has 133 total columns, 132 of them being symptoms experienced by patients and the last column is the prognosis for the same.

Source-2
The dataset for this problem used with the Jupyter notebook is downloaded from here.

This dataset has 3 columns:

Disease
Count of Disease Occurrence
Symptom
You can either copy-paste the whole table from the website to an Excel sheet or scrape it using Beautifulsoup.

Directory Structure

|_ dataset/
         |_ training_data.csv
         |_ test_data.csv

|_ saved_model/
         |_ [pre-trained models]

|_ main.py [code for loading Kaggle dataset, training & saving the model]

|_ notebook/
         |_ dataset/
                  |_ raw_data.xlsx [Columbia dataset for notebook]
         |_ Disease-Prediction-from-Symptoms-checkpoint.ipynb [IPython Notebook for loading Columbia dataset, training model, and inference]
Usage
Please make sure to install all dependencies before running the demo, using the following:


pip install -r requirements.txt
Interactive Demo
For running an interactive demo or sharing it with others, please run demo.py using Jupyter Notebook or Jupyter Lab.


jupyter notebook demo.ipynb
Standalone Demo
For running the inference on the test set or on custom inputs, you can also use the infr.py file as follows:


python infer.py
