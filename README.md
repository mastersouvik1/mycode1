import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

data=pd.read_csv("/content/sample_data/california_housing_test.csv")
df1=pd.DataFrame(data)



plt.scatter(df1["longitude"], df1["latitude"])


latitude = df1["latitude"]
longitude = df1["longitude"]
plt.plot(longitude, latitude)
plt.savefig("housing data")
plt.show()# mycode1
