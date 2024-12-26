# Email and SMS Spam Classifier

This project is an **Email and SMS Spam Classification Application** that identifies whether a message is **Spam** or **Not Spam** using machine learning techniques. It provides a user-friendly web interface for real-time classification of messages.

## View the live website
Click the link to view the website  (https://emailandsmsspamclassifier-wzkfcwm7xu4ixgn7nkvppf.streamlit.app/)
## Features

- **Accurate Predictions**: The model uses Natural Language Processing (NLP) techniques and machine learning algorithms to classify messages with high accuracy.
- **User-Friendly Interface**: A simple and intuitive web application where users can input a message and get instant predictions.
- **Efficient Model**: Pre-trained model (`model.pkl`) and TF-IDF vectorizer (`vectorizer.pkl`) ensure fast and reliable results.
- **Dataset**: Trained on a robust dataset of labeled SMS and email messages.


## Input Fields

- **Message Text**: Enter the content of the email or SMS message you want to classify.


## Output

The application will output whether the given message is:
- **Spam**: The message is classified as unwanted or promotional content.
- **Not Spam**: The message is classified as legitimate communication.
--- 
## Screenshots
### Application Interface
![image](https://github.com/user-attachments/assets/3074ce82-e47f-4c97-a58f-ae3b020b7f77)

### Results
![image](https://github.com/user-attachments/assets/1fa506eb-30d5-4a47-aec3-5dd8cb1d7cb6)


![image](https://github.com/user-attachments/assets/5a8e47aa-a3d6-44cd-bb1c-8cf5d22da0d6)


---

## Technologies Used

- **Streamlit**: For building the interactive web interface.
- **Python**: For backend logic and NLP preprocessing.
- **scikit-learn**: For the pre-trained machine learning model.
- **NLTK**: For text preprocessing, including tokenization, stopword removal, and stemming.
- **pickle**: For saving and loading the model and vectorizer.



## Dataset

The model is trained on a dataset containing labeled emails and SMS messages as either **Spam** or **Ham (Not Spam)**. The dataset has been preprocessed to remove noise and ensure optimal performance.


## Model

A **Naive Bayes** model is used to classify the messages. The model was trained on preprocessed text data and saved as `model.pkl` for inference. Text vectorization was performed using **TF-IDF**, saved as `vectorizer.pkl`.


## Deployment

This application is deployed using **Streamlit** and can be run locally or hosted on platforms like Streamlit Cloud, Heroku, or Render.

