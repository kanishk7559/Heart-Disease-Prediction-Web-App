# Heart-Disease-Prediction

HDP is Machine Learning and Deep Learning based Web Application built using Django that can predict heart diseases. 

Cardiovascular disease is the leading cause of death in the modern society. 
We use the data mining process as a tool for selection and extraction of necessary information which is then put into various machine learning models.

##### The main aim of the project to provide users with an interactive interface using which they can predict if they have heart disease or not.

![Input Form](https://i.ibb.co/23pPDLL/home-page.jpg)
<br>
![result 0](https://i.ibb.co/TcpLF7L/output2.jpg)
<br>
![result 1](https://i.ibb.co/4THpmZY/output1.jpg)
## Algorithms used are:
- K-Nearest Neighbours (KNN) ( Accuracy = 92% )
- Support Vector Machine (SVM) ( Accuracy = 87% )
- Logistic Regression ( Accuracy = 85% )
- Random Forest Classifier ( Accuracy = 84% )
- Artificial Neural Networks ( Accuracy = 84% )


## Features (Input Parameters)

- **age**: age in years
- **sex**: sex (1 = male; 0 = female) 
- **cp**: chest pain type <br>
  * Value 1: typical angina 
  * Value 2: atypical angina
  * Value 3: non-anginal pain 
  * Value 4: asymptomatic
- **trestbps**: resting blood pressure (in mm Hg on admission to the hospital)
- **chol**: serum cholestoral in mg/dl
- **fbs**: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false) 
- **restecg**: resting electrocardiographic results
  * Value 0: normal
  * Value 1: having ST-T wave abnormality 
  * Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- **thalach**: maximum heart rate achieved
- **exang**: exercise induced angina (1 = yes; 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: the slope of the peak exercise ST segment
  * Value 1: upsloping
  * Value 2: flat
  * Value 3: downsloping
- **ca**: number of major vessels (0-3) colored by flourosopy
- **thal**: thalassemia
  * 3 = normal; 
  * 6 = fixed defect; 
  * 7 = reversable defect

## Tech

HDP uses a number of open source projects to work properly:

- [Python](https://www.python.org/) - programming language
- [Tensoflow](https://www.tensorflow.org/) - end-to-end open source platform for machine learning.
- [scikit-learn](https://scikit-learn.org/) - Machine learning library for the Python programming language
- [Jupyter Notebook](https://jupyter.org/) - open-source, interactive web tool for computation
- [Django](https://www.djangoproject.com/) - Python Web framework
- [Bootstrap](https://getbootstrap.com/) - great UI boilerplate for modern web apps
- [Heroku](https://www.heroku.com/) - Deployment

## Installation

Create a virtualenv and install the dependencies.

In macOS and Linux:
```sh
virtualenv env
source test/Scripts/activate
python install -r requirements.txt
```
In Windows:
```cmd
python3 -m venv env
.\env\Scripts\activate
```
To run...
```sh
python manage.py runserver
```
## Dataset 
https://www.kaggle.com/ronitf/heart-disease-uci

## Contributers 
 * [Nidhi Sabu](https://github.com/blurryface-1)
 * [Kanishk Jamgaonkar](https://github.com/kanishk7559)

## Development

Want to contribute? Great!



