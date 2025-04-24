The goal of this project is to build a prototype data science solution that will optimize rides to be claimed earlier and for trip boosting costs to be minimzed. I proposed a model that predicts elasticity for time it takes to claim rides and then use the elasticity to simulate different scenarios of boost cost and claim times in order to select the optimal boost cost, based on a default multi-objective function.

HopSkipDrive/
├── data/
│   └── boost_df.csv
│ 
├── notebooks/
│   ├── eda.ipynb - data exploration, messy
│   └── model.ipynb - cleaned up procedure, includes prediction and optimization models and example simulation
│ 
├── readme.txt - shows file directory
├── writeup.txt - case-study documentation
