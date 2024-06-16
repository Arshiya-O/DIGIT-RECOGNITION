# DIGIT-RECOGNITION
simple digit recognizer using machine learning (CNN and tkinter GUI)
# MNIST Digit Classifier
This is a Tkinter GUI application that uses a pre-trained TensorFlow model to classify MNIST digits.
## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/your_repository.git
    cd your_repository
    ```
2. Create a virtual environment and activate it (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
## Running the Application
1. Ensure that you have the `mnist.h5` model file in the `ml` directory.
2. Run the application:
    ```bash
    python gui/app.py
    ```
    3. Use the GUI to load an image and predict the digit.

## The application is designed to load grayscale images of digits and predict the digit using the pre-trained MNIST model.

