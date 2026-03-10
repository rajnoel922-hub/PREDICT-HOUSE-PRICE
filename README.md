# PREDICT-HOUSE-PRICE
[ ]
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import r2_score,root_mean_squared_error
Gemini
This code snippet creates a scatter plot to visually compare the actual prices (from y_test) against the predicted prices (from y_pred).

plt.scatter(y_test,y_pred,color='gold'): This line creates a scatter plot where the x-axis represents the actual prices and the y-axis represents the predicted prices. The points are colored 'gold'.
plt.plot(y_test,y_test,color='silver'): This line plots a diagonal line where actual price equals predicted price. This line serves as a reference; points close to this line indicate good model performance.
plt.xlabel("Actual Prices"): Sets the label for the x-axis.
plt.ylabel("Predicted Prices"): Sets the label for the y-axis.
plt.title("Actual vs Predicted Prices"): Sets the title of the plot.
plt.show(): Displays the generated plot
