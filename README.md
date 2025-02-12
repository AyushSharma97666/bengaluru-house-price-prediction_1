# Bengaluru House Price Prediction

## Project Overview
This project aims to predict house prices in Bengaluru using Machine Learning techniques. The dataset is sourced from Kaggle, and the model is built using Python, Pandas, Sklearn, and Flask. The project was completed with guidance from the Codebasics YouTube channel.

## Dataset
Dataset used for this project is available on Kaggle:
[Bengaluru House Price Data](https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data)

## Objectives
- Gain hands-on experience with Machine Learning.
- Understand data preprocessing required for model training.
- Build an ML model from scratch.

## Technologies Used
- **Python** for scripting
- **Numpy & Pandas** for data cleaning
- **Matplotlib** for data visualization
- **Scikit-learn** for model building
- **Jupyter Notebook, Visual Studio Code, PyCharm** as IDEs
- **Flask** for creating an HTTP server
- **HTML, CSS, JavaScript** for UI

## Project Structure
```
bengaluru-house-price-prediction/
│── data/                      # Contains raw and processed data
│   ├── Bengaluru_House_Data.csv
│   ├── cleaned_data.csv
│── notebooks/                  # Jupyter Notebooks for exploration & modeling
│   ├── data_exploration.ipynb
│   ├── model_training.ipynb
│── src/                        # Source code
│   ├── app.py                  # Flask API
│   ├── model.py                # ML Model training and prediction
│   ├── preprocess.py           # Data preprocessing functions
│── templates/                   # HTML Templates for UI
│   ├── index.html
│── static/                      # CSS & JavaScript
│── requirements.txt             # Dependencies
│── README.md                    # Project documentation
│── .gitignore                   # Ignore unnecessary files
```

## Installation
### 1. Clone the repository
```bash
git clone https://github.com/your-username/bengaluru-house-price-prediction.git
cd bengaluru-house-price-prediction
```

### 2. Create a virtual environment and activate it
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

## Running the Project
### 1. Data Preprocessing & Model Training
Use Jupyter Notebook to run the `data_exploration.ipynb` and `model_training.ipynb` notebooks for data analysis and model training.

### 2. Run the Flask API
```bash
python src/app.py
```
The Flask server will start, and you can interact with the model using the web UI or API.

## Contributing
Feel free to submit pull requests or report issues.

## License
This project is for educational purposes only.

