# Web application developed in Python/Streamlit for faster & better Vizualization of data for ML. Key for EDA as well. 
This is in reference to my Blog --> https://shamikbhattacharya.wordpress.com/2022/02/22/story-telling-through-visualization-tools-in-python/ where visualization tools for 
Machine Learning in python was discussed.
In this project I will develope & discuss lot of web projects developed in one of best web tools available in python named Streamlite.
Speed is the essence in today's fast paced world. One of fastest way to build/deploy ML/AI models & projects in through web app. One option is to host through hiroku 
OR use STREAMLIT application from python. The fastest way to build and share data apps. Streamlit turns data scripts into shareable web apps in minutes. All in pure Python. 
if you haven't already check @streamlit it completely changed the way I think about prototypes and data apps. Removes a lot of frontend and design barriers for us data nerds.
if you do ML and work with Data@streamlit will breathe life into your work. It is when you can write it in Python itself. Make your machine learning app pretty and shareable with @streamlit.

# Python Codes developed are discussed below in short. Feel free to access & use them.
## ml_random_forrest_algo.py ==> This web web app that will allow you to automatically build a machine learning model by just uploading a CSV file
Through this app, I will be showing you how to build The **Machine Learning App in Python** using the Streamlit and Scikit-learn library. This web app will allow users to upload their own CSV file and specify the learning parameters of the random forest algorithm to use and it will use that to build a regression model
One can play with learning params of Random Forrest that is ==> Number of estimators & Seed number (random_state)

## ml_hyperparam_optimizer.py ==> The Machine Learning Hyperparameter Optimization Web App. 
This app allows any user to use this web to play with all possible combination of hyper params to arrive at best possible output/score in ML. Here also user 
can upload any raw data file in this web page & start playing with params to find the optium combination.

## Model_Performance_Calc.py ==> This web application calculates performance of your ML Model. 
This code is particularly useful when you prediction results from machine learning models lying around & now u need to spin up a code to **calculate the performance metrics**. 
You feed this app with the actual and predicted values and the app produces the performance metrics. I will keep adding lot of metrics later or infact use a diff python lib like *dabl & D-Tale*. This app uses logo.png & Y_example.csv which are also attached here.
Note : For this code to run, Pl add PIL lib of python *in your requirements.txt or in your setup env --> from PIL import Image*

## Best_Predict_Perf_Model.py ==> A machine learning model comparison web app in Python using the Streamlit and lazypredict libraries.
This app will allow you to *rapidly compare the prediction performance* of more than **30 machine learning models** in 1 step by simply uploading an input CSV file. After uploading the CSV file the models will be built and the app will allow you to download the results of the model performance.
“I need to fit the data for every model then apply metrics to check which model has better accuracy for the available dataset ,then choose best model and also this process is time-consuming and even it might not be that much effective too“.
For this problem, I got a simple solution when surfing through python org, which is a small python library by name “lazypredict” and it does wonders
Note : For this code to run, Pl add lazypredict lib of python *in your requirements.txt or in your setup env --> Pip install lazypredict*. Python version to chose is 3.6 or 3.7

## To execute these programs use :
pip install -r requirements.txt

streamlit run ml_hyperparam_optimizer.py
