# Analyse local explanation using SHAP explanation model for UCI bank-marketing dataset
The goal of this project is to determine the utility of the explanation for users. The
explanation derived from local explanation methods can be locally accurate. However, users need
to have a specific instance that they are interested in. The model behaviour is also difficult to
estimate from a local explanation. To help users extract useful explanations, we show a
process for understanding the model from aggregating the explanations to the model and group levels 
with different visualization techniques.

### Dataset
The [UCI bank marketing dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing) consists of 
telemarketing phone calls to sell long-term deposits from May 2008 to November 2010. The data are 
related to the direct marketing campaigns of a Portuguese banking institution. In the campaign, 
a human agent makes phone calls to a list of clients to sell the deposits. If the clients call the 
contact centre for any other reason, they are asked to subscribe to the deposit. Thus, the result 
is a binary unsuccessful (No) or successful (Yes) contact.

### Models and Techniques
Classification model: [XGBoost](https://xgboost.readthedocs.io/en/latest/) \
Explanation model: [SHAP](https://github.com/slundberg/shap) \
Visualization library: [Altair](https://altair-viz.github.io), [iml](https://github.com/interpretable-ml/iml), [Seaborn](https://seaborn.pydata.org)



