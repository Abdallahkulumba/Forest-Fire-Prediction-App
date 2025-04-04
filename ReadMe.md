# Forest Fire Prediction Application

This project is a Flask-based web application that predicts the likelihood of forest fires based on various environmental factors. The application uses a Ridge regression model and a standard scaler for preprocessing the input data.

## Project Structure

## Files and Directories

- `application.py`: The main Flask application file that handles routing and prediction logic.
- `models/`: Directory containing the pre-trained Ridge regression model (`ridge.pkl`) and the standard scaler (`scaler.pkl`).
- `notebooks/`: Contains Jupyter notebooks for exploratory data analysis (EDA) and model training.
- `templates/`: HTML templates for rendering the web pages.
- `requirements.txt`: List of Python dependencies required for the project.

## Setup and Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Abdallahkulumba/My-App.git
    cd Project
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Run the Flask application:
    ```sh
    python application.py
    ```

5. Open your web browser and go to `http://127.0.0.1:5000/` to access the application.

## Usage

- Navigate to the home page to see the input form.
- Enter the environmental factors such as Temperature, RH, Ws, Rain, FFMC, DMC, ISI, Classes, and Region.
- Click the "Predict" button to get the prediction result.

- <meta name="google-site-verification" content="QnDftAhfxESZAIjaCGX__tZ0sI8RPjJ8yFeEfsplmew" />

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements

- This project is based on the dataset and course provided by Krish Naik.
