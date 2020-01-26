
```python
import matplotlib.pyplot as plt 
  
# x axis values 
x = [int(i) for i in input().split()]
# corresponding y axis values 
y = [float(i) for i in input().split()]
  
# plotting the points  
plt.plot(x, y) 
  
# naming the x axis 
plt.xlabel('Input') 
# naming the y axis 
plt.ylabel('Time') 
  
# giving a title to my graph 
plt.title('Time vs Input graph') 
# function to save the plot 
plt.savefig('graph.png')
```
**Input Format**

First line will contain array of n, second line will contain time

**Example input**
```
1 2 3
10 20 40
```
**Generated Graph**


![](https://imgur.com/zhtPlfc.png)