# Black-Friday-Feature-Model-Training-Python

## Project Objective and Process 
I worked with the Black Friday dataset, which consisted of a large training dataset (550,068 rows) and a test dataset (250,000 rows), each containing 12 columns. I concatenated both datasets for feature engineering.

I started with the Age column, which was categorical, and applied a mapping function to assign numerical values to each category. Similarly, I transformed the Gender column by encoding Female as 0 and Male as 1. The same approach was applied to other categorical columns such as City_Category and Stay_In_Current_City_Years. For the remaining categorical variables, I used one-hot encoding.

Next, I handled missing values. The Product_Category_1 column had 245,982 missing values, Product_Category_2 had 545,809, and Purchase had 233,599. I used statistical methods to impute the missing values in Product_Category_1 and Product_Category_2. The missing values in Purchase were acceptable, as this column is the target variable and would be naturally split when dividing the dataset into training and test sets for model training.

To explore the data further, I created bar plots to visualize relationships such as Age vs Purchase, Product_Category_1 vs Purchase, Product_Category_2 vs Purchase, and Product_Category_3 vs Purchase. After that, I performed feature scaling and proceeded with model training.
