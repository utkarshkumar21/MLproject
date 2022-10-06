# MLproject
TEMPERATURE FORECAST 
• Objective: Perform an exploratory data analysis and build 
a prediction model for temperature forcast based on the 
CRISP-DM process for the dataset below. The thought 
process and conclusions will be shares throughout this 
notebook.
• Dataset: Bias correction of numerical prediction 
model temperature forecast Data Set from UCI


Table of content
• Import libraries
• Read dataset
• Exploratory data analysis
▪ General information
▪ Missing values
▪ Categorical variables
▪ Numerical variables
• Machine learning model
• Conclusion

1) Import libraries

![Screenshot (26)](https://user-images.githubusercontent.com/114558841/194383496-4da0de83-9e18-477e-ae83-4b819fd7e087.png)
Libraries used numpy,pandas,matplotlib,seaborn,sklearn etc.

2. READING DATASET
![Screenshot (29)](https://user-images.githubusercontent.com/114558841/194384009-21c0810b-4703-4348-841d-93b33d258e5c.png)
▪ OUTPUT
![Screenshot (27)](https://user-images.githubusercontent.com/114558841/194384321-3f6db466-116b-469b-bc93-a7498abf6bd0.png)

3. Exploratory Data Analysis
▪ General information
![Screenshot (28)](https://user-images.githubusercontent.com/114558841/194384827-315ea874-40df-4588-a005-f29fa411e684.png)
 
 No. of dataframes are 7752 rows and 25 columns
 
 ▪ Missing values
 ![Screenshot (32)](https://user-images.githubusercontent.com/114558841/194385144-04dc38c0-1419-40f4-9258-2c7a76542eb2.png)
 
 There are 20 from 25 columns with missing values:
Columns with no missing values = {'LDAPS_Tmax_lapse', 'L
DAPS_PPT2', 'Date', 'station', 'LDAPS_PPT1', 'Present_Tmin', 
'LDAPS_RHmax', 'Next_Tmax', 'LDAPS_CC1', 'LDAPS_Tmi
n_lapse', 'LDAPS_PPT3', 'LDAPS_LH', 'LDAPS_CC4', 'LDAP
S_RHmin', 'LDAPS_CC3', 'Next_Tmin', 'LDAPS_WS', 'Presen
t_Tmax', 'LDAPS_CC2', 'LDAPS_PPT4'}

![Screenshot (31)](https://user-images.githubusercontent.com/114558841/194385910-e8af2eee-5f7c-4531-8f1b-e403ca31f63c.png)

There are 0 from 25 columns with more than 75.0% of missing 
values:
 Columns more than 75.0% of values missing = set()
 
 ![Screenshot (34)](https://user-images.githubusercontent.com/114558841/194386183-92411487-8f0a-44d3-bfdc-ec224b5b58ef.png)

There are 0 from 25 columns with more than 50.0% of missing values:
Columns more than 50.0% of values missing = set()

![Screenshot (36)](https://user-images.githubusercontent.com/114558841/194386340-c22c4a79-320a-4d43-a762-1191700ec0f3.png)
▪ OUTPUT
![Screenshot (38)](https://user-images.githubusercontent.com/114558841/194386465-419764c4-7a85-4511-8d32-bbc527928ccd.png)

![Screenshot (39)](https://user-images.githubusercontent.com/114558841/194386608-480d43b9-97e1-44a8-8645-7ee9b61a84a1.png)
The dataframe has 7588 rows and 25 columns

![Screenshot (42)](https://user-images.githubusercontent.com/114558841/194386730-ef71f10f-8708-407c-8127-d76dec6662c0.png)

▪ OUTPUT
![Screenshot (43)](https://user-images.githubusercontent.com/114558841/194386892-efc315f5-e638-4309-a1e7-1a7d7f2fbf3d.png)

![Screenshot (44)](https://user-images.githubusercontent.com/114558841/194387089-5e4a527c-9483-4fe8-a107-e02f798ef304.png)

OUTPUT: 2.1155830753353975
• The rows with missing values were droped successfully and 2% of the data was lost.

• Categorical variables:

![Screenshot (50)](https://user-images.githubusercontent.com/114558841/194387382-9a801cc2-b92a-4ebe-b2aa-30f8812a1d66.png)

There are 1 from 25 columns with categorical data
 Columns categorical data = ['Date']






