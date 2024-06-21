# Linear-Regression-Health-Costs-Calculator

This project involves predicting healthcare costs using a regression algorithm. The dataset contains various attributes of individuals along with their healthcare expenses.

## Project Overview

In this project, we will:

1. **Data Preparation:**
   - Import the dataset which includes information such as age, sex, BMI, region, smoker status, and healthcare expenses.
   - Convert categorical data (like sex, smoker status, and region) into numerical format for model training.

2. **Data Splitting:**
   - Divide the dataset into training (80%) and testing (20%) sets.
   - Separate the "expenses" column from both datasets to create `train_labels` and `test_labels`.

3. **Model Building:**
   - Create a regression model using TensorFlow and Keras.
   - Train the model using the training dataset (`train_dataset`).

4. **Model Evaluation:**
   - Evaluate the trained model using the unseen testing dataset (`test_dataset`).
   - The evaluation metric to focus on is Mean Absolute Error (MAE), which should be less than $3500 for the model to pass the challenge.

5. **Prediction and Visualization:**
   - Use the trained model to predict healthcare expenses on the test dataset.
   - Plot the predicted expenses against the actual expenses to visualize the model's performance.

## Libraries Used

- TensorFlow (for building and training the neural network)
- Pandas (for data manipulation)
- Matplotlib (for data visualization)

## Files Included

- `health_costs_regression.ipynb`: Jupyter notebook containing the Python code for the entire project.
- `insurance.csv`: Dataset used for training and testing.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Open the Jupyter Notebook:**
   - Launch Jupyter Notebook and open `health_costs_regression.ipynb`.
   - Run each cell sequentially to execute the code and see the results.

3. **Project Validation:**
   - After training the model, ensure that the Mean Absolute Error (MAE) on the test set is below 3500.
   - The final cell in the notebook will automatically test the model's performance and provide feedback.

4. **Explore Further:**
   - Feel free to experiment with different model architectures, hyperparameters, or preprocessing techniques to improve the model's accuracy.

## Dependencies

Ensure you have the necessary libraries installed:
```bash
pip install -r requirements.txt
```

## Notes

- This project focuses on predicting healthcare costs using a basic linear regression model. For more complex scenarios, consider exploring advanced machine learning algorithms.
- For any issues or improvements, feel free to contribute or reach out to the project maintainers.
