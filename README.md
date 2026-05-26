# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
~~~
import seaborn as sns
import pandas as pd

Read the CSV File:

df=pd.read_csv("iris.csv")
df.head()

Join Plot:


sns.jointplot(x="petal_length", y="petal_width", data=df, kind="hex")

Pair PLot:


sns.pairplot(data=df, vars=["sepal_length","sepal_width"], hue="species")

Dist Plot:


sns.displot(df["petal_length"], kde=True)

Count Plot:


sns.countplot(y="species", data=df)

Box Plot:

sns.boxplot(x="species", y="petal_length", data=df)

Bar Plot:


sns.barplot(x="species", y="petal_length", data=df)

Violin Plot


sns.violinplot(x="species", y="petal_length", data=df)
~~~

<img width="773" height="808" alt="image" src="https://github.com/user-attachments/assets/31872a1c-8b99-434e-87a7-a87a0d91d98f" />

<img width="787" height="626" alt="image" src="https://github.com/user-attachments/assets/f4555935-b616-47c7-8423-b1ba9486f7e7" />


<img width="673" height="687" alt="image" src="https://github.com/user-attachments/assets/9f00ca9e-dec5-4b8b-96fa-72f636bf720a" />

<img width="851" height="577" alt="image" src="https://github.com/user-attachments/assets/7eb1eaf7-3bde-4771-a4f1-4823b69216a7" />

<img width="811" height="614" alt="image" src="https://github.com/user-attachments/assets/d72d1447-81c4-4bfc-945d-a823adff78c5" />

<img width="824" height="604" alt="image" src="https://github.com/user-attachments/assets/46f739e6-dd6c-4c5b-89d6-c754eef5cc44" />

<img width="757" height="605" alt="image" src="https://github.com/user-attachments/assets/3c2e1eb9-1ef1-465c-b82c-fa5246caafe3" />


# Result:
successfully get Perform Data Visualization using seaborn python library for the given datas
