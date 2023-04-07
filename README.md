# Ex03-Univariate-Analysis

AIM:

To read the given data and perform the univariate analysis with different types of plots.

THEORY:

Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

ALGORITHM:

Step 1:

Read the given data.
Step 2:

Get the information about the data.
Step 3:

Remove the null values from the data.
Step 4:

Mention the datatypes from the data.
Step 5:

Count the values from the data.
Step 6:

Do plots like boxplots,countplot,distribution plot,histogram plot.

PROGRAM:
```
#Program developed by :VAISHALI BALAMURUGAN
#Register number : 212222230164

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
OUTPUT:
![image](https://user-images.githubusercontent.com/119390134/230626704-1573b1e3-8f8d-47e5-ab45-4208f4211e7b.png)
![image](https://user-images.githubusercontent.com/119390134/230627027-02d429f9-3c00-49f9-9eb8-dca9c481f77b.png)
![image](https://user-images.githubusercontent.com/119390134/230627153-22132de4-0e2f-4ad4-9484-223b0590d999.png)
![image](https://user-images.githubusercontent.com/119390134/230627214-40011838-83a5-4bea-91ae-5a574d4cae58.png)
![image](https://user-images.githubusercontent.com/119390134/230627276-56f3518d-8a4d-40e5-8618-1aac44908600.png)
![image](https://user-images.githubusercontent.com/119390134/230627349-0f1aba96-4c37-4ef4-b47a-ac612040483f.png)
![image](https://user-images.githubusercontent.com/119390134/230627424-0327f8a5-0d5a-4605-b1fe-41240e1ac4fc.png)
![image](https://user-images.githubusercontent.com/119390134/230627518-3d4ef0ca-3e1e-49fe-8fee-f753b01eb7ae.png)
![image](https://user-images.githubusercontent.com/119390134/230627599-88cf718d-bacf-4dcf-92ad-8f6d154f1fb5.png)
![image](https://user-images.githubusercontent.com/119390134/230627682-8ef2d707-fdc7-41fe-b8ff-4ea83d2396d0.png)
![image](https://user-images.githubusercontent.com/119390134/230627784-e4ed982b-cc49-41e3-8cc6-2faa4327ddf5.png)
![image](https://user-images.githubusercontent.com/119390134/230627847-5e66a618-53c2-480a-84d6-92bc7028e2df.png)
![image](https://user-images.githubusercontent.com/119390134/230627904-9bcb9a33-a653-43c5-bbb1-896a68266b68.png)
![image](https://user-images.githubusercontent.com/119390134/230628044-faae7237-202b-484a-a121-32ffe6970367.png)
![image](https://user-images.githubusercontent.com/119390134/230628106-22dd2df5-8f43-4703-a6a7-5da78c047015.png)
![image](https://user-images.githubusercontent.com/119390134/230628183-eb0851d8-2ad1-41b8-aea3-e04e5ef7061b.png)
![image](https://user-images.githubusercontent.com/119390134/230628287-bf9e8cd4-d868-4d6a-91bc-688b4908a936.png)
![image](https://user-images.githubusercontent.com/119390134/230628354-93262686-f0aa-42de-bb2c-606f4c6038f4.png)
![image](https://user-images.githubusercontent.com/119390134/230628396-6d81c668-4333-41ca-b77a-fe425e005999.png)
![image](https://user-images.githubusercontent.com/119390134/230628448-34ff1d4f-b4fa-4b7d-b345-1fbc07ca9a32.png)
![image](https://user-images.githubusercontent.com/119390134/230628621-3fbfeabc-5ae0-4d3e-9d5e-3799f43a4e5a.png)
![image](https://user-images.githubusercontent.com/119390134/230628669-a38c65b3-a1ba-4074-b91d-a0353a2ed31b.png)
![image](https://user-images.githubusercontent.com/119390134/230628728-cebdc076-4127-4891-aaa1-2bfcd8248efe.png)
![image](https://user-images.githubusercontent.com/119390134/230628784-1f041966-154b-43d2-8f78-6b2f3c90a359.png)
![image](https://user-images.githubusercontent.com/119390134/230628826-20f85682-df16-47f1-8b9e-dc2ea55efad1.png)
![image](https://user-images.githubusercontent.com/119390134/230628868-ae9626ac-b7ed-4bfd-9b22-edb7334a6848.png)
![image](https://user-images.githubusercontent.com/119390134/230628922-217d89a9-ec14-43d2-b83d-dbf3549cd449.png)

RESULT:

Thus we have read the given data and performed the univariate analysis with different types of plots.
