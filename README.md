# Steel-price-prediction
In this project, we will be analyzing the “daily_offers.xlsx” dataset that contains information about steel items offered to customers
The dataset contains 14 columns with 181673 rows of data. Each row represents an item, and has an offered/selling price of that item.

The main objective of this project is to build regression models to predict the price of an item. To achieve this, we will first perform data cleaning, feature engineering, and exploratory data analysis (EDA). We will then split the data into training and testing sets in the ratio of 90:10 and build regression models to predict the selling price of an item. Finally, we will evaluate the best model using the metric r2 score on the testing set.

Column descriptions
Table- daily_offers
id:A unique identifier for each steel item.<br>
item_date: The date on which the steel item was added to the dataset.<br>
quantity tons: The quantity of steel item in tons.<br>
customer: The id of the customer who ordered the steel item.<br>
country: The country id where the steel item is delivered.<br>
status: The current status of the steel item.<br>
"Won" indicate that a sale has been successfully completed or a procurement order has been approved.<br>
"Draft" indicate that a proposal or order is still being worked on and has not yet been finalized.<br>
"To be approved" indicate that a proposal or order has been submitted for approval, but a final decision has not yet been made.<br>
"Lost" could mean that the order did not go through or was not successful for some reason.<br>
item type: The type of steel item.<br>
"W" stands for "wide-flange" W-section steel beam<br>
"S" stands for "standard" S-section steel beam<br>
application: The purpose for which the steel item is used.<br>
thickness: The thickness of the steel item.<br>
width: The width of the steel item.<br>
material_ref: The reference number for the material used in the steel item.<br>
product_ref: The reference number for the steel item.<br>
delivery date: The expected delivery date of the steel item.<br>
selling_price: The offered/selling price of the steel item.<br>
