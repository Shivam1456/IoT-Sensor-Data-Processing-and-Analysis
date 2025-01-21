# IoT Sensor Data Processing

A Python-based solution to process IoT sensor data, clean it, load it into a database, and generate meaningful reports and visualizations.

## Features
- Load and clean IoT sensor data from a CSV file.
- Store data in an SQLite database.
- Normalize, interpolate, and process data for time-series analysis.
- Generate metrics like daily averages, maximums, and sums.
- Visualize data trends and export reports.

## Dependencies
- Python 3.x
- SQLite
- Pandas
- NumPy
- Matplotlib

## Usage
1. Place the IoT sensor data CSV file in the project directory.
2. Update `file_path` and `db_name` variables in the script if necessary.
3. Run the script to:
   - Load, clean, and process data.
   - Save data into a database.
   - Generate plots and export reports.

## File Structure
- **IoT_Sensor_Data.csv**: Input data file.
- **iot_sensor_data.db**: SQLite database file.
- **plots/**: Directory for saved visualizations.
- **metrics_report.csv**: Exported report of calculated metrics.

## SQL Queries
- Calculate total power consumption per site.
- Identify meters with the highest power usage.
- Detect missing timestamps for sensors.

## How to Run
1. Ensure all dependencies are installed.
2. Execute the script in any Python environment:
   ```bash
   python script_name.py
