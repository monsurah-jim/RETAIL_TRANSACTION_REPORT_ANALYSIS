# RETAIL_TRANSACTION_REPORT_ANALYSIS

# AIMS AND OBJECTIVES
1. Customer Engagement: Encourage customer interaction and engagement during the transaction

2. Market Presence:Ehance the store's presence and reputation

3. Customer Satisifaction: Ensure customers have a postive and satisifactory experience

4. Inventory Management: Maintain accurate inventory records and optimized stock levels

5. Payment Security: Ensure secure and reliable payment transaction


# DATA SOURCE
It was and uncleaned data gotten from kaggle with missing columns.

# Data Cleaning and Preparation
I had to clean the data with excel and power query, fill in the columns, create additional row and save it as csv file, before importing it into My sql and also i had to update and replace the $ sign in the order amount column.

# BREIF EXPLANATION OF THE COLUMNS
It contained 11 columns and also 75605 rows and they include 
Transaction date: Is the date upon which any financial dealing occurs.

Month: The month which  any financial dealing happened.

Transaction Hour: Time of the day which the financial dealing occured.

Location State: The state which the fiancial dealing happened.

Location City: City where the dealing haopened.

Reward Memeber: List of memebers that will be eligble to receive rewards.

Reward Number: The numbers assigned to each reward that is meant for the memebers.

Number of Items: The number of items meant for the members.

coupon Flag:The flag used whether the members are eligble.

Discount Amount: The discount given the members.

Order Amount:The order made by each members.


# RESULT OF THE ANALYSIS
## The table after the $ sign has been replaced
<img width="741" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/bfd062f8-2e05-4267-84d6-acc2488f018d">

# 1) What is the month with highest transaction made?
## The 10th month which is october has the highest transaction record of 11626
<img width="467" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/85c00ef2-dfe5-4952-a52c-8de4a36c4fc1">

# 2) What is the hightest transaction made in the month of june?
## The highest transaction made in june was 5691
<img width="368" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/4b74d345-c0c4-4268-9ef4-a64d534dd948">

# 3) What is the total order amount in the month of january and which make the highest order between january and december?
## The total order amount in january was 5837
<img width="405" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/6ff0bbae-add3-487d-838d-fd9db1c823fc">

## The total order amount in Decmeber is 6044 which makes December to have the highest  order amount
<img width="434" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/1105579f-22e9-4ff8-b76b-016da218c25a">

# 4) What is the lowest sales made in the month of november and was there an increase in december compare to november
## The sales made in novemeber is 5744
<img width="441" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/f83ada90-18ec-4f6c-8f57-d8f968d9d317"> 

## while the sales made in december is 6044 and also there is an icrease in sale in december comared to november an icrease of 300 sales
<img width="390" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/f158aae5-60ad-41ee-913a-1a275a4e8bc6">

# 5) What is the total discount given?
## The totla discount given is  '6250.909999999741'
<img width="394" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/66c27f03-98be-40b7-85ab-fb4ae274f20d">

# 6) What is the total order amount?
## The total order amount is '9656774.130000066'
<img width="374" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/924fc83d-1dd6-4405-8182-5b449c14c072">

# 7) What is the average sales made in a month?
## The average sales made in the month of june is '126.7673572307152'
<img width="480" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/c4757513-2444-4d2e-8acf-593a447b9e9b">

# 8) What is the lowest discount given compared to order discount.
##  The lowest discount given is zero while the order discount is 100
<img width="380" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/665efc4d-d29a-454d-8a0c-c948d4aa9cba">

# 9) What is the state with highest sales?
## Mississipiis the state that has the highest sales of '392277.50000000006'
<img width="383" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/7ab47474-414c-488a-89fc-9ab77c0b7d72">

# 10) What is the total sales of each state made in florida?
## The following state in Florida with their total sales'Miami' is '671208.6600000005','Sarasota'is '105090.92000000023','Pensacola' is '243321.47000000006','Daytona Beach'is '111504.60999999997' and 'Homestead'is '36124.439999999966'
<img width="501" alt="image" src="https://github.com/monsurah-jim/RETAIL_TRANSACTION_REPORT_ANALYSIS/assets/148765480/fa53abdb-3652-490e-8a18-0c38adb99c42">

















