# Objective:

The objective is to clean the dataset by dealing with incorrect, missing, duplicate and inconsistent values using python pandas.

# Data cleaning:

Data cleaning is the process of removing inconsistent and wrongly formatted data. This can be achieved by manually dealing with these values or by automating the process.

Having a clean dataset will boost the overall productivity by making better decisions and hypothesis relating to a data set.

# About the dataset:

The data set that we are using is Automobile which can be downloaded from the link:
https://www.kaggle.com/toramky/automobile-dataset

This data set has 26 different columns. These consists of three types of entities:
1.	Specifications of the automobile.
2.	Insurance risk rating. The range is between-3 (pretty safe) to +3 (risky).
3.	Normalised losses. The range is between 65 to 256. This entity represents average loss per car per year.

# Steps taken to clean the dataset:

By counting the frequency of occurrence of each value we observe that values are inconsistent. Dealing with these inconsistent values by removing white spaces and replacing some of the values.

### Checking all values in make column:

![](Images/make.png)
•	Removing all white spaces using strip command.
•	Replacing vol00112ov to volvo.
•	Replacing Nissan to nissan.
•	Replacing Peugot to peugot.


### Checking all the values in fuel-type:

 ![](Images/fuel%20type.png)
•	Removing all white spaces using strip command.
•	Replacing Gas to gas.
•	Replacing Diesel to diesel.


### Checking all the values in aspiration column:

 
 ![](Images/aspiration.png)
•	Removing all white spaces using the strip command.
•	Replacing turrrrbo to turbo.
•	Replacing Std to std.

### Checking all the values in number of doors column:

 
 ![](Images/number%20of%20doors.png)

•	Removing all white spaces using strip command.
•	Replacing fourR to four.
•	Replacing fourR to four.

### Checking all the values in body style column:

 
![](Images/body%20styles.png)
•	Removing all white spaces using strip command.
•	Replacing Sedan to sedan.
•	Replacing Wagon to wagon.

### Checking all the values in drive wheels column:

 
![](Images/drive%20wheels.png)
•	Removing all white spaces using strip command.
•	Replacing Fwd to fwd.

### Checking all the values in engine location column:

 ![](Images/engine%20location.png)
•	Removing all white spaces using strip command.
•	Replacing Front to front.
•	Replacing FRONT to front.
•	Replacing REAR to rear.
•	Replacing Rear to rear.

### Checking all the values in fuel system column:
 
![](Images/fuel%20system.png)
•	Removing all white spaces using strip command.
•	Replacing Mpfi to mpfi.

### Checking the number of nulls in all the columns:


 ![](Images/null%20values.png)
•	Replacing all the numerical null values with mean values.
•	Replacing all the categorical null values with suitable values in the column.


### Checking all the values in price column:
 ![](Images/price.png)
•	Replacing 0.000000 with mean value.

### Checking all the values in symbolling column:
 
![](Images/symboling.png)
•	Replacing the value 4 which is out of range with 3.

### Checking normalized losses column to verify if the values are between 65 and 256:
![](Images/normalized%20losses.png)

 
•	Replacing the values that are out of range with the mean values in the same column.

### Checking if all the values are in appropriate range:
![](Images/checking%20range.png)

 

### Generating csv file:
•	Finally generating a new csv file with clean data.

# Conclusion:

The dataset was cleaned by replacing all the missing numerical data with mean values and missing categorical data with suitable values. The inconsistent values were replaced by suitable values making the dataset consistent. The out of range values was also replaced by mean values.

# How to run python code:

1.	Download anaconda navigator from the link: https://www.anaconda.com/products/individual
2.	Launch jupyter notebook.
![](Images/anaconda%20navigator.png)


 
3.	Download Automobile.ipynb file and automobile.csv file. Both the files should be present in the same folder. 
![](Images/folder%20layout.png)

4.	Open Automobile.ipynb file using jupyter notebook.
5.	Run to generate new csv file with clean data.
![](Images/run.png)
 

# Contact me:
| Contact Method | Links  |
| --- | --- |
| Email | justinmathew.cta@gmail.com |
| LinkedIn | www.linkedin.com/in/thejustinmathew |




 
