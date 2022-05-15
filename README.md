# econet-anomaly-detection

## Environment Setup
In order to properly run our Jupyter Notebook code, you must first download the three ipynb files onto your local machine. In this directory, a subdirectory folder must exist called "ECONet" which contains all of the raw ECONet data. This data is too large to be stored on github and must be obtained seperately. At minimum the "train.csv" and "test.csv" files must be present because those are directly used for experimenting and results. Our code is meant to be run and has been tested on Jupyter Notebook exclusively even though other versions of Jupyter exist.

## Experimenting & Results
The three seperate ipynb source files are distinguished by name into three parts. The first part mainly conducts exploratory data analysis but is required in order to conduct necessary preprocessing. The second part is designed for tuning and testing our models and oversampling techniques and is technically optional if all you want are results, but it will explaing the exact models and hyperparameters we used. The third part is strictly for running the models and has space set up for the user to modify the models and hyperparameters before the model runs. Running the results on the full "test.csv" unlabeled data is not included in these three project files and is done elsewhere at the user's discretion. The execution order follows as such:
* ECONet_Anomaly_Part1 (required/preprocessing)
* ECONet_Anomaly_Part2 (optional/tuning/testing)
* ECONet_Anomaly_Part3 (required/evaluation)
A lengthy report has also been written detailing our data and results which can be provided upon request

## Creators
* Mathew Deel
* Sean McKone
* Amanda Richardson
