
# Analysing Booking Data for Major Hotel Chain

This project analyzes booking data for a major hotel chain, uncovering key trends, customer behaviors, and factors influencing booking cancellations. The analysis aims to provide actionable insights for business decision-making and to build predictive models for cancellation likelihood.

---

## Project Overview

This repository contains a comprehensive data analysis of hotel booking records. The primary objectives are:

- To explore and visualize booking patterns across different hotel types and time periods.
- To identify factors that contribute to booking cancellations.
- To build and evaluate a predictive model for cancellation prediction.
- To generate business insights that can help optimize revenue, reduce cancellations, and improve customer satisfaction.

---

## Dataset

The dataset includes booking information for a major hotel chain, covering details such as:

- Booking dates and lead times
- Length of stay (weekend and weekday nights)
- Number of adults, children, and babies
- Hotel type (city or resort)
- Customer demographics (country, customer type)
- Booking channel and market segment
- Special requests, deposit type, and cancellation status

**Note:** All personally identifying information has been removed from the dataset to ensure privacy.

---

## Repository Structure

- `booking-analysis.ipynb`: Exploratory data analysis (EDA) notebook with data cleaning, visualization, and key insights.
- `cancellation-prediction.ipynb`: Notebook for building and evaluating a machine learning model to predict booking cancellations.
- `pyproject.toml`, `poetry.lock`: Dependency management files for reproducibility.
- `README.md`: Project documentation.
- `LICENSE`: MIT License.

---

## Getting Started

**Prerequisites**

- Python 3.8+
- Poetry (for dependency management)

**Installation**

1. Clone the repository:
   ```
   git clone https://github.com/PoojaChandrashekara/Analysing-Booking-Data-For-Major-Hotel-Chain.git
   cd Analysing-Booking-Data-For-Major-Hotel-Chain
   ```
2. Install dependencies using Poetry:
   ```
   poetry install
   ```
3. Launch Jupyter Notebook:
   ```
   poetry run jupyter notebook
   ```
4. Open and run the notebooks:
   - `booking-analysis.ipynb`
   - `cancellation-prediction.ipynb`

---

## Analysis Highlights

- **Exploratory Data Analysis:**  
  - Trends in booking volume by month, hotel type, and country of origin.
  - Distribution of stay durations and booking lead times.
  - Cancellation rates across different segments.
  - Visualization of special requests, deposit types, and customer types.

- **Predictive Modeling:**  
  - Feature engineering to select relevant predictors.
  - Model built to predict the likelihood of booking cancellation.
  - Evaluation using accuracy and other relevant metrics.

- **Key Insights:**  
  - Identification of peak booking periods and high-risk segments for cancellations.
  - Recommendations for targeted marketing and operational improvements.

---

## Results

- Approximately 30–35% of bookings are canceled, with higher rates in certain months and customer segments.
- City hotels tend to have higher booking volumes than resort hotels.
- Most guests originate from a handful of countries, with notable seasonal trends.
- Lead time, deposit type, and customer type are strong predictors of cancellation.

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for suggestions, improvements, or bug fixes.

---

## Authors

- Pooja Chandrashekara
- Mahikshit Kurapati

For questions, please use GitHub Issues.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments

- Inspired by open datasets and prior analyses on hotel booking demand.
- Thanks to contributors and the open-source data science community for resources and support.
