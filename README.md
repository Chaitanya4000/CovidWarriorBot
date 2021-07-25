# CovidWarriorBot
This bot is developed for cg2021 hackathon.

# Problem Statement
The world is currently affected by Covid-19. Doctors are trying their best to serve the patients, still virus has affected a lot of people.
People are waiting into long queues for getting the Covid-19 reports, and it is taking around 48 hours to get the reports of test.
Can RPA along with AI speedup this process?
Can people get their primary Covid-19 reports within minutes? So that if detected positive, further treatment can be started ASAP…

# Solution Approach
1. Patients can provide their details, symptoms and X-Ray of lungs through application that is build using UiPath Apps.
2. As soon as patient submits the details, ‘Covid Warrior Bot (RPA bot)’ gets triggered.
3. Bot fetches all details provided by patient in UiPath Apps and pass X-Ray image to ‘Convolutional Neural Network’ model that is deployed in UiPath AI Center.
4. On basis of image of X-Ray, AI model predicts if respective patient is Covid positive or negative and pass prediction to RPA bot.
5. RPA bot after receiving the prediction, fetches the details of active cases from government website and enters all details in Salesforce application.
6. Patient can view their reports using Augmented Reality based mobile application.

# Technical Details
1. UiPath Apps used to build application
2. Python used to build and train AI center model
3. UiPath AI Center used to deploy AI model
4. Bot used ML Skill activity in studio to use AI model
5. UiPath Data Service used to store data of patients
6. UiPath Studio to develop the bot
7. UiPath Robot to run the bot
8. Python script using twilio to call patients
9. Salesforce CRM to store data of patients.
10. Unity Hub to build AR application.

