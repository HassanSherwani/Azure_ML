# Azure_ML
Building a simple Naive bayes model with Azure ML service

# Aim of study

In this small project, we will build and deploy a machine model to positive or negative reviews from customers(in resturant setting)

# Modules

numpy, pandas, sklearn,azureml.core

# Error control

install the following pip packages on your target virtual environment:

pip install azure <br>
pip install azure-ml-api-sdk <br>

# Limitation to study

We showed  freeze method(pickle) to add custom Python modules. While this is feasible for small modules, it's cumbersome for large modules (especially modules with native DLLs) or a large number of modules. We might need to work over it in future.
