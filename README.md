# engine_rul_prediction

Predict remaining useful life of aircraft engines using NASA's C-MAPSS dataset and a random forest regressor

Goal

prevent unexpected engine failures by forecasting when maintenance is needed

dataset

-NASA Turbofan Engine Degredation Simulation (C-MAPSS)

-26 sensor signals + operational cycles

-100 engines, each with multiple cycles

Approach

-Removed constant sensors (no variance)

-Split 80 engines for training, 20 for testing

-Trained a Random forest regressor(100 trees)

Result

-Mean Absolute Error: 36.5 cycles

-This means the model predicts remaining engine life off by about 36 cycles on average-which is enough to schedule maitenance weeks in advance

Files

-engine_rul_prediction.ipynb-complete python code

tools

-python, pandas, scikit-learn, matplotlib, Jupyter Notebook
