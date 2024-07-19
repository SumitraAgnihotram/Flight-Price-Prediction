FLIGHT PRICE PREDICTION SYSTEM 

The "Flight Price Predicton system" presents a comprehensive solution to address the challenges
associated with budgeting. In the dynamic and highly volatile airline industry, predicting accurate
ticket prices is crucial for both travelers and service providers. This project leverages machine
learning algorithms to analyze historical flight data, and other relevant factors to forecast future
ticket prices.
The implementation encompasses a user-friendly interface (a webapp, i.e front-end) that enables users to input travel details,
route popularity, and seasonal trends, and receive reliable predictions, empowering them to make
informed decisions regarding their air travel expenses.
The development process involves rigorous testing and validation to guarantee the accuracy and
reliability of the predictions.


FILE DESCRIPTION:
1. Static folder- it contains the background image for the single page web app and the css file, you can edit this according to your styling preferences.
2. templates- it contains the home.html file, the structure for the webapp.
3. Data_Train.xlsx and Test_set.xlsx- these files contain the historical data. Divided for the purpose of training and testing the ML model.
4. app.py- python file where the flask application is developed, routed and deployed. The ML model that is trained is imported by this file.
5. flight_price.ipynb- this file contains code to preprocess the data, load it into a model, train and test the model using various algorithms for better results.
6. flightmod.pkl- the ML model saved by the python pickle library for easy export to the web app.


HOW TO RUN THE APPLICATION:

Prerequisites:- System having python installed. 
                Install all necessary libraries using the command: pip install <library_name>
                Any IDE supporting python to edit the python code.
                Recommended to donload all the files and folders under one directory.

Open a terminal, 
Navigate to the directory containing all the above files and folders,
enter the following command: python app.py
this will show the address and port where the Flask app is running,
click on it or copy and paste it in a browser search bar and you can see your output.

