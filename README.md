<div align="center">
  <h3 align="center">Streamlining Renewable Energy Site Selection with ML: Predict the Suitability of Solar Energy Resources</h3>

  <p align="center">
    <strong>A machine learning model that predicts the suitability of solar power plant given geospatial features.</strong>
  </p>
  <p align="center">
    Timothy Yu | tinyau.yu@outlook.com
  </p>
</div>

## Motivation

Energy decision makers and the energy sector are facing challenges in meeting increasing energy demand and stabilizing the energy price from volatility of fossil fuels, while facing trying to reduce greenhouse gas emissions to combat global warming <a href='https://www.iea.org/reports/world-energy-outlook-2019'>[1]</a>. Solar power is a popular and cost-effective clean energy source that being considered as the biggest source of electricity by 2050. However, finding the best site for solar power plants is challenging and requires detailed assessment of various geospatial factors and socio-economic factors. With the advancement of technology and the availability of GIS data, machine learning models can be trained to identify suitable sites for renewable energy sources.

The goal of this project is to apply machine learning techniques to classify whether solar is suitable as the primary energy source for a location.

This can help energy decision makers and energy companies to simplify the complex site selection process, thereby accelerating the transition to clean and sustainable energy sources, ultimately contributing to the fight against climate change and energy crisis.

This project is inspired by the following paper:
Sachit, M.S.; Shafri, H.Z.M.; Abdullah, A.F.; Rafie, A.S.M.; Gibril, M.B.A. Global Spatial Suitability Mapping of Wind and Solar Systems Using an Explainable AI-Based Approach. ISPRS Int. J. Geo-Inf. 2022, 11,422. https://doi.org/10.3390/ijgi11080422

# Project Structure

As can be seen, the project is split into a number of notebooks:

### <u>Data Analysis</u>
**1.1 Power Plants Inventory Data Analysis.ipynb** <br>
*Preliminary analysis of the US operable power plants inventory data set* <br>
**1.2 Geospatial Data Data.ipynb** * <br>
*Preliminary analysis of the Raster data* <br>

### <u>Data Preparation, EDA and Initial Models</u>
**2. Data Preparation, EDA, and Initial Models.ipynb** <br>
*Notebook describing EDA and initial model building process* <br>

### <u>The Modelling Process</u>
**3.1 Logistic Regression.ipynb**<br>
*Building and optimizing logistic regression classifier*<br>
**3.2 Decision Tree.ipynb**<br>
*Building and optimizing decision tree classifier*<br>
**3.3 Random Forest.ipynb**<br>
*Building and optimizing random forest classifier*<br>
**3.4 XGBoost.ipynb** * <br>
*Building and optimizing XGBoost classifier*<br>

**Note:** * denotes that a notebook will run for a long time.