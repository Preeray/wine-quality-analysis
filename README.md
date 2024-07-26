# Wine Quality Analysis

This project analyzes a wine quality dataset to understand the factors affecting wine quality. The analysis involves data visualization, statistical analysis, and data preprocessing for machine learning tasks. For the purpose of this project i have converted the output to a binary output where each wine is either good quality(a score of 7 or higher)or not(a score below 7). 

## Dataset

The dataset used in this project is the Wine Quality dataset, which contains various physicochemical tests performed on wine samples along with quality ratings given by experts. The dataset is available in a CSV file named `winequality-red.csv`.

## Project Structure

The project consists of the following main steps:

1. **Data Loading and Initial Exploration**
   - Load the dataset using pandas.
   - Display the first few rows of the dataset.
   - Check the shape of the dataset.

2. **Data Visualization**
   - Use seaborn and matplotlib to visualize missing values and correlations.
   - Plot histograms to understand the distribution of each feature.
   - Compare each attribute with the `quality` rating using scatter plots.

3. **Analysis of Specific Questions**
   - Investigate whether sweeter wines receive better ratings.
   - Determine which level of acidity receives the highest average rating.
   - Analyze the quantity of wines produced according to quality ratings.

4. **Data Preprocessing for Machine Learning**
   - Convert the quality ratings into binary classification for machine learning tasks.
   - Implement feature selection and regression tasks.

5. **Model Training and Evaluation**
   - Train machine learning models to predict wine quality.
   - Evaluate the accuracy of the models.

## Key Findings

- The correlation heatmap reveals the relationships between different physicochemical properties and wine quality.
- Wines with a slight more acidity tend to have better ratings.
- There is close competition between sweet and less sweet wines regarding their quality ratings.
- The distribution of wine quality ratings shows the number of wines produced in each quality category.

## Screenshot

Below is a screenshot of the accuracy achieved by the machine learning model:

![Model Accuracy](![accuracy](https://github.com/user-attachments/assets/0e4ac53f-502f-451b-b564-15aba4218922)
)

## Usage

To run the analysis, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/wine_quality_analysis.git

2. Navigate to the project directory:
   ```sh
   cd wine-quality-analysis

3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
4. Run jupyter Notebook or google colab:
   ```sh
   jupyter notebook wine_quality_analysis.ipynb

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib

## Contributing
Contributions are most welcome! Please feel free to submit a pull request or open an issue to discuss improvements or bugs.
   
