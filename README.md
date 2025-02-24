# Shopping Trends Analysis

This project performs Exploratory Data Analysis (EDA) on shopping trends data to uncover insights about customer behavior, product popularity, and seasonal trends.

## Features

The EDA process includes:

1. **Data Overview**
   - Basic information about the dataset.
   - Checking for missing values and duplicates.

2. **Descriptive Statistics**
   - Summary statistics for numerical and categorical features.

3. **Data Visualization**
   - Distribution plots for numerical features.
   - Count plots for categorical variables.

4. **Correlation Analysis**
   - Heatmap to identify relationships between numerical variables.

5. **Customer Segmentation**
   - K-Means clustering to group customers based on age and purchase amount.

## Project Structure

```
.
├── data
│   └── shopping_trends.csv (your dataset)
├── eda_shopping_trends.ipynb (EDA notebook)
├── README.md (this file)
```

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
3. Activate the virtual environment:
   - Windows:
     ```bash
     venv\Scripts\activate
     ```
   - Mac/Linux:
     ```bash
     source venv/bin/activate
     ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Place your dataset (e.g., `shopping_trends_updated.csv`) in the `data` folder.
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook AICTE-Shopping Trends Analysis.ipynb
   ```
3. Run the cells sequentially to perform the analysis.

## Dependencies

The project uses the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install them via:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Results

- **Insights:** Summary of trends, correlations, and clusters uncovered during the analysis.

## Contributing

Feel free to fork the project, create feature branches, and submit pull requests. Let's build this together!

## License

This project is licensed under the MIT License.

---

Happy analyzing! 📊
