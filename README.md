# Crop & Fertilizer Recommendation System

## Overview
This project includes two systems:
1. **Crop Recommendation System** - Suggests the best crop to grow based on soil and environmental factors.
2. **Fertilizer Recommendation System** - Provides optimal fertilizer recommendations based on soil nutrients and crop requirements.

## Features
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA) with visualizations
- Feature distribution analysis
- Crop classification and fertilizer suggestions
- Machine learning models for predictions (if applicable)

## Datasets
### Crop Recommendation Dataset (`Crop_recommendation.csv`)
- **N, P, K:** Soil nutrient levels (Nitrogen, Phosphorus, and Potassium)
- **Temperature & Humidity:** Climatic conditions
- **pH & Rainfall:** Soil acidity and rainfall levels
- **Label:** The recommended crop

### Fertilizer Recommendation Dataset (`Fertilizer_recommendation.csv`)
- **Soil Type & Crop Type**: Defines the type of soil and crop
- **N, P, K Levels**: Current nutrient levels in the soil
- **Fertilizer Recommendation**: Suggested fertilizer for the given soil condition

## Installation
To run this project, install the required dependencies:
```bash
pip install pandas numpy matplotlib seaborn
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/your-username/agriculture-recommendation.git
cd agriculture-recommendation
```
2. Run the Jupyter Notebooks:
```bash
jupyter notebook crop.ipynb
jupyter notebook fertilizer.ipynb
```

## Visualizations
The project includes:
- Histograms to analyze feature distributions
- Scatter plots for feature relationships
- Insights into the datasets

## Contribution
Feel free to fork this repository, create a new branch, and submit a pull request with improvements or additional features.

## License
This project is open-source and available under the [MIT License](LICENSE).

