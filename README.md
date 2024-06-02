# Software-Developer-Salary-Prediction
Predict software developer salaries using machine learning models through an interactive Streamlit app. Input details like education level, countries, and experience to get instant salary estimates.
# Software Developer Salary Prediction using Machine Learning with Streamlit

## Project Description

Welcome to the Software Developer Salary Prediction project! This repository houses a machine learning application designed to predict software developer salaries based on various factors such as experience, location, education, and more. Leveraging the power of machine learning algorithms and the interactivity of Streamlit, this project aims to provide an easy-to-use tool for estimating potential salaries in the software development field.

### Key Features

- **Interactive UI with Streamlit**: A user-friendly web interface built with Streamlit, allowing users to input their details and receive immediate output salary predictions.
- **Machine Learning Models**: Implementation of various machine learning models, including Linear Regression, Random Forest, Dicision Tree and GridSearchCV, to provide accurate salary predictions.
- **Data Preprocessing**: Robust data preprocessing pipeline to handle missing values, categorical variables, and feature scaling.
- **Exploratory Data Analysis (EDA)**: Detailed EDA to understand the underlying patterns and correlations in the dataset.
- **Model Evaluation**: Comprehensive evaluation of model performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.
- **Deployment**: Ready-to-deploy Streamlit application that can be easily hosted on platforms like Heroku or AWS.

### Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

#### Prerequisites

- Python 3.8+ (Latest)
- Streamlit
- Pandas
- Scikit-learn
- NumPy
- Matplotlib
- Data Set (you may download from Stack Overflow website)

#### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/software-developer-salary-prediction.git
   cd software-developer-salary-prediction
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py or in vs terminal we may use- python -m streamlit run app.py
   ```

### Usage

1. Open your browser and go to `http://localhost:8501`.
2. Input the relevant information such as years of experience, location, education level, etc.
3. Click on the "Predict Salary" button to get the predicted salary.

### Project Structure

- `app.py`: The main Streamlit application script.
- `data/`: Directory containing the dataset used for training and evaluation.
- `models/`: Directory where trained models are saved.
- `notebooks/`: Jupyter notebooks for EDA and model training.
- `requirements.txt`: List of dependencies required to run the project.
- `README.md`: Project overview and setup instructions.

### Contributing

Contributors are welcome! Please read for details on our code of conduct and the process for submitting pull requests.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to explore, use, and improve this project. If you have any questions or suggestions, please open an issue or reach out to us.
mail: mdzeeshanrasheed5@gmail.com

Happy Coding!
