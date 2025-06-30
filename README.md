# 🌡️ MinTemperatures: PySpark Daily Minimum Temperature Analysis

This repository contains a PySpark script, **`min_temperatures.py`**, that processes historical weather data to find the minimum daily temperature for each weather station. It demonstrates how to define a schema, filter data, perform aggregations, and convert units using a PySpark DataFrame.

---

## 🚀 Features

- **Schema Definition**  
  Explicitly defines the schema for the input CSV data, ensuring correct data types.

- **Data Ingestion**  
  Reads CSV data into a Spark DataFrame using the defined schema.

- **Data Filtering**  
  Filters the dataset to include only minimum temperature (`TMIN`) records.

- **Aggregation**  
  Groups data by `stationID` and calculates the minimum temperature for each station.

- **Unit Conversion**  
  Converts temperatures from Celsius (original data is assumed to be in Celsius, scaled by 10) to Fahrenheit.

- **Sorting**  
  Sorts the final results by temperature.

- **Result Display**  
  Collects and prints the station ID and its corresponding minimum temperature in Fahrenheit.

---

## 📁 Dataset

The script expects a CSV file named `1800.csv` to be present at the following path:

