# Laptop Price Predictor

A machine learning project that predicts laptop prices based on various specifications using regression models.

## Description

This project uses a regression model to predict the price of laptops based on features such as brand, type, RAM, weight, touchscreen, IPS display, screen size, resolution, CPU, HDD, SSD, GPU, and operating system. The model is trained on a dataset of laptop specifications and prices, and the prediction is made through a Streamlit web application.

## Features

- Interactive web interface for inputting laptop specifications
- Real-time price prediction
- Support for various laptop configurations
- Data visualization and analysis in Jupyter notebook

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/laptop-price-predictor.git
   cd laptop-price-predictor
   ```

2. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Ensure the model files (`pipe.pkl` and `df.pkl`) are in the project directory. If not, run the Jupyter notebook `main.ipynb` to train the model and generate these files.

## Usage

1. Run the Streamlit app:

   ```
   streamlit run app.py
   ```

2. Open your web browser and go to the provided URL (usually `http://localhost:8501`).

3. Select the laptop specifications from the dropdowns and inputs.

4. Click "Predict Price" to get the estimated price.

## Dataset

The dataset `laptop_data.csv` contains information about various laptops including their specifications and prices. It is used for training the regression model.

## Model

The prediction model is built using XGBoost regression. The preprocessing pipeline includes encoding categorical variables and scaling numerical features. The trained model is saved as `pipe.pkl`, and the processed data is saved as `df.pkl`.

## Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## License

This project is licensed under the MIT License.
