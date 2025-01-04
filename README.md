

---

# Global_Temps: Analyzing Global Temperature Trends with AI

Welcome to the **Global Temperatures Project**! This repository aims to analyze and visualize global temperature trends to enhance our understanding of climate change. Leveraging **Llama-2 13B Chat** and machine learning, the project uncovers historical patterns and predicts future trends in global temperatures.

---

## Project Overview

This project provides a detailed analysis of global temperature data, combining data preprocessing, exploratory analysis, visualization, and machine learning modeling. The goal is to understand how global temperatures have evolved over time and anticipate future changes.

---

## Features

- **AI Integration**: Utilizes Llama-2 13B Chat for intelligent insights and interactive analysis.
- **Data Preprocessing**: Cleaning and transforming raw temperature data for accurate analysis.
- **Exploratory Data Analysis (EDA)**: Identifying trends, anomalies, and statistical insights using visualizations.
- **Trend Visualization**: Graphical representation of global temperature trends over decades.
- **Predictive Modeling**: Machine learning models to forecast future temperature changes.

---

## Installation

To run this project, ensure you have Python installed and the required dependencies:

### Required Libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `transformers` (for Llama-2 13B Chat integration)

Install dependencies using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn transformers
```

---

## Usage

### Clone the Repository
```bash
git clone https://github.com/ENKI0311/Global_Temps.git
cd Global_Temps
```

### Run the Notebooks
Execute the Jupyter notebooks in the following order:
1. **`data_preprocessing.ipynb`**: Clean and prepare the dataset.
2. **`exploratory_data_analysis.ipynb`**: Perform initial data exploration.
3. **`trend_visualization.ipynb`**: Visualize historical and current temperature trends.
4. **`predictive_modeling.ipynb`**: Build and evaluate predictive models.

### Google Colab
You can run the notebooks on Google Colab for free GPU/TPU support. Click the button below to open the project on Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ENKI0311/Global_Temps)

---

## Data Source

The temperature data is sourced from [Berkeley Earth](http://berkeleyearth.org/), a reliable provider of global temperature datasets.

---

## Project Structure

```
Global_Temps/
├── data/                           # Raw and cleaned datasets
├── notebooks/                      # Jupyter notebooks for analysis and modeling
│   ├── data_preprocessing.ipynb
│   ├── exploratory_data_analysis.ipynb
│   ├── trend_visualization.ipynb
│   ├── predictive_modeling.ipynb
├── requirements.txt                # List of dependencies
├── LICENSE                         # License file
├── README.md                       # Project documentation
└── results/                        # Output and visualizations
```

---

## Contributing

Contributions are welcome! If you’d like to suggest improvements or add analysis, please:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature-name"`).
4. Push to the branch (`git push origin feature-name`).
5. Submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Acknowledgments

- Special thanks to **Berkeley Earth** for providing the global temperature datasets.
- Gratitude to the developers of **Llama-2 13B Chat** for enabling advanced AI-driven analysis.

---

