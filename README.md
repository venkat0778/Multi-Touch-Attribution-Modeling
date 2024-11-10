Multi-Touch Attribution Model and Marketing Budget Optimization
Business Objective
Marketing attribution is a vital aspect of understanding how various marketing channels contribute to overall success. This project delves into multi-channel attribution modeling, aiming to quantify the value of advertising campaigns and improve advertising ROI. The goal is to help stakeholders make informed decisions by isolating the impact of each touchpoint on conversions.

Aim
This project aims to build various attribution models to determine the channels that lead to greater customer conversions.

Data Description
The dataset is in CSV format and comprises 586,737 rows and 6 columns. The columns include:

Cookie: Anonymous customer ID
Time: Date and time of the visit
Interaction: Categorical variable indicating the interaction type
Conversion: Binary indicator (0 for not converted, 1 for converted)
Conversion value: Value of the potential conversion event
Channel (target variable): The marketing channel responsible for bringing the customer to the site
Tech Stack
Language: Python
Libraries: NumPy, Matplotlib, Seaborn, Itertools, Gekko, Pandas-Profiling
Approach
Import the required dependencies and libraries.
Import the dataset.
Exploratory Data Analysis (EDA):
Generate an EDA report using the Pandas Profiling Python module.
Building Single Touch Attribution Models:
Last Touch Attribution Model
First Touch Attribution Model
Last Non-Direct Touch Attribution Model
Building Multi-Touch Attribution Models:
Linear Attribution Model
Position-Based (U-Shaped) Attribution Model
Position Decay Attribution Model
Building Probabilistic Attribution Models:
Markov Attribution Model
Shapley Value Model
Results:
Tables: Average of all the models
Graphs: Model visualizations
Build a Budget Optimization Engine.
