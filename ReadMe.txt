Notes for running the code file.
1. Download the seg_train and seg_test from https://www.kaggle.com/puneet6060/intel-image-classification and store it in a local directory.
2. Provide the path of the datasets in cell 2 of the python code file.
3. If you are using cross validation functions other than validation set approach, which have been presented in the comment section of the code file, kindly uncomment the appropriate scaling commands in cell 12.  
4. Different model architectures have been provided in cell 12, please feel free to try out different models by commenting and uncommenting the lines of code.
5. The model.fit function has the argument callback_lists. Kindly add the suitable callback_lists based on the improvement technique used.   

References:
1. Data loading - https://pythonprogramming.net/loading-custom-data-deep-learning-python-tensorflow-keras/
2. Cross Validation functions - https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.KFold.html
3. Adaptive Learning Rate - https://towardsdatascience.com/learning-rate-schedules-and-adaptive-learning-rate-methods-for-deep-learning-2c8f433990d1
4. Confusion Matrix - https://www.kaggle.com/grfiv4/plot-a-confusion-matrix
