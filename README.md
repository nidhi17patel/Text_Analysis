<h1 align="center">
             Complete Text Analysis Web App 💬 📝 ✍️
</h1>

![image](https://user-images.githubusercontent.com/78029145/154792740-dadca757-5424-4e4c-af69-fc3a5055af3b.png)

This app is used to perform an indepth analysis of a text
The analysis sections include ->

**1. Spam or Ham Detection**

**2. Sentiment Analysis**

**3. Stress Detection**

**4. Hate & Offensive Content Detection**

**5. Sarcasm Detection**

## Tech Stacks Used

<img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/>

## Libraries Used

<img src="https://img.shields.io/badge/numpy%20-%2314354C.svg?&style=for-the-badge&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/pandas%20-%2314354C.svg?&style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/streamlit%20-%2314354C.svg?&style=for-the-badge&logo=streamlit&logoColor=white"/> <img src="https://img.shields.io/badge/nltk%20-%2314354C.svg?&style=for-the-badge&logo=nltk&logoColor=white"/> <img src="https://img.shields.io/badge/scikitlearn%20-%2314354C.svg?&style=for-the-badge&logo=scikitlearn&logoColor=white"/>

## Structure Of The Project

- Each prediction page is conneceted with a Machine Learning Model which uses either of Logistic Regression, Decision Tree, Random Forest Algorithms to predict the results.
- Also we have 5 different datasets being used for each prediction.
- We can land into each prediction site of the web app from the options in the Navigation Menu.
- We have only 1 relevant feature taken into consideration which is the text and then the text is preprocessed and vectoized with help of TF-IDF Vectorizer to fit into the model and tain it.
- So the user gets a broad overview of the text after the analysis

## The feature taken into consideration

| Text Analysis Type | Feature |
| - | - |
| Spam or Ham Detection Page | Text |
| Sentiment Analysis Page | Text |
| Stress Detection Page | Text |
| Hate & Offensive Content Page | Text |
| Sarcasm Detection | Text |

The text is preprocessed then fed to the model.

## Deployment Of The Project

After the modeling part the model is deployed using Streamlit library on Streamlit Share so that the app is available for usage for everyone.

## Glance At The Hosted Application- 

### 1. Home Page
![image](Output\Home_Page.png)

### 2. Spam or Ham Detection Page
![image](Output\Spam-Ham.png)

### 3. Sentiment Analysis Page
![image](Output\Sentiment_Analysis.png)

### 4. Stress Detection Page
![image](Output\Stress_Detection.png)

### 5. Hate & Offensive Content Page
![image](Output\Hate_Text.png)

### 6. Sarcasm Detection Page
![image](Output\Sarcasm.png)
