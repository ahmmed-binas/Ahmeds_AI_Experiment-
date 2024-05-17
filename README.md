# Ahmeds_AI_Experiment



I am making an application which will test show the training of models (drawings) which will be able to be learned by the neural networks and identified  later by artificial intelligence.
setting up the application:
first make sure the getpip.py file is in your folder that you are working with to download and setup pip.
then go to your directory and download pip if you dont have ...
```
python -m venv venv
```
![done](https://github.com/ahmmed-binas/doodle-prediction-application/assets/110778968/889f917a-5d8b-44bb-b6a1-14eb06fe8530)
Then Activate The Virtual Environment
```
.\venv\Scripts\activate

```
After That Download all the needed libraries' 
![train](https://github.com/ahmmed-binas/doodle-prediction-application/assets/110778968/5379972d-5537-47d6-a0df-651d317295ee)

```
pip install pillow opencv-python numpy scikit-learn tk

```
Project Overview:

The Drawing Classifier is a Python application that allows users to draw simple shapes on a canvas and classify them into predefined classes. The application utilizes machine learning algorithms to train and classify drawings into different categories.

Features:

User-Friendly Interface: The application provides an intuitive graphical user interface (GUI) built using the Tkinter library in Python.
Canvas Drawing: Users can draw simple shapes (e.g., circles, squares) on the canvas using a mouse or touch input.
Multi-Class Classification: The drawings can be classified into multiple classes defined by the user.
Model Training and Prediction: The application supports training machine learning models (e.g., Linear SVM, K-Nearest Neighbors, Decision Trees) using the drawn shapes and provides real-time prediction of the drawn shapes.
Model Persistence: Trained models can be saved to disk for future use, allowing users to reload and reuse previously trained models.
Customizable: Users can customize the project name, class names, and other settings to suit their requirements.
Installation:

Clone the repository from GitHub: Drawing Classifier Repository
Install the required dependencies using pip:

```
pip install pillow opencv-python scikit-learn
```

Usage:
Run the DrawingClassifier.py script.
Provide a project name and define the classes.
Draw shapes on the canvas and classify them using the provided buttons.
Train the model using the training data.
Save the trained model for future use.
Predict the class of drawn shapes using the trained model.
Optionally, load a previously saved model.
Contributing:

Contributions to the project are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request on the GitHub repository.

License:

This project is licensed under the MIT License. See the LICENSE file for more details.

Author:

Ahmed Binas

Contact:

For inquiries or support, please contact binasroxz@gmail.com.

Acknowledgements:

Thanks to the creators and maintainers of the libraries used in this project: Tkinter, Pillow, OpenCV, scikit-learn.
Special thanks to [Name], [Name], and [Name] for their contributions and feedback.
Finally Run your code !!!!

```
python start.py

```

