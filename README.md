# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
 import matplotlib.pyplot as plt
 x_values=[0,1,2,3,4,5]
 y_values=[0,1,4,9,16,25]
 plt.plot(x_values,y_values)
 plt.show()
```
<img width="768" height="429" alt="image" src="https://github.com/user-attachments/assets/403bf47e-6de2-461f-afe6-816f4af8d592" />
```
import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()
```
<img width="836" height="461" alt="image" src="https://github.com/user-attachments/assets/3b7d5cad-ad6e-4659-b472-c5e75b81a89c" />
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlim(1,8)
plt.ylim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```
<img width="844" height="455" alt="image" src="https://github.com/user-attachments/assets/d1222be1-6be1-41c3-8968-fa50aebdb928" />
```
 years=[2010,2011,2012,2013,2014,2015]
 yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
 plt.plot(years,yield_apples)
```
<img width="845" height="455" alt="Screenshot 2025-10-16 132338" src="https://github.com/user-attachments/assets/6c0f65af-0c78-43f9-8d72-f10941229dbf" />
```
 years=range(2000,2012)
 apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
 oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
 plt.plot(years,apples)
 plt.plot(years,oranges)
 plt.xlabel('year')
 plt.ylabel('Yield(tons per hectare)')
 plt.title("Crop Yield in Kanto")
 plt.legend(['Apples','Orandes']);
```
<img width="815" height="461" alt="image" src="https://github.com/user-attachments/assets/94290fac-5a45-4584-930b-b8c0e2586117" />
```
 plt.figure(figsize=(12,6))
 plt.plot(years,oranges,marker='o')
 plt.title("Yield of Oranges (tons per hectare)");
```
<img width="852" height="449" alt="image" src="https://github.com/user-attachments/assets/0a9da5b6-6906-4113-8235-85d7bbb46f94" />
```
 plt.plot(years, apples, marker='o')
 plt.plot(years, oranges, marker='x')
 plt.xlabel('Year') 
plt.ylabel('Yield (tons per hectare)')
 plt.title("Crop Yields in Kanto") 
plt.legend(['Apples','Oranges'])
```
<img width="846" height="486" alt="image" src="https://github.com/user-attachments/assets/2f1749f1-c697-4a6f-a16c-251a5de125e3" />
```
 import matplotlib.pyplot as plt
 x = [1,2,3,4,5,6,7,8,9,10]
 y = [2,4,5,7,6,8,9,11,12,12]
 plt.scatter(x, y, label= "stars", color="gray", marker="*", s=30)
 plt.xlabel('x axis')
 plt.ylabel('y axis')
 plt. title('My scatter plot!')
 plt.legend()
 plt.show()
```
<img width="815" height="463" alt="image" src="https://github.com/user-attachments/assets/407af056-2eb0-4aa8-b15a-61356c6a27bc" />
```
 plt.scatter(x,y,c='r') 
plt.xlabel('X axis') 
plt.ylabel('Y axis') 
plt.title('Graph in 2D') 
plt.savefig('Test.png')
```
<img width="790" height="454" alt="image" src="https://github.com/user-attachments/assets/45828c99-d94f-4361-8f16-b9d1c9f00123" />
```
 plt.plot(x,y,'g*', linestyle='dashed', linewidth=2, markersize=12)
 plt.xlabel('x axis')
 plt.ylabel('Y axis')
 plt.title('2d Diagram')
```
<img width="817" height="485" alt="image" src="https://github.com/user-attachments/assets/8fb6ca20-8a64-4828-a905-f4417c9ad92a" />
```
 plt.subplot(2,2,1)
 plt.plot(x,y,'r--')
 plt.subplot(2,2,2)
 plt.plot(x,y,'g*-')
 plt.subplot(2,2,3)
 plt.plot(x,y,'bo')
 plt.subplot(2,2,4)
 plt.plot(x,y,'go')
```
<img width="711" height="441" alt="image" src="https://github.com/user-attachments/assets/20eae9de-f7b7-4075-a6aa-f93e13459a7a" />
```
import numpy as np
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
<img width="796" height="436" alt="image" src="https://github.com/user-attachments/assets/3207bc80-0a64-445c-a483-765c1c506a4f" />
```
 import matplotlib.pyplot as plt
 import numpy as np
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```
<img width="702" height="423" alt="image" src="https://github.com/user-attachments/assets/d5b49a18-3946-4dcb-ac09-43984f527625" />
```
 plt.stackplot(x, y1, y2, y3,labels=['Line 1', 'Line 2', 'Line 3'])
 plt.legend(loc='upper left')
 plt.title('Stacked Line Chart')
 plt.xlabel('X-axis')
 plt.ylabel('Y-axis')
 plt.show()
```
<img width="685" height="465" alt="image" src="https://github.com/user-attachments/assets/d449e313-33e2-4e71-8f31-77045d9f031a" />
```
 import numpy as np
 import matplotlib.pyplot as plt
 from scipy.interpolate import make_interp_spline
 x = np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
 y = np.array([2, 4, 5, 7, 8, 8, 9, 10, 11, 12])
 spl = make_interp_spline(x, y)
 x_smooth = np.linspace(x.min(), x.max(), 100)
 y_smooth = spl(x_smooth)
 plt.plot(x, y, 'o', label='data')
 plt.plot(x_smooth, y_smooth, '-', label='spline')
 plt.legend()
 plt.show()
```
<img width="783" height="416" alt="image" src="https://github.com/user-attachments/assets/f4fd9d76-ef36-4729-b7a9-ab7cb29095cc" />
```
x = [2,8,10] 
y = [11,16,9] 
x2 = [3,9,11] 
y2 = [6,15,7] 
plt.bar(x, y, color='r') 
plt.bar(x2, y2, color = 'g') 
plt.title('Bar graph') 
plt.ylabel('Y axis') 
plt.xlabel('x axis')
plt.show()
```
<img width="790" height="454" alt="image" src="https://github.com/user-attachments/assets/3c044a46-8541-45c2-99a1-d264b1296e9e" />
```
 import matplotlib.pyplot as plt
 import numpy as np
 np.random.seed(0)
 data=np.random.normal(loc=0,scale=1,size=100)
 data
 fig, ax=plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box plot')
```
<img width="838" height="494" alt="image" src="https://github.com/user-attachments/assets/d8c906fd-0c45-4a8c-829d-95249051cc26" />
```
 import matplotlib.pyplot as plt
 activities = ['eat', 'sleep', 'work', 'play']
 slices = [3, 7, 8, 6]
 colors = ['r', 'y', 'g', 'b']
 plt.pie(slices, labels = activities, colors=colors, startangle=90, shadow = True)
 plt.legend()
 plt.show()
```
<img width="648" height="388" alt="image" src="https://github.com/user-attachments/assets/0ac859d0-22c9-4007-8563-7527e6fa4ad4" />
```
 labels = 'Python', 'C++', 'Ruby', 'Java'
 sizes = [215, 130, 245, 210]
 colors = ['gold', 'yellowgreen', 'lightcoral', 'lightskyblue'] 
explode = (0, 0.4, 0, 0.5)
 plt.pie(sizes, explode=explode, labels=labels, colors=colors, autopct='%1.1f',shadow=True)
 plt.axis('equal')
 plt.show()
```
<img width="836" height="398" alt="image" src="https://github.com/user-attachments/assets/ad262136-7754-4ad6-8822-d7f788ac42d5" />

# Result:
The above code is excuted successfully 
 
