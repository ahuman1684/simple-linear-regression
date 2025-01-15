# Simple Linear Regression Project

This repository contains a simple linear regression analysis performed using Python. The project aims to predict salaries based on years of experience using the given dataset.

## Project Files

- **`simple_linear_regression.ipynb`**: A Jupyter Notebook that contains the implementation of the simple linear regression model.
- **`Extended_Salary_Data.csv`**: The dataset used for the analysis. It contains information on years of experience and corresponding salaries.

## Features

- Exploratory Data Analysis (EDA) to understand the dataset.
- Implementation of a simple linear regression model using Python libraries.
- Visualization of the regression line and data points.
- Model evaluation using metrics such as Mean Squared Error (MSE) and R-squared.

## Technologies Used

- **Python**: Programming language used for analysis.
- **Jupyter Notebook**: Environment for writing and executing code.
- **Libraries**:
  - `pandas`: For data manipulation and analysis.
  - `matplotlib` and `seaborn`: For data visualization.
  - `scikit-learn`: For implementing the linear regression model.

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/simple-linear-regression.git
   ```
2. Navigate to the project directory:
   ```bash
   cd simple-linear-regression
   ```
3. Install the required dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook simple_linear_regression.ipynb
   ```
5. Follow the instructions in the notebook to execute the code and analyze the results.

## Dataset Details

The `Extended_Salary_Data.csv` file contains the following columns:
- **YearsExperience**: Number of years of professional experience.
- **Salary**: Annual salary in dollars.

## Results

- The model successfully predicts salaries based on years of experience.
- Visualization shows a strong positive correlation between the two variables.

## Future Improvements

- Extend the model to include multiple linear regression with additional features.
- Apply feature scaling to optimize model performance.
- Test the model with different datasets to validate its robustness.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
