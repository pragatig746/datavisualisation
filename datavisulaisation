import numpy as np

from matplotlib import pyplot as plt

x =np.arange(5)
y = x
print(y)
plt.title('test plot')
plt.plot(x,y,'o-')

plt.plot(x,np.sin(x))
plt.axis('tight');

x = np.linspace(0,10,30)
y = np.sin(x)
plt.plot(x,y,'o', color='black')

x =np.arange(5)
y = x
plt.plot(x, y+1 , 'g',x, y+0.5 , 'y',x, y , 'r',x, y-0.2 , 'c',x, y-0.4 , 'k',x, y-0.6 , 'm',x, y-0.8 , 'w',x, y-1 , 'b')
plt.show()

import seaborn as sns

data=pd.read_csv("day.csv")

data.head()

data.isna().sum()#for checking if data is null 

data.count()

data.describe()

sns.pairplot(data)
