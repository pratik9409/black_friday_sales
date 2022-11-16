# Black_Friday_Sales_Analysis

This dataset comprises of sales transactions captured at a retail store. It’s a classic dataset to explore and expand your feature engineering skills and day to day understanding from multiple shopping experiences. This is a regression problem. The dataset has 550,069 rows and 12 columns.


### Data Overview
Dataset has 537577 rows (transactions) and 12 columns (features) as described below:

User_ID: Unique ID of the user. There are a total of 5891 users in the dataset.
Product_ID: Unique ID of the product. There are a total of 3623 products in the dataset.
Gender: indicates the gender of the person making the transaction.
Age: indicates the age group of the person making the transaction.
Occupation: shows the occupation of the user, already labeled with numbers 0 to 20.
City_Category: User's living city category. Cities are categorized into 3 different categories 'A', 'B' and 'C'.
Stay_In_Current_City_Years: Indicates how long the users has lived in this city.
Marital_Status: is 0 if the user is not married and 1 otherwise.
Product_Category_1 to _3: Category of the product. All 3 are already labaled with numbers.
Purchase: Purchase amount.


## Analysis

You can see the products purchased by male and female are almost similar. 
Note: Female = 0 & Male = 1

![product_category1](https://user-images.githubusercontent.com/67755812/202199623-d09b7060-bdef-440e-b3a9-ad7f4aa70854.png)


![product_category_2](https://user-images.githubusercontent.com/67755812/202199650-645cd5f1-92c9-493b-8898-1808842e2562.png)


![product_category_3](https://user-images.githubusercontent.com/67755812/202199669-a90a37e8-3dff-4ef9-b7a9-7df72505969a.png)


We can observe that purchase amount is repeating for many customers.This may be because on Black Friday many are buying discounted products in large numbers and kind of follows a Gaussian Distribution.

![purchase_dist](https://user-images.githubusercontent.com/67755812/202197957-8e296750-0a58-46e4-b6f5-4721164d2e78.png)


Occupation has at least 20 different values. Since we do not known to each occupation each number corresponds, is difficult to make any analysis. Furthermore, it seems we have no alternative but to use since there is no way to reduce this number.

![occupation_purchase](https://user-images.githubusercontent.com/67755812/202198191-66408fb2-8547-4a18-9071-ef038d4abc89.png)


Age 26-35 Age group makes the most no of purchases in the age group
![age](https://user-images.githubusercontent.com/67755812/202198320-408db96e-9dee-4e55-9b18-f066280599be.png)










