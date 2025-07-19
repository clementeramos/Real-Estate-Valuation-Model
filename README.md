# Real-Estate-Valuation-Model
<h2>Description</h2>

- Built a linear regression model to predict housing sales prices based on property valuation data from Cook County's Assesors Office.
- Developed a data preprocessing pipeline, <b>feature_engine_final</b>, by defining helper functions such as a OneHotEncoder HOF, <b>ohe_roof_material</b>, and feature engineering functions, like <b>add_in_expensive_neighborhood</b>, to help determine whether a property is in an expensive residential area as well as encode the roofing material type from a a categorical to a numerical variable. Other HOFs include <b>remove_outliers</b>, <b>add_total_bedroom</b>, and <b>select_columns</b> to facilitate the train/test split to train the model. 
- Analyzed model performance using <b>rmse_interval</b> and residual plots, providing insights into prediction error and fairness in property assessments
- Examined the socioeconomic and ethical impacts of a regressive property tax assessment model, using Cook County as a case study to illustrate how structural biases produce systemic winners and losers.

<h2>Environments Used </h2>

- <b>Jupyter Notebook</b> 
