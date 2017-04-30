# Machine Learning Project Blueprint

This repository is an attempt at creating a common project structure for machine learning projects. The purpose is to make it easier for others to rapidly consume and understand your project and its results and to determine if it can be useful for their own project.



The structure contains the following:

* checkpoints: storage location for the weights of trained models.


* data: store data used to train/test the models you've built.
* logs: store various logs such as training results or any debugging/log information.
* models: source code of various models that have been tested against the problem you are trying to tackle.
* utils: utility functions that might be used within your models or when you convert your raw data into data that can be fed to the model.
* generate.py: convert raw data from the data folder into data expected by your models.
* train.py: load your data, setup your model(s) and train these model(s) against the provided data.

