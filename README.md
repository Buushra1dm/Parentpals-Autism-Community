# Autism Assist Chatbot

This project is a web application built using Flask, Flask-Login, Flask-SocketIO, and OpenAI's GPT-4 for providing support to individuals with autism. The chatbot assists users in both English and Arabic and helps individuals connect with others who share similar experiences. The application also includes a prediction model for autism detection and a user profile management system.

## Features

- **User Authentication**: Users can sign up, log in, and manage their profiles.
- **Profile Management**: Users can update their personal details such as age, gender, child age, diagnosis, and region.
- **Mentor Matching**: Users can find mentors based on specific criteria.
- **Chat Functionality**: Real-time messaging with other users using SocketIO.
- **Prediction Model**: An autism detection model that takes user inputs and predicts the likelihood of autism based on various factors.
- **Multi-language Support**: Chatbot supports both English and Arabic.
- **Community Posts**: Users can submit and view posts related to accomplishments or blog entries.

## Technologies Used

- **Backend**: Flask, Flask-Login, Flask-SocketIO
- **Model**: Scikit-learn's SGDClassifier for prediction
- **OpenAI GPT-4**: For generating responses to user queries
- **Web**: HTML, CSS, JavaScript (for frontend)
- **JSON**: Used for data storage (users, profiles, chats, posts)
  
## DEMO
