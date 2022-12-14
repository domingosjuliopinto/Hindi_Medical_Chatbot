# Hindi Medical Chatbot
This is a Medical Health Chatbot in Hindi Language. It is an extractive chatbot and will chat with the user in hindi language only.

# This Readme Contains
* [Introduction](#introduction)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Activity Diagrams](#activity-diagrams)
* [Screenshots](#screenshots)
* [Drawbacks](#drawbacks)
* [References](#references)

## Introduction

Language is a very important thing in this world which helps us bond together, talk to people, understand each other and do many more things. Many people in the world only know one language that is their mother tongue. In a country like India,many people mostly in the north and the central region of India, know only hindi or the regional language used in their region. Many people who aren’t educated or are educated in hindi medium prefer to communicate or read and write in hindi. The information provided on the internet or the chatbots only facilitate or use English as their primary language which makes it difficult for people who don’t know English. Many people in this region want to know or get information about various diseases or health related issues but due to the information available in English, it's difficult for the people to understand and process the information. So in order to solve all this problem we made a Health chatbot in Hindi which will help people to get information in Hindi about various health diseases, symptoms and home remedies to cure the disease and respond to the chatbot in hindi only.

## Technologies Used
- Python and Various Python Libraries
- Colab
- Gradio

## Features
- It will give you knowledge regarding the sickness based on your questions
- It will guess what sickness you have based on the symptoms 

## Activity Diagrams
Activity Diagram to select Module<br>
![](diagrams/selectingmod.png)<br>
Activity diagram for preprocessing<br>
![](diagrams/preprocess.png)<br>
Activity Diagram for sickness knowledge module<br>
![](diagrams/sickknowledge.png)<br>
Activity Diagram for symptoms to sickness module<br>
![](diagrams/symptosick.png)

## Screenshots

![Capture](https://user-images.githubusercontent.com/71319075/199654603-c18349a0-777d-4d9d-a996-81c8c4360077.PNG)
![Capture1](https://user-images.githubusercontent.com/71319075/199654619-3463aa12-a000-431f-af89-39cbc96412b3.PNG)
![Capture2](https://user-images.githubusercontent.com/71319075/199654638-f552f6aa-6792-47d3-b2c9-ced2b9fc3948.PNG)
![Capture3](https://user-images.githubusercontent.com/71319075/199654648-2fe7830e-0121-43e4-a60b-3e1dc76911a5.PNG)
![Capture4](https://user-images.githubusercontent.com/71319075/199654654-27035409-51b5-4443-9f80-a454e88f9a41.PNG)
![Capture5](https://user-images.githubusercontent.com/71319075/199654669-a175137f-23e2-4f67-be9d-450b144413c1.PNG)
![Capture6](https://user-images.githubusercontent.com/71319075/199654562-27ec9bb6-b27b-426b-bca1-843be3feb361.PNG)

## Drawbacks
* It's an extractive type chatbot and follows a particular sequence.
* It will show the previous chats it had before you begin a new conversation (if it's hosted or if u haven't re-executed the gradio code).
* It's a primitive system and has a chance to fail/waste time if the user will not input topics related to medical health topic.

## References
* <a href='https://gradio.app/creating_a_chatbot/'>Using Gradio Chatbot</a>
* <a href='https://www.kaggle.com/datasets/aijain/hindi-health-dataset?select=Hindi+Health+Data.txt'>Dataset</a>
* <a href='https://inltk.readthedocs.io/en/latest/api_docs.html'>iNLTK</a>
* <a href='https://www.nltk.org/'>NLTK</a>
* <a href='https://www.nltk.org/api/nltk.tokenize.html'>NLTK Tokenize</a>