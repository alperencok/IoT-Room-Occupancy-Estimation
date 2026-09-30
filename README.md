# IoT Room Occupancy Estimation

An exploratory data analysis and sensor analytics project using environmental telemetry (temperature, light, sound, CO2, and PIR motion) to estimate room occupancy levels.

## Features

- **Data Exploration & Cleaning:** Ingests multi-sensor time-series observations, inspects missing values, and benchmarks imputation strategies.
- **Sensor Visualizations:** Generates distribution plots for CO2, sound sensors comparison, temperature trends, and correlation heatmaps.
- **Occupancy Analysis:** Analyzes the relationship between environmental sensor readings and the number of room occupants.

## Project Structure

- `IoT_Room_Occupancy_Estimation.ipynb`: Main Jupyter Notebook with data processing and visualization steps.
- `Occupancy_Estimation_1_new.csv`: Raw sensor dataset.
- `Occupancy_Estimation_Cleaned.csv`: Cleaned dataset.
- `assets/`: Exported sensor plots and correlation charts.
- `requirements.txt`: Python package requirements.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/alperencok/IoT-Room-Occupancy-Estimation.git
   cd IoT-Room-Occupancy-Estimation
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook IoT_Room_Occupancy_Estimation.ipynb
   ```

## Author

- **alperencok** (https://github.com/alperencok)

## License

This project is licensed under the MIT License.
