# Federated-Learning-Analytics
A repository with Python code to facilitate federated learning with the educational analytics datasets OULAD, EdNet, and KDD Cup 2015.

Each dataset folder contains 4 Python Jupyter Notebooks, which allow users to walk through the complete process from downloading the dataset, to feature engineering, to eventually obtaining federated learning results. The four notebooks are structured as follows:
+ 1 - Feature engineering: provides details on how to download the relevant dataset, along with code to engineer features for the classification task.
+ 2 - Central learning: provides the code to perform (regular) central learning, where all data and parameters are shared and there are no local clients.
+ 3 - Local learning: provides the code to perform local learning, where no data or parameters are shared. To simulate this process, data is divided over K hypothetical local clients.
+ 4 - Federated learning: provides the code to perform federated learning. We simulate the process of dividing data over K local clients, before aggregating parameters using federated averaging.

Finally, each dataset folder contains the results from our experiments, which should be replicable using the notebooks we provide.
