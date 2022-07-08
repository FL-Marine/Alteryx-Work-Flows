## Matt's mini-project instructions

For example:  Mini-Project for you....
Pretend your boss gave this dataset. 
If you open the file called Question 72. There are 5 columns of data:

Port Name

Date

Month

Vehicle Type

Number of People

And asked you for the following:
1. What is the total number of people from each port?
  
  a. input data tool
  
  b. summarize tool ➡️ group by Port Name ➡️ sum number of people ➡️ add browse tool

  
  ![image](https://user-images.githubusercontent.com/74512335/178007780-11139636-d7c2-415b-a17e-72cb8149c5d0.png)

2. What vehicle type had the most passengers? **Personal Vehicle Passengers**

  a. summarize tool ➡️ group by Vehicle Type ➡️ sum number of people ➡️ sort passengers per vehicle type descending ➡️ sample first N rows ➡️ add browse tool
  
![image](https://user-images.githubusercontent.com/74512335/178008633-a9fc3460-f560-4af5-a33c-9f552423f039.png)

3. What month had the highest average? **December**

 a. summarize tool ➡️ group by Month ➡️ sum Avg number of people ➡️ sort Avg number of people descending ➡️ add browse tool

!![image](https://user-images.githubusercontent.com/74512335/178009401-512dce96-7c92-4c47-8242-379937d9fd5a.png)

4. Create a "pivot table" like structure with:

- Port Name on Rows
- Vehicle Type on Columns
- Passengers as the values

  a. transpose tool grouping data by Port Name, changing column headers to vehicle type and values for new columns is number of people ➡️ summing values
  b. data cleansing tool replacing nulls with 0 (numeric fields) ➡️ ctrl, shift, b for browse tool

## Final workflow

![image](https://user-images.githubusercontent.com/74512335/178040210-986e5629-4734-4299-8930-e6d5e227208f.png)
