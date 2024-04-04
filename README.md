# Wine Quality Prediction Using Machine Learning

This project aims to predict the quality of wine using machine learning techniques. The dataset used in this project is sourced from the UCI Machine Learning Repository. It includes the chemical properties of both 'red' and 'white' wines, along with their quality ratings ranging from 0 to 10. By training machine learning models on this dataset, we aim to understand the distribution and relationships between the chemical properties and the quality of wine.

## Dataset Information

The wine quality dataset used in this project can be found at the UCI Machine Learning Repository:
- [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)

The dataset contains two separate datasets for red and white wines, each with the following columns:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target variable, ranging from 0 to 10)

## Repository Structure

- `data/`: Folder containing the raw dataset files.
- `notebooks/`: Folder containing Jupyter notebooks for data exploration, preprocessing, model training, and evaluation.
- `models/`: Folder containing saved trained machine learning models.
- `README.md`: This file providing an overview of the project.

## Getting Started

To get started with this project, you can clone this repository and explore the Jupyter notebooks in the `notebooks/` directory. These notebooks provide step-by-step instructions for data exploration, preprocessing, model training, and evaluation.

## Dependencies

This project requires Python 3 and the following libraries:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

You can install the dependencies using pip:

`pip install numpy pandas matplotlib seaborn scikit-learn`


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
