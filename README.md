AIM
To apply row and column indexing using .loc and .iloc methods in Pandas to filter specific data from a dataset based on given conditions.

Explanation

In this activity, we use Pandas, a Python library for data manipulation, to filter rows and select specific columns from a dataset containing information about bank clients.
We use the .loc method to apply conditional filtering based on column values. Some key filtering operations include:
Selecting clients based on education level and deposit subscription status
Filtering clients based on loans, previous marketing outcomes, and employment status
Extracting specific columns like name and salary (balance) for clients under a certain age

 Algorithm
 
Step 1: Load the dataset using Pandas.  
Step 2:  Inspect the dataset by checking the first few rows and column names.  
Step 3:  Apply filtering conditions using the .loc method:  
   - Select rows where clients with primary education have subscribed to a deposit.  
   - Select rows where clients have not subscribed to a deposit.  
   - Select rows where subscribed clients have a housing or personal loan.  
   - Select rows where secondary-educated clients have not subscribed to a deposit.  
   - Select rows where clients subscribed due to a successful marketing campaign.  
   - Select rows where unemployed clients have not subscribed to a deposit.  
   - Select columns 'age' and 'balance' where age is less than or equal to 30.  
Step 4:  Display the filtered results.  
Step 5:  Save or export the filtered data if needed

Coding and Output
ACTIVITY 1
1.Write a Python program to select the 'name' and 'score' columns from the following DataFrame.
![Screenshot (8)](https://github.com/user-attachments/assets/e0184a33-70f2-4bec-9692-c0ba25bf6ac4)
![Screenshot (9)](https://github.com/user-attachments/assets/e3eb71be-ab0f-4fbe-9a5d-0d21fc346e11)
![Screenshot (11)](https://github.com/user-attachments/assets/d55146b9-79c0-44e8-bf2f-97d15ab1bffd)

2. For the above dataframe, Write a program to select the data who's attempt is greater than 3.
3. ![Screenshot (13)](https://github.com/user-attachments/assets/3e76b320-3416-4615-88d2-a4deaad50052)


3.Write python code for indexing rows and columns based on the following conditions:
Assume we have the following dataframe:
![Screenshot (16)](https://github.com/user-attachments/assets/6d8df21e-f05f-4bb3-94c4-4da75e8f2bf0)
![Screenshot (15)](https://github.com/user-attachments/assets/8d62c18a-3e43-42bb-acfb-d08c72b49656)
a. Select rows where age is greater than 30:
![Screenshot (18)](https://github.com/user-attachments/assets/c85cb004-ab63-4473-8364-73d50ab808d7)
b. Select rows where name contains 'e':
![Screenshot (21)](https://github.com/user-attachments/assets/ec58efee-289a-4afe-a78c-6dc769240fd8)
c. Select rows where gender is 'M' and salary is greater than 65000:
![Screenshot (19)](https://github.com/user-attachments/assets/d4f02cb1-316b-4000-937c-e3e2caeaa09b)
d. Select columns 'name' and 'age'
![Screenshot (23)](https://github.com/user-attachments/assets/18a69580-98f6-47ab-9b06-72b9fae8949a)

ACTIVITY 2
1.a.  select the rows where clients with primary education have subscribed to a deposit?
![Screenshot (26)](https://github.com/user-attachments/assets/bfb156a1-fd52-4673-b75f-44232f93e234)
b.  select the rows where clients who have not subscribed to a deposit?
![Screenshot (28)](https://github.com/user-attachments/assets/8cc42203-95d0-4b99-9d45-05eda418fc36)
c. select the rows where clients who have subscribed to a deposit either have a housing or a personal loan?
![Screenshot (30)](https://github.com/user-attachments/assets/0b06bd72-bd19-4455-870c-50ebeb145030)
d. select the rows where clients with secondary education who have not subscribed to a deposit?
![Screenshot (34)](https://github.com/user-attachments/assets/87f26f76-3ca8-445c-ac31-7b8f3dac6022)
e.select coloumns ‘education’ and ‘balance’ where age is less than or equal to 30. 
![Screenshot (36)](https://github.com/user-attachments/assets/b3de320a-a1d9-4065-a0b4-01756a40f439)
f. select the rows where unemployed clients who have not subscribed to deposit?
![Screenshot (38)](https://github.com/user-attachments/assets/3333e4cb-698b-4e12-a260-90f17f5ea4f1)
g. Select columns 'name' and 'salary' where age is less than or equal to 30:
![Screenshot (41)](https://github.com/user-attachments/assets/aa85b5b3-088e-4128-9e7c-b256c928418a)










