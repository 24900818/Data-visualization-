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

# Coding and Output

        import matplotlib.pyplot as plt
        x_val = [0,1,2,3,4,5]
        y_val = [0,1,4,9,16,25]
        plt.plot(x_val,y_val)
        plt.show()

  ![image](https://github.com/user-attachments/assets/c85491cd-e8c6-470b-a437-ee06f9fe051e)

           import matplotlib.pyplot as plt
           x = [1,2,3]
           y = [2,4,1]
           plt.plot(x,y)
           plt.xlabel('x-axis')
           plt.ylabel('y-axis')
           plt.title('My first graph')
           plt.show()

![image](https://github.com/user-attachments/assets/4405cd4e-e362-419a-8042-40bf54abdb66)

             import matplotlib.pyplot as plt
             x1 = [1,2,3]
             y1 = [2,5,3]
             plt.plot(x1,y1,label = 'line 1')
             x2 = [1,2,3]
             y2 = [3,1,6]
             plt.plot(x2,y2,label = 'line 2')
             plt.xlabel('x-axis')
             plt.ylabel('y-axis')
             plt.title("Two lines on the same graph")
             plt.legend()
             plt.show()

![image](https://github.com/user-attachments/assets/bbf399bf-68e7-4397-8ff2-40cf9d34ef69)

             import matplotlib.pyplot as plt
             import numpy as np
             x = [1,2,3,4,5]
             y1 = [10,12,14,16,18]
             y2 = [5,7,9,11,13]
             y3 = [2,4,6,8,10]
             plt.fill_between(x,y1,color = 'blue')
             plt.fill_between(x,y2,color = 'orange')

 ![image](https://github.com/user-attachments/assets/0fbf587c-7d58-4d71-96ee-0c8f64508945)

                plt.stackplot(x,y1,y2,y3,labels = ['line1','line2','line3'])
                plt.legend(loc = 'upper left')
                plt.title('Stacked line charts')
                plt.xlabel('x-axis')
                plt.ylabel('y-axis')
                plt.show()

 ![image](https://github.com/user-attachments/assets/e26f7e5c-f789-4b0a-806b-dc4e2333efdf)

              import numpy as np
              import matplotlib.pyplot as plt
              val = [2,4,7,3]
              names = ['A','B','C','D']
              plt.bar(names, val,color = 'purple')
              plt.show()    

 ![image](https://github.com/user-attachments/assets/62216dad-fc48-4383-9a0d-6f0f30050aed)

              import matplotlib.pyplot as plt
              import numpy as np
              ages = [2,6,4,12,13,12,16,18,18,19,26,24,39,34,45,42,54,56,90,56,86,79]
              range = (0,100)
              bins = 10
              plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
              plt.xlabel('age')
              plt.ylabel('no of people')
              plt.title('histogram')
              plt.show()

![image](https://github.com/user-attachments/assets/2044c43b-3cb5-44a5-8323-307e90ed4d5d)

                import matplotlib.pyplot as plt
                import numpy as np
                np.random.seed(0)
                data=np.random.normal(loc=0,scale=1,size=100)
                data

![image](https://github.com/user-attachments/assets/b69810c1-a0fd-4449-b52f-94609721a851)

                  fig,ax=plt.subplots()
                  ax.boxplot(data)
                  ax.set_xlabel("data")
                  ax.set_ylabel("values")
                  ax.set_title("box plot")

![image](https://github.com/user-attachments/assets/ca0398d2-0329-4f39-ab34-b6afafffd513)

                  import matplotlib.pyplot as plt
                  activities=['eat','sleep','work','play']
                  slices=[3,7,8,6]
                  colors=['r','y','g','b']
                  plt.pie(slices,labels = slices,colors=colors,startangle=90,shadow = True,explode = (0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
                  plt.legend()
                  plt.show()

![image](https://github.com/user-attachments/assets/9111e69d-0772-4ca2-a278-16b0bac89d33)

# Result:
                 Thus the program has been executed successfully.
                 
