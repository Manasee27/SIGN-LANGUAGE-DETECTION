# SIGN-LANGUAGE-DETECTION

American Sign Language translation using a chrome extension for Google Meet- 

• Captured video frames from Google Meet are sent to MediaPipe framework to predict hand gestures using image processing.
• Implemented JavaScript solution API to integrate functions of MediaPipe into Chrome extension.
• Adopted Mongo DB database program to store hand sign coordinates in form of arrays and send it to Node JS server, which sends it to chrome extension. These arrays are refreshed every 60 seconds.
• Logistic Regression algorithm is utilized to design an ML model with an accuracy score of 0.956.
