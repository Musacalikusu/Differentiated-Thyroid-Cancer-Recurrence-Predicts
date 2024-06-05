
# Differentiated Thyroid Cancer Recurrence Prediction

## Project Overview

This project utilizes the Differentiated Thyroid Cancer Recurrence dataset from Kaggle to predict the recurrence of thyroid cancer. The primary goal is to analyze the dataset, build predictive models, and evaluate their performance in predicting cancer recurrence.

## Dataset

The dataset can be found [here](https://www.kaggle.com/datasets/alsaniipe/differentiated-thyroid-cancer-recurrence-dataset/data). It contains information on patients with differentiated thyroid cancer, including various clinical features and whether the cancer recurred.

### Features

- `age`: Age of the patient
- `gender`: Gender of the patient
- `tumor_size`: Size of the tumor
- `T_stage`: Tumor stage
- `N_stage`: Lymph node involvement
- `M_stage`: Metastasis
- `extrathyroidal_extension`: Whether there is extrathyroidal extension
- `multifocality`: Whether the cancer is multifocal
- `histology`: Histological type of the tumor
- `risk_level`: Risk level of the patient
- `recurrence`: Whether the cancer recurred

### Target Variable

- `recurrence`: A binary variable indicating if the cancer recurred (1) or not (0).

## Project Structure

- `data/`: Contains the dataset files.
- `notebooks/`: Jupyter notebooks with data analysis, visualization, and model building.
- `src/`: Source code for data preprocessing, feature engineering, model training, and evaluation.
- `models/`: Saved models.
- `reports/`: Generated analysis and model evaluation reports.
- `README.md`: Project overview and instructions.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/thyroid-cancer-recurrence.git
   cd thyroid-cancer-recurrence
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Preprocess the data:
   ```bash
   python src/preprocess_data.py
   ```

2. Train the model:
   ```bash
   python src/train_model.py
   ```

3. Evaluate the model:
   ```bash
   python src/evaluate_model.py
   ```

4. Jupyter notebooks are provided in the `notebooks/` directory for interactive analysis and visualization.

## Results

The project includes various machine learning models to predict thyroid cancer recurrence. Performance metrics such as accuracy, precision, recall, and F1-score are used to evaluate the models. Detailed results and analysis can be found in the `reports/` directory.

## Contributing

Contributions are welcome! Please create a new branch for each feature or bugfix and submit a pull request for review.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements

- The dataset is provided by Alsan Iipe on Kaggle.
- Inspiration for this project comes from various machine learning and healthcare analytics research.
