# TaskForVisualizationPython
Training case: visualize health insurance data with Python
# Case data
There is a table «insurance.csv». It is taken from an open source - kaggle.com.  
The table contains the patient data columns:    
+ age;  
+ sex;  
+ bmi — body mass index;  
+ children — number of children;  
+ smoker — smoking or not;  
+ region — region of residence;  
+ charges — amount of insurance payment.
# Case
I am an analyst at a medical insurance company. My team is preparing a large study about the firm’s clients.  
I agreed with the manager that i would study the data and bring useful schedules for the next meeting.
# What i did:
1. Imported Libraries
2. Configured the chart display throughout the document.
3. Downloaded insurance.csv dataset in Jupyter Notebook.
4. Applied a function that showed me the names of the columns in the table.
5. Visualized variables using the pairplot() function.  
I set the arguments of the function so that the values of one of the swing variables differ in color.
6. Selected 1 most interesting for business graphic. Using the scatterplot() function I built a graph,  
set axis and header. Configured their size and location. Wrote down the function plt.show() to run all functions.
7. Сonstructed a point diagram with a regression line and confidence interval, using the lmplot(). Customized axle names, title and legend.
8. Selected several categorical variables and plotted for each group within the variable.
9. Exported all graphics with the savefig() function.
