## HealthifyUp
Medical problems always need a solution regardless of the era we live in. Having an automated system saves time that is required to do the complete diagnosis of the patient and based on the suggestions provided by the system we can only get the patient diagnosed for those diseases that are required.


## What it does
This web-app predicts the whether the person has diabetes, heart disease, liver disease, kidney disease, back pain, or tuberculosis from the given inputs using the machine learning algorithm.

## How it was built

#### Front End
- Frontend is built only using **HTML**. 
- Styling is done using inline HTML styling and **Javascript**.

#### Back end
- Backend is built using machine learning algorithms in **Python** and hosting it using **Flask** and **Heroku**.
- Logistic Regression algorithms from **sklearn** library was used for training and testing of the model.
- **Matplotlib**, **pandas** and **numpy** were used for training the model.

#### How it works
- First the user enters the information and submits the form.
- Then the data is sent to the respective trained model.
- Then is it passed through the trained model and it send the output accordingly.
- Then according to the output given by the model, the result is shown to the user. 
