# WineVarietyPrediction

Insights from the wine variety dataset are given i report.docx

The actual notebook is wine.ipynb where you can find the code using which I have produced the insights

I have trained a randomForestClassifier based on the tf-idf processing of review description. The results of the training is there at the end of the notebook. 

I have extracted the trained weights of the random forest model and tfidf vectorizer so that we can use it in real time.
You can go to the google drive link provided in the top of the winePredicton.py. Download and extract the zip and place both the weight files in the directory of the python file.
Then you can choose any random review description from the dataset and provide it as an input to the script as a text. 
The script will then load the weights pass the string input and predict the wine variety.
