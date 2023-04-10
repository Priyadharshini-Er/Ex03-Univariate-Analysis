# Ex03-Univariate-Analysis
# Aim:
To detect the Univariate Analysis by using default functions.
 
# Algorithm:
1.Import pandas(),numpy()and seaborn() for a required detection.

2.use the head()

3.The information and is null function.

Use the describe function. 5.Figure the boxplot.

6.plot the countrplot,Displot,Histoplot.

7.Print the program.

# Program:
```
import pandas as pd
import numpy as np
import seaborn as sns

data=pd.read_csv('SuperStore.csv')
data

data.head()

data.info()

data.describe()

data.isnull().sum()

data.dtypes

data['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=data)

sns.countplot(x='Postal Code',data=data)

sns.distplot(data["Postal Code"])

sns.histplot(x='Postal Code',data=data)
```
# OUTPUT
# READ FILE
![image](https://user-images.githubusercontent.com/119558093/230889056-52406964-c6c5-491d-b00b-655199c2aa25.png)
# HEAD
![image](https://user-images.githubusercontent.com/119558093/230889101-5f2d6f46-c7c4-4482-bbba-02f17a00d9bd.png)

# INFO
![image](https://user-images.githubusercontent.com/119558093/230889152-c35a94d2-63ee-4bcf-9269-d2e76cc5c67d.png)

# DESCRIBE
![image](https://user-images.githubusercontent.com/119558093/230889199-27337f09-5723-4b41-bdda-c590f6ea3dee.png)

# NULL
![image](https://user-images.githubusercontent.com/119558093/230889238-bf7b5f40-b1f0-4385-9b3c-5fd511e4de53.png)

# DTYPE
![image](https://user-images.githubusercontent.com/119558093/230889285-a6df567d-a2e1-4290-9104-feffb08ab01b.png)
# COUNT
![image](https://user-images.githubusercontent.com/119558093/230889359-ef879b12-2e95-4bf9-9894-ed88183e86af.png)

# BOXPLOT 
![image](https://user-images.githubusercontent.com/119558093/230889394-0652ccc2-2ea7-4e0f-a2e6-9e6e77c8b2a6.png)

# COUNTERPLOT
![image](https://user-images.githubusercontent.com/119558093/230889483-2443906a-2164-4e96-9421-70775e4a6534.png)

# DISPLOT
![image](https://user-images.githubusercontent.com/119558093/230889516-0ff4d6b3-c371-4c04-8334-1353e92ee3fb.png)

# HISPLOT
![image](https://user-images.githubusercontent.com/119558093/230889550-fd7f53e4-7cc1-46b2-8eb8-51eb8a662b80.png)
# RESULT
Thus the univariate analysed by using default functions


