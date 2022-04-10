# FB_Prophet_modeling_on_Sales
Exploration on Rossman's Sales data by using the Facebook's Prophet time series model.

Not like general auto-regressive model, the predicted value in Prophet is according to time factor itself. In this project, we are trying to use Facebook's Prophet Model to fit the sales in Store two in the dataset. To finetune the model, we will try to ignore the sales when the store is closed, and try to increase the flexibility by adjusting the change point prior scale.

Four model's are presented in the notebooks:

1. m:
model with default parameters and data includes sales(0 units) in Saturday and Sunday 
2. m_cp:
model with hyperparameter changepoint_prior_scale adjusted and data includes sales(0 units) in Saturday and Sunday 
3. m_open
model with default parameters and data excludes sales(0 units) in Saturday and Sunday 
4. m_open_cp
model with hyperparameter changepoint_prior_scale adjusted and data excludes sales(0 units) in Saturday and Sunday 

