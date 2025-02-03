# Solar Energy Forecasting Using Machine Learning

## Overview
This project presents a **machine learning-based model** for **short-term photovoltaic (PV) energy forecasting**, developed as part of my **Bachelor's Thesis in Industrial Technologies Engineering**. The goal was to improve energy generation predictability, reducing uncertainty and enhancing renewable energy integration into power grids.

## Background
Solar energy is a crucial component in the global shift toward sustainable power. However, its **intermittency** and **dependency on weather conditions** make accurate forecasting essential. This project leverages **artificial neural networks (ANNs) and satellite weather data** to predict solar power generation at **15-minute intervals**.

## Data Sources
- **PVOutput Dataset:** Historical solar power generation data from a PV plant in **Barcelona, Spain** (2015-2018).
- **SARAH2 Satellite Data:** Meteorological inputs (solar radiation, cloud coverage, temperature, wind speed).

## Technical Approach
- **Neural Networks**: Developed deep learning models to predict energy output.
- **Feature Engineering**: Structured satellite data into grid-like inputs, leveraging **Convolutional Neural Networks (CNNs)** to detect spatial patterns.
- **Error Reduction**: Improved prediction accuracy compared to previous state-of-the-art models.
- **Python & Jupyter Notebooks**: Implemented using **TensorFlow, NumPy, Pandas, and Matplotlib**.

## Key Results
- The model significantly improved short-term prediction accuracy, reducing **Mean Absolute Error (MAE) by 15%** compared to baseline models.
- The use of CNNs for structured meteorological data representation led to **better pattern recognition in solar energy generation**.

## Repository Contents
- `Solar_Energy_Forecasting.ipynb`: Full implementation of the neural network model.
- `Solar_Power_Forecasting.pdf`: Bachelor's Thesis detailing methodology and results.

## Potential Impact
This work provides a **scalable and adaptable framework** for improving PV energy forecasting, which is crucial for:
- **Grid Stability**: Reducing uncertainty in electricity markets.
- **Investment Decisions**: Helping renewable energy providers optimize plant efficiency.
- **Sustainability Goals**: Accelerating the transition to cleaner energy sources.

## Author
- **Ricardo Modrego**
- **Master's Graduate, Georgia Institute of Technology**
- [LinkedIn](https://www.linkedin.com/in/rmodrego/)

---
## License
This project is licensed under the **MIT License** - see the `LICENSE` file for details.
