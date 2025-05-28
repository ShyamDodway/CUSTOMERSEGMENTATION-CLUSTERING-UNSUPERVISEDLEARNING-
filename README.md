# Time Series Forecasting of Energy Consumption

## Project Overview
This project forecasts daily energy consumption using historical hourly data from the PJM Energy Market. The goal is to predict future energy demand accurately to support better energy planning and grid management.

## Dataset
- Source: [PJM Hourly Energy Consumption](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)
- Data: Hourly electricity usage (megawatts) from 2002 to 2018
- Preprocessing: Resampled to daily averages to reduce noise and capture trends

## Tools & Libraries
- Python 3.x
- Pandas, NumPy
- Statsmodels (SARIMA model)
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab

## Approach
1. **Exploratory Data Analysis**: Visualized trends, seasonality, and patterns
2. **Data Processing**: Converted hourly data to daily means; handled missing data
3. **Modeling**: Built a SARIMA model to capture trend and weekly seasonality
4. **Evaluation**: Forecasted a 30-day horizon and evaluated using MAE and MAPE metrics

## Results
- **Mean Absolute Error (MAE):** _e.g., 503_
- **Mean Absolute Percentage Error (MAPE):** _e.g., 2.6%_
- The model effectively forecasts daily energy demand with good accuracy.

## Business Impact
Accurate forecasting helps energy providers optimize resource allocation, reduce operational costs, and avoid blackouts by anticipating demand.

## How to Run
- Clone the repo:  
  `git clone https://github.com/yourusername/energy-forecasting.git`
- Open the notebook `pjme_energy_forecasting.ipynb` in Jupyter or Google Colab
- Install required packages (if needed):  
  `pip install -r requirements.txt`
- Run cells step-by-step to reproduce the analysis and forecasting

## File Structure
- `pjme_energy_forecasting.ipynb` — Main notebook with full analysis and model  
- `requirements.txt` — List of Python dependencies  
- `README.md` — This documentation

## License
This project is open-source under the MIT License.

---

Feel free to explore the notebook and reach out if you have any questions or suggestions!

---

**[Optional: Add your contact info or LinkedIn]**

---

### Would you like me to help you generate:

- A **requirements.txt** file  
- A brief **presentation slide deck** for interviews  
- A simple **Streamlit app** to demo the forecasting interactively?  

Just let me know!
