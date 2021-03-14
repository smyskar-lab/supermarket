This project analyzes sales data from the supermarket for the Q1-2019 and provides some insights on improvements for increasing revenues (and eventually gross margins) and discusses various ways to improve customer ratings for their stores.

This project has data file avaialble in the repository (supermarket_sales.csv) and jupyter notebook (supermarket_data blog,ipynb) which explains the process used to analyze the data and provide some recommendation on improving revenues of the supermarket. 

I have used pandas, numpy and matplotlib python packages for all the analysis in the jupyter notebook.

supermarket_sales.csv:- This data is the transaction data from supermarket stores in the 3 cities for the months of Jan-2019, Feb-2019 and Mar-2019. It has 17 variables and 1000                           oberservations. Description of the Variables is given below (it was taken from the Kaggle website).

                            Invoice id: Computer generated sales slip invoice identification number

                            Branch: Branch of supercenter (3 branches are available identified by A, B and C).

                            City: Location of supercenters

                            Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.

                            Gender: Gender type of customer

                            Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and                                                 lifestyle, Sports and travel

                            Unit price: Price of each product in $

                            Quantity: Number of products purchased by customer

                            Tax: 5% tax fee for customer buying

                            Total: Total price including tax

                            Date: Date of purchase (Record available from January 2019 to March 2019)

                            Time: Purchase time (10am to 9pm)

                            Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)

                            COGS: Cost of goods sold

                            Gross margin percentage: Gross margin percentage

                            Gross income: Gross income

                            Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)
                            
                            
Summary:- 

1) We see that customers who are members are relatively as not-satisfied with the services of supermarkets as compared to non-members (this interpretation is made based on that the average rating of members is lower than non-members). 
2) Total gross income is highest for the Naypyitaw city = $5265.18       
3) Members spend more than Non-Members by $5480.14       
4) Females spend more than Males by $12,799.1     
5) Majority of members use Credit Card to pay their bills whereas non-members use Ewallets


References:-

1) https://www.kaggle.com/aungpyaeap/supermarket-sales
