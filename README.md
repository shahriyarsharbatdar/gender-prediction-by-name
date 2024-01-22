
# gender-prediction-by-name

# Project Title: Name Analysis

## Overview:
This project uses Python and popular libraries like pandas, numpy, matplotlib, seaborn, and Faker to generate a synthetic dataset of names. It then extracts relevant information such as first name, last name, gender, and country using the `names_dataset` library. The extracted data is visualized through a pie chart showcasing the distribution of names across different countries.

## Installation:
To run this project, ensure you have Python installed. Install the required libraries using the following commands:
```bash
pip install names-dataset
pip install Faker
```

## Usage:
1. Clone the repository:
```bash
git clone https://github.com/your-username/name-analysis.git
cd name-analysis
```

2. Run the Jupyter Notebook or Python script:
```bash
# If using Jupyter Notebook
jupyter notebook name_analysis.ipynb

# If using Python script
python name_analysis.py
```

3. Explore the generated synthetic dataset, extracted name parts, gender, and country information in the generated DataFrame.

## Description:
- The script generates a synthetic dataset of 100 names using the Faker library.
- It defines functions to extract name parts (first name and last name) and determine gender and country based on the first name using the `names_dataset` library.
- The DataFrame is enriched with extracted information, including gender and country.
- The gender is converted to numerical values (0 for Male, 1 for Female) for better analysis.
- The country distribution is visualized using a pie chart.

## Files:
- `name_analysis.ipynb` or `name_analysis.py`: Main script or Jupyter Notebook containing the project code.
- `README.md`: Documentation for the project.

## Dependencies:
- names-dataset
- Faker
- pandas
- numpy
- matplotlib
- seaborn

## Contribution:
Contributions are welcome! Feel free to open issues or pull requests.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
 e3c099f70464cd9644bd2ae7e3b6c5b18400eeda