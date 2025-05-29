# Tropical Cyclone Impact Forecasting Model
This project uses machine learning to predict the potential housing damage caused by tropical cyclones, using multi-source geospatial and environmental data.
Developed during my research experience at the ISI Foundation in collaboration with the Netherlands Red Cross and the UN OCHA Centre for Humanitarian Data.


# An Overview of the Project
The goal of this project was to improve existing cyclone early-warning systems by developing a globally applicable impact forecasting model. 
The model uses publicly available indicators such as:

- Wind speed
- Topography
- Vulnerability
- Building Material, ...

The machine learning pipeline was built around **XGBoost**, with preprocessing done using geospatial tools and Python libraries.


**Note**: The scripts in this repository reflect my contributions to a collaborative project that adapted the Typhoon impact model originally developed by [510 Global](https://github.com/rodekruis/Typhoon-Impact-based-forecasting-model) for the Philippines. My work focused on extending and generalizing this model to make it applicable on a global scale.

# Repository Structure
notebooks/
|--- new_model_training/        # Main model development notebooks
├── baseline_model/            # Analysis and visualization of dataset which has been compiled by [510 Global](https://github.com/rodekruis/Typhoon-Impact-based-forecasting-model), from their work developing a typhoon impact prediction model in the Philippines.
├── new_model_input/          # Input data for developed model (only my code included)
├── codes_of_article/         # Evaluation and results in the published paper
README.md
requirements.txt

# Key Technologies
Python: `pandas`, `XGBoost`, `scikit-learn`, `Seaborn`  
Jupyter Notebook  
QGIS (geospatial preprocessing)  
Git & GitHub

# My Contributions 
  My Work was done under the supervision of experts at the ISI Foundation.
- Designed and trained the impact prediction model using XGBoost.
- Built and validated the model evaluation pipeline.
- Wrote the core training and analysis notebooks.
- Collaborated on the scientific paper and presentation at EGU 2023.

# Collaborators
This work was part of a joint project between:
- **ISI Foundation** 
- **UN OCHA Data Expert** 
- **Netherlands Red Cross** 


# Results
The model demonstrated high accuracy in predicting cyclone-related housing damage in the Philippines and later was adapted for other countries such as Fiji and Vietnam. These findings contributed to real-world early warning systems.


# Citation
If you use this code or dataset, please cite:

> Kooshki, M. et al., *Towards a Global Impact-based Forecasting Model for Tropical Cyclones*, EGU Journal, 2024.  
> DOI: [10.5194/nhess-24-309-2024](https://nhess.copernicus.org/articles/24/309/2024/)


# License
This repository is licensed under the GNU General Public License v3.0 (GPL-3.0).  
It builds upon work from the [510 Global](510 Global](https://github.com/rodekruis/Typhoon-Impact-based-forecasting-model) and Netherlands Red Cross teams.  
See [LICENSE](./LICENSE) for full terms.

