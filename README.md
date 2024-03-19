# Space Weather Alerts Analysis

## Overview
This project focuses on analyzing space weather alerts data obtained from NOAA (National Oceanic and Atmospheric Administration). The objective is to understand space weather events, detect anomalies, and visualize severity using Python programming language and relevant data analysis libraries.

## Project Structure
- `data/`: Directory containing the space weather alerts data (`alerts.json`).
- `src/`: Directory containing the source code files.
  - `fetch_data.py`: Python script to fetch the space weather alerts data from the NOAA API and save it as `alerts.json`.
  - `analyze_data.py`: Python script to analyze the space weather alerts data, detect anomalies, and visualize severity.
- `README.md`: This file, providing an overview, instructions, and documentation for the project.
- `requirements.txt`: Text file listing the required Python libraries and their versions.

## Setup
1. Clone this repository to your local machine.
2. Install the required Python libraries using pip:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Fetch Data:
   - Run `fetch_data.py` to fetch the space weather alerts data from the NOAA API and save it as `alerts.json`.
   ```
   python src/fetch_data.py
   ```

2. Analyze Data:
   - Run `analyze_data.py` to analyze the space weather alerts data, detect anomalies, and visualize severity.
   ```
   python src/analyze_data.py
   ```

## Detailed Analysis
1. **Data Collection and Preprocessing**:
   - Fetched space weather alerts data from the NOAA API.
   - Preprocessed the data to clean, format, and prepare it for analysis.

2. **Anomaly Detection**:
   - Utilized Z-score to detect anomalies in the NOAA Scale values of space weather alerts.

3. **Severity Detection**:
   - Mapped NOAA Scale values to severity levels to assess the severity of space weather events.

4. **Visualization**:
   - Used Plotly library to visualize anomaly detection results and severity levels over time.

5. **Learnings and Insights**:
   - Identified challenges in data collection, preprocessing, and analysis.
   - Gained insights into the frequency, severity, and impact of space weather events.
   - Explored potential applications of the analysis results for space weather monitoring and prediction.

## Future Enhancements
- Implement advanced anomaly detection algorithms for more accurate results.
- Enhance visualization techniques for better presentation and interpretation of data.
- Incorporate real-time data streaming and automated analysis for timely insights into space weather events.

## Contributors
- [Duane Thuku](https://github.com/DwayneT)

## Acknowledgements
- [NOAA](https://www.noaa.gov/) for providing space weather alerts data.
