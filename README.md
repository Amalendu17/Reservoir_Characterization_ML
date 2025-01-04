# Reservoir Characterization Using Machine Learning

## Overview
Reservoir characterization is a critical process in the oil and gas industry that involves understanding the physical and chemical properties of subsurface reservoirs to optimize exploration and production. Traditionally, this process relies on analyzing seismic data, well logs, and core samples using manual or semi-automated methods. However, with the growing availability of large datasets and advancements in computational power, machine learning (ML) has emerged as a powerful tool to enhance reservoir characterization.

Machine learning enables the integration and analysis of diverse datasets, such as seismic attributes, well logs, and production data, to build accurate reservoir models. These models provide valuable insights into key reservoir properties, including porosity, permeability, fluid saturation, and lithology. By leveraging ML algorithms, geoscientists and engineers can automate tasks, identify hidden patterns, and make predictions with higher accuracy and efficiency. From seismic interpretation to petrophysical property estimation, ML techniques transform reservoir characterization by reducing time, improving precision, and supporting data-driven decision-making.

## Dataset Overview
The dataset used in this project has been made available in this repository. It includes measurements from subsurface reservoirs and consists of the following features:

1. **Gamma Ray (GR):** Measurement of natural radioactivity in the formation.
2. **Resistivity (ILD_log10):** Logarithmic representation of electrical resistivity.
3. **Photoelectric Effect (PE):** Measurement of photoelectric absorption.
4. **Neutron-Density Porosity Difference (DeltaPHI):** Difference between neutron and density porosity values.
5. **Average Neutron-Density Porosity (PHIND):** Combined neutron and density porosity measurement.
6. **Nonmarine/Marine Indicator (NM_M):** Categorical feature indicating depositional environment.
7. **Relative Position (RELPOS):** Relative position within the reservoir.

Each record corresponds to a half-foot depth interval and includes a facies label representing lithology types such as shale, sandstone, or limestone. This dataset provides the foundation for building machine learning models for tasks such as lithology classification, porosity prediction, and reservoir property estimation.

## Project Highlights

1. **Data Preprocessing:**
   - Handling missing values.
   - Normalizing and scaling features for better model performance.

2. **Reservoir Property Analysis:**
   - Calculating porosity for individual wells.
   - Visualizing depth-porosity profiles for better interpretation.

3. **Machine Learning Models:**
   - Classification of lithology using supervised learning techniques.
   - Time-series analysis for production forecasting.

4. **Visualization:**
   - Generating depth-wise porosity plots for each well.
   - Comprehensive data visualizations to aid interpretation.



2. Navigate to the project directory:
   ```bash
   cd Reservoir_Characterization_ML
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter notebook for interactive analysis:
   ```bash
   jupyter notebook notebooks/Reservoir_Characterization.ipynb
   ```

## Results
This project provides insights into subsurface reservoir properties and demonstrates the application of machine learning techniques for efficient and accurate reservoir characterization. Key outputs include:

- Lithology classification with high accuracy.
- Depth-wise porosity profiles for each well.
- Time-series forecasting for production trends.


---
Feel free to contribute to this repository by submitting pull requests or raising issues!

