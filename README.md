# Rossmann Store Sales Forecasting

This repository contains my project work on forecasting sales for Rossmann stores. The project involves data cleaning, exploratory data analysis, feature engineering, and building machine learning models for prediction. A submission file is generated and uploaded to the [Rossmann Store Sales competition](https://www.kaggle.com/competitions/rossmann-store-sales).

## Project Structure

- **data/**: Contains raw data files like `train.csv`, `test.csv`, `store.csv`, and the `sample_submission.csv` format.
- **notebooks/**: Contains the Jupyter Notebook (`rossmann_forecasting.ipynb`) where data processing, modeling, and submission file generation are documented.
- **submission.csv**: The final submission file generated from the notebook.
- **requirements.txt**: List of required Python packages.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/rossmann-store-sales-forecasting.git
    ```
2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use: venv\Scripts\activate
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Open the Jupyter Notebook and run the cells sequentially:
    ```bash
    jupyter notebook notebooks/rossmann_forecasting.ipynb
    ```

## Kaggle Submission

A submission file (`submission.csv`) is generated in the notebook, which can be uploaded to Kaggle for evaluation.

## License

This project is licensed under the MIT License.
