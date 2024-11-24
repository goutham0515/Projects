# Projects

# Superstore Sales Dashboard

### Dashboard Link : 

## Problem Statement

The Dashboard operates a chain of superstores across multiple locations. The goal of this analysis is to leverage the Power BI tool to gain insights into the sales, profit margins, and performance of different product categories and regions. This will help the management make data-driven decisions to optimize operations, improve sales, and increase profitability..

The analysis will cover multiple years of sales data, including both revenue and profit, across different product categories, store locations, and regions.
Key metrics include: Sales, Profit, Profit Margin, Units Sold.




### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under  Data      preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 

           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
          
- Step 10 : A bar chart was also added to the report design area representing the number of satisfied & neutral/unsatisfied customers. While creating this visual, field named "Gender" was also added to the Legends bucket, thus number of customers are also seggregated according the gender. 
- Step 11 :  Visual was used to represent different Sub Catageries mentioned below,

  (a) Accessories

  (b) Appliances
  
  (c) Arts
  
  (d) Binders
  
  (e) Bookcases
  
  (f) Chairs

  (g) Copiers
  
  (h) Envelopes
  
  (i) Fastenes
  
  (j) Furnishinges
  
  (k) Labels
  
  (l) Machines
  
  (m) Papers

  (n) Phones

  (o) Storage

  (p) Supplies

  (Q) Tables
  

A card visual was used to represent the Sum of profit,sales and quantity of categories.

![Sales2024-11-24 123250](https://github.com/user-attachments/assets/c543f8b5-7ee3-49d7-a9d1-603a1e159fc1)

   
     This table shows total Sales according to the sub-category along with consumer corporate and home office Sales

 ![2024-11-24 125229](https://github.com/user-attachments/assets/eef1adf4-0c9d-47c2-9709-01b4141b3ac1)

# Snapshot of Dashboard (Power BI Service)


![Power-bi 2024-11-23 230831](https://github.com/user-attachments/assets/34b1057e-7f19-459e-9893-cc40a622c576)

Sub Catageries involved Phones and Chairs are the top most Sales in Superstore over 0.33M Sales According to the data from      2011 - 2014

Superstore has fail to sail products like Arts ,Envelopes,Labels and Fasteners

According to the visualizations 

(1) New York City

(2) los Angeles

(3) Seattle

(4) San Francisco

(5)Philadelphia

Are the states generated more revinue compair to others ststes USA

 This Power BI project leverages advanced data modeling to deliver a dynamic analysis of a superstore's operations, transforming raw data into actionable insights. It unravels patterns in sales, discounts, and revenue across categories like Technology, Furniture, and Office Supplies, highlighting regional performance with the West emerging as a key revenue hub. The integration of predictive modeling enables the identification of shipping efficiencies, with Standard Class driving both sales and operational success. Temporal trend analysis uncovers peak revenue periods From Consumers compair to Corporate and Home office  while category-level deep dives reveal opportunities for growth and cost optimization.

