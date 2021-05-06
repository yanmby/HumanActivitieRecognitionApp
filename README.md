# HumanActivitieRecognitionApp
There is an Android App that recognize human activities usign deep learning models in real time.

The recognition of human activities basically consists of identifying and classifying the movement patterns present in human beings when performing a specific task or activity, this is done using inertial sensors, which are capable of detecting changes in movement of people.

A previously trained classification model was used (Valkov, V. 2017), based on a type of recurrent neural networks, large short-term memory networks (LSTM).

This model classifies 6 different activities (sitting, standing, walking, climbing stairs, descending stairs, and jogging).

The model has an accuracy close to 97%

In the first place, the model was exported in the format indicated by TensorFlow (.pb). For this, a process called "Freeze the model" is carried out in which all its data is unified, eliminating unnecessary files and metadata

Through Android Studio the application was developed using the Java programming language and TensorFlow tools

The application consists of 3 “activities”, which are: MainActivity, TensorFlowclassifier and about.

It was possible to recognize and classify in the mobile application with high precision 3 activities (Standing 100%, sitting 100% and walking 93%).

The precision obtained in the application is close to the theoretical precision of the model (97%).

A larger database would positively influence the performance of the classifier.

Using TensorFlow it is possible to implement deep and machine learning models on mobile devices in a practical and simple way, with good performance

