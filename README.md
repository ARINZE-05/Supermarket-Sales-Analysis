# Supermarket-Sales-Analysis

## Introduction
Every business owner wants their business to thrive. And every business is as good as the profit it makes which most times defines the success of the business.  So, in the business world, every profitable business will always stay ahead despite the challenges or stiff competition from others. This analysis delves into the financial capability of a supermarket general sales performances, despite making sales, they don't generate profits. Emphasis on its profitability with the aim of understanding challenges faced by this organization and provide relative solutions to it; considering some metrics like customer type and satisfaction, business locations, total sales, quantity and product category.

## Data Description
This dataset was provided by The Data Initiative.It is a supermarket sales data that gives a general overview of the company's sales performance.The dataset includes the following:
- Invoice ID: Sales slip invoice identification number.
- Branch: Branch of supercenters where transactions occured(A, B and C).
- City: Location of supercenters(Yangon, Naypitaw, Mandalay).
- Customer Type: Customers with member card(1) and customers without member card(0).
- Gender: Gender of customers( Male and Female).
- Product Category: General product category(Electronic accessories, Fashion accessories, Food and Beverages, Health and Beauty, Home and 
  Lifestyle, Sports and Travel)
- Unit Price: Per unit cost of product.
- Quantity: Number of products purchased.
- Tax: 5% of customer's purchase.
- Total: Total sales of products including Tax.
- Date: Date of purchase(January 2019 - March 2019).
- Time: Purchase time(10am - 9pm).
- Payment: Payment method used by customers for purchase(Cash, Credit card, Ewallet).
- COGS: Cost Of Goods Sold.
- Gross Margin Percentage: Gross Margin Percentage.
- Gross Income: Gross Income.
- Rating: Customer satisfaction rating with overall shopping experience.

  ## The dataset KPIs/Statistics
- Total Sales: $322,967
- Total Gross Income: $55,672
- Total COGS: $307,587
- Total Quantity: 5,510 Items
- Total Cost Price: $55,672
- Count Of Unique Customers: 1000
- Count Of Product Category: 6
- Count Of City: 3

  ## Methodology
  
  ### Data Collection
  This dataset used for this analysis was provided by The Data Initiative. This is a learning organization that helps educate and train data 
  analysts. This analysis is for educational and learning purpose.

  ### Data Manipulation
  #### Data cleaning and Data formatting
   - The dataset didn’t take much time to clean as the errors were very minimal. Firstly, I turned the dataset into a Table using “Ctrl + T”. 
     From the Table Design ribbon, I chose a favorable Table Style.
   - The Gender column had its values abbreviated. It had “FM” and “M”. Using the Find & Replace Function, I replaced “FM” with Female and 
     “M” with Male.
   - The Customer Type column had numbers 1 and 0. Using Find & Replace Function, I replaced “1” with Members and “0” with Normal.
   - I applied Currency Formatting to some of the numbers that denotes monetary value.
   - I checked for Duplicates and there was none. Took a deep breathe because my data is now clean and ready for analysis.

  ### Tool Used
  The software used for this analysis is Microsoft Excel [Download here](https://www.microsoft.com/en-us/microsoft-365/excel)

  ## Dashboard
  ![](https://github.com/ARINZE-05/Supermarket-Sales-Analysis/blob/main/Dashhboard.PNG)

  ## Data Analysis
  ### Customer Insight
  This research tries to understand customer purchasing pattern and demographics. It ehance product marketing and distribution.
  ![](doc1.PNG)
  ### Insight
  - Mode of payment was highly considered as it influence customer purchasing ability. Ewallet was the most used mode of payment and Credit card was the least used. Showing how digital 
    mode of payment is getting popular among people.  This may interest you to know that to some customers, the use of credit card for shopping isn’t their strongest suit.
  - Gender purchasing affected their sales. Female customers purchased more items than the male customers. Food and Beverages was the highest selling product as it is an essential. The 
    female customers being the biggest patronizer of this commodity and the male customers settled for Electronic and accessories.
  - Member customers and Normal customers made the highest purchased of product like Food and Beverages. We also discovered that Normal customers are more in number than Member customer.
    
  ![](doc4.PNG)
  ### Total Sales
  This seeks to provide detailed analysis on sales within the 3 months period and across various cities.
  ![](https://github.com/ARINZE-05/Supermarket-Sales-Analysis/blob/main/Total%20Sales.PNG)
  ### Insight
  - January was a successful month in terms of sales. Sales were at its peak with $110,754. Then it started dwindling in February selling a total of $92,590 and consistently rising in 
 the month of March selling at $104,243. They had a Gross income of $5,538, $4,629 and $5,212 respectively. Despite huge sales made, their gross income is slightly the same across 
 different months.
  - Naypyitaw is the city with the most sales at $110,569 selling 1,831 unit of products. This implies that they prioritised selling high-priced products than any others and set good 
  pricing control measures. 
  - Yangon is the second city with the most sales at $106,200 selling 1,859 unit of products. This shows high sales volume with adequate customer engagement. Having sold more unit of 
  products than Naypyitaw yet couldn't make more sales clearly shows they sold more low-priced products.
  - Mandalay follows closely to Yangon and being the lowest selling city with $106,198 selling 1,820 unit of products. This indicate consistent customer satisfaction and huge buying 
  strength.
  ### Customer satisfaction
  This analysis indicates how customer interest and satisfaction affect the general sales performance.
      
  
  
  
    
  
    
     


