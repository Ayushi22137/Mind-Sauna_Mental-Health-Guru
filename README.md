# Mind-Sauna_Mental-Health-Guru
## Description 
The increase of mental health problems and the need for effective medical health care have led to an investigation of machine learning that can be applied in mental health problems. Mental health problems detected at earlier stage helps the psychologist to medicate and enhance the patient’s life. As such, it becomes important to track and remedy any problems before they get too serious. We try achieving this using Mind Sauna. 
This project provides an evaluation of machine learning in mental healthcare. We performed a thorough analysis of the dataset to characterize the subjects’ behaviour based on different aspects of their PHQ9 question answering and textual inputs. Quiz Based Analysis is done using multiple machine learning algorithms (SVM, Naïve Bayes, KNN, DT, Random Forest) and TextBlob is used for detecting depression from sentiments.

## How to Set Up and Run the Project 
1.	Install all libraries $ pip install -r requirements.txt
2.	Run the application $ python server.py
3.	In Browser open URL localhost:5987

## How to Make Use of The Project

![Alt text](static/Screenshot (1).png?raw=true)

## Contribution
The project work was divided into two broad categories- Frontend and Backend. 

•	Backend work was further divided into two parts- 
Text Based Analysis (Sentiment Analysis) and Quiz Based Analysis (PHQ9 survey dataset analysis). I and Mansi worked on this part. We researched the available data, applied pre-processing, EDA, data manipulation and feature engineering, selected the appropriate model and tuned it.

Quiz Based Analysis was performed by me. The dataset was PHQ-9(Patient Health Questionnaire-9) Survey. I’ve applied 5 different ML algorithm/ classifier- Support Vector Machine, Naïve Bayes, KNN, Decision Tree, Random Forest on the dataset. SVM provided the best results with the highest F1 score and lowest log loss which were my chosen performance metric. The dataset was balanced, hence using these were justified. The results also conveyed that the more features are used, the higher the accuracy and F-measure scores in detecting depressed. However, the data set was very minimal and in the future, the research may be applied to a large data set to obtain more accuracy

Sentiment Based Analysis was performed by Mansi. It was a Natural Language Processing task and was performed using TextBlob. No dataset is required for this. TextBlob is one of the most prominent and easy-to-use libraries. As the official documentation suggests: TextBlob is a Python (2 and 3) library for processing textual data. It provides a simple API for diving into common natural language processing (NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.

•	Frontend work was performed by Lakshya. Our ML model is deployed to production using FLASK as an API. In order to get user input and then render your predictions as output, we needed a web-page structure and some aesthetics for better user experience. HTML is used to provide base structure and CSS gave aesthetics to it. He has written the code creating 6 HTML files in template folder i.e. “index.html”, “link.html”, “error.html”, “result.html”, “sentiment.html” and “tweetresult.html”. We have communicated with html files from our server.py file  which is heart of the project and links to our other files.






