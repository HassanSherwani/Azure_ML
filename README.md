# Azure_ML

Build and Deploy a Machine Learning Model(Naive Bayes in our example) with Azure ML Service

# Aim of study

In this small project, we will build and deploy a machine model to predict positive or negative reviews from customers(in resturant setting).<br>
There are three key steps to follow;

1-Initializing Azure ML Environment<br>
2-Training and Testing Model <br>
3-Registering and Serving the Model<br>

# Modules

numpy, pandas, sklearn,azureml.core

# Error control

install the following pip packages on your target virtual environment:

pip install azure <br>
pip install azure-ml-api-sdk <br>

# Limitation to study

We showed  freeze method(pickle) to add custom Python modules. While this is feasible for small modules, it's cumbersome for large modules (especially modules with native DLLs) or a large number of modules. We might need to work over it in future.
