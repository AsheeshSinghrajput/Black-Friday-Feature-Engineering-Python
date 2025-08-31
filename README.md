# Black-Friday-Feature-Model-Training-Python

## Project Objective and Process 
I worked with the Black Friday dataset, which consisted of a large training dataset (550,068 rows) and a test dataset (250,000 rows), each containing 12 columns. I concatenated both datasets for feature engineering.

I started with the Age column, which was categorical, and applied a mapping function to assign numerical values to each category. Similarly, I transformed the Gender column by encoding Female as 0 and Male as 1. The same approach was applied to other categorical columns such as City_Category and Stay_In_Current_City_Years. For the remaining categorical variables, I used one-hot encoding.

Next, I handled missing values. The Product_Category_1 column had 245,982 missing values, Product_Category_2 had 545,809, and Purchase had 233,599. I used statistical methods to impute the missing values in Product_Category_1 and Product_Category_2. The missing values in Purchase were acceptable, as this column is the target variable and would be naturally split when dividing the dataset into training and test sets for model training.

To explore the data further, I created bar plots to visualize relationships such as Age vs Purchase, Product_Category_1 vs Purchase, Product_Category_2 vs Purchase, and Product_Category_3 vs Purchase. After that, I performed feature scaling and proceeded with model training.

## Dataset used

-<a href="https://github.com/AsheeshSinghrajput/Black-Friday-Feature-Engineering-Python/blob/main/train.csv">Dataset</a>

-<a href="https://github.com/AsheeshSinghrajput/Black-Friday-Feature-Engineering-Python/blob/main/test.csv">Dataset</a>

## Python Code

-<a href="https://github.com/AsheeshSinghrajput/Zomato-Python-EDA/blob/main/Zomato%20Exploratory%20Data%20Analysis.ipynb"> Jupyter Notebook</a>

## Work Samples

<img width="1920" height="1080" alt="Screenshot (149)" src="https://github.com/user-attachments/assets/47fc74c9-19ad-4acc-986a-4d117426eb99" />

<img width="1920" height="1080" alt="Screenshot (150)" src="https://github.com/user-attachments/assets/86dcb8fa-fa0c-47e1-bbf8-e1d40e8ac52c" />

<img width="1920" height="1080" alt="Screenshot (151)" src="https://github.com/user-attachments/assets/382983c2-90b9-43e7-96c7-4f6820ec73e0" />

<img width="1920" height="1080" alt="Screenshot (152)" src="https://github.com/user-attachments/assets/06ec88a6-23e6-41c1-89a0-48dc41db402a" />

<img width="1920" height="1080" alt="Screenshot (153)" src="https://github.com/user-attachments/assets/f2f62a08-d7b5-40f4-a5ee-eeaefabb427a" />
