# Roggy-s-Cars-Uncovering-Patterns-in-Car-Sales.
This repository tells us about factors influencing the prices of cars. This project analyzes car sales data in order to finetune out trends and patterns in pricing so as to understand what drives the key determinants of the cost of cars. 
Roggy’s Cars: Uncovering Patterns in Car Sales.

<img width="808" height="402" alt="CAR SALES DASHBOARD" src="https://github.com/user-attachments/assets/0460a30b-d70a-4823-940e-82528592e5fd" />

Roggy’s Car Sales Analysis for Different Manufacturers, 2021

Introduction: 
The Car market is a vast and competitive industry with different factors influencing the prices of vehicles, some of which are; their Engine sizes, Fuel type, Year of manufacture etc. This project analyzes car sales data in order to finetune out trends and patterns in pricing so as to understand what drives the key determinants of the cost of cars.
By analyzing correlations like Engine size, Fuel type, Year of Manufacture etc.key takeaways can be gained into the automotive market.
Objectives:
 1. To identify determinants affecting car prices.
2. To understand customer preferences.
3. To find out which cars are top sellers and why.
Methodology:
The next step taken for this analysis was to input the data in a pivot table to find the relationship between variables.

<img width="644" height="239" alt="CS 1" src="https://github.com/user-attachments/assets/ecabecd7-a68f-4638-98d7-f848981cf0da" />

This is a Bar chart that shows the Most Priced Manufacturer. From the Pivot table, Porsche is seen to be the most priced manufacturer with an average price of $29,104 while VW is the least priced manufacturer with about $10,362.

<img width="562" height="231" alt="CS 2" src="https://github.com/user-attachments/assets/bfe505e9-fbcd-4802-b011-acf3ae31bd8d" />

The Column chart here shows us the total number of cars sold. From the pivot table, Ford sold the highest number of cars. It sold about 14,956 cars while Porsche sold the lowest number of cars (2,609).

<img width="532" height="230" alt="CS 3" src="https://github.com/user-attachments/assets/ad4a21a7-a208-4eca-bf14-65f409e6b199" />

The Engine Type vs Price is recorded in a Pie-chart. Cars with 4-5 engine size has the highest average price while cars with 1-2 engine size is the least priced.

<img width="566" height="231" alt="CS 4" src="https://github.com/user-attachments/assets/ccea1298-31f3-40d5-b1fc-523035235b6d" />

Fuel type vs Price is shown in a Pie-chart. The 3 different car fuel types are Hybrid, Petrol and Diesel. From the Pivot Table, Hybrid fuel type cars has the highest average price while Diesel has the least average price.

<img width="515" height="233" alt="CS 5" src="https://github.com/user-attachments/assets/7013d643-db94-4083-a4c4-1cce3f3e20b9" />

Relationship between year of manufacture vs car price is represented in a Bar chart. From the visual representation, cars produced in recent years seem to be the most priced cars. This could be because of upgrade in their features and increase in demand.

<img width="556" height="236" alt="CS 6" src="https://github.com/user-attachments/assets/ddeb5422-9a1d-4c6c-a06f-2f0ea0f882e7" />

The Bar chart above shows the relationship between Mileage and Price. The lower the mileage, the higher the value of the car. Here, cars with the least total of km run are the most priced.

Story of Data:
This project is a project linked to the Automotive Industry that shows factors influencing car sales with the dataset gotten from kaggle.com. It consists of 49,988 rows and 7 columns which are Manufacturer, Model, Engine Size, Fuel Type, Year of Manufacture, Mileage and Price. All of these can be regarded as the key variables of the dataset as they are the factors that determine the prices of cars.  

Data Splitting and Preprocessing:
- Data Cleaning
The dataset was downloaded from kaggle.com and loaded into an Excel Workbook. Checks were performed for blanks and duplicates while a currency sign was added to the price column. 
 In order to preserve the original dataset, the raw data was duplicated and retained for reference. 
- Data Splitting
Independent
 - Manufacturer
- Model
- Fuel type
- Year of Manufacture
- Engine size
- Mileage
Dependent
  - Price


Industry context and Stakeholders
This project is connected with the Automotive Industry, focusing on understanding the factors influencing car sales. Stakeholders to be impacted are Car Manufacturers, Car Dealers, Investors in Car Manufacturing Companies and Car Data Providers.

Potential-Analysis Questions:
- Which is the top manufacturer by price?
- Which is the top manufacturer by count (number of cars sold)?
- What is the correlation between engine size and price?
- What is the impact of fuel types on prices of cars?
- How does the year of manufacture affect the prices of cars?
- How does the mileage of cars affect their prices?
 
Pre-Analysis Insights:
- To examine and compare average prices across manufacturers.
- To find out manufacturer popularity so as to develop market presence insights.
- To find and analyze the relationship between engine size and prices of cars.
- To analyze how fuel types correlates with prices of cars.
- To inspect how car prices vary with the age/year of manufacture of a car.
- To ascertain the relationship between prices of cars and their mileage.
 

Data Visualizations:
  - Fuel Type vs Price: A Pie-Chart was used.
  - Engine Size vs Price: A Pie-Chart was used.
  - Most Priced Manufacturer: A Bar-chart was used.
  - Manufacturer Popularity: A Column-chart was used.
  - Year of Manufacture: A Bar-chart was used.
  - Price vs Mileage: A Bar Chart was used.
 
In-Analysis Observations:
Analysis: Year of Manufacture vs Price
- Cars that are recently manufactured are higher in price than those that were manufactured in the past. This is due to engine upgrade, body upgrade, functions etc.
- By Average price, Cars manufactured in 2022 are more pricey, they are sold for $59,023.
- Cars manufactured in 2021 are sold for $49,717 which is almost similar in price with that of 2022.
- Cars manufactured 2020 are sold for $46,211, 2019 models are sold for $41,034 while 2018 models are sold for $36,073.
 
Analysis: Fuel Type vs Price
- By fuel type, Hybrid cars are more pricey than others, it is sold for  (AVG) $14,949. Petrol used cars are sold for $13,691 while Diesel cars are sold for $13,146.

 Analysis: Engine Size vs Price
- By Average price, Engines with size 4-5 are higher in price than those that are 1-4. Engines with size 4-5 are sold for $36,885, Engines that are size 3-4 are sold for $26,170, size 2-3 are sold for $16,497 while size 1-2 are sold for $10,751.

Analysis: Top Manufacturer by Price 
- By rank, the most priced (AVG)Manufacturer is Porsche, with $29,104, next is BMW ($24,432), Toyota ($14,341), Ford ($10,671) and VW ($10,362).

Analysis: Manufacturer Popularity
- By count, Ford sold the highest number of cars, it sold 14956 models, next is VW which sold 14906 models.
- There is a very slight difference in the total number of cars sold between Ford and VW.
- Toyota ranked 3rd by selling 12553 models, BMW ranked 4th (4964) while Porsche ranked the least (2609).


In-Analysis Recommendations:
Analysis: Year of Manufacture vs Price
- Recently manufactured cars should be purchased more during restocking so as to drive sales and increase revenue.
- Cars produced in the earlier years have the lowest average prices and depreciate over time. Therefore, recently manufactured cars should be higher in restock than the early manufactured ones.

Analysis:Fuel Type vs Price
- Hybrid vehicles had the higher average prices for manufacturers like Ford, VW and Toyota. It also had the highest average price amongst the 3 fuel types. Therefore, Hybrid fuel type vehicles should be focused on (always available) so as to generate more profit.

Analysis: Engine Size vs Price
- Following the observation, larger engine sizes commands larger average prices which will in turn generate great revenue when sold. Therefore, brands with larger engine sizes should always be made readily available for sale.
- Also, smaller engine cars should also be considered because they fit into the  budget of most customers (judging from the general observation  board). 

Analysis: Top Manufacturer by Price
- Brands like Porsche and BMW should be marketed mostly to customers in need of luxury brands while Toyota, Ford and VW should be marketed to customers with a budget.

Analysis: Manufacturer Popularity
- Customer feedback should be gathered from customers to understand their needs and budget.
- Ford and VW brands should be constantly available for buyers with a budget so as to generate more revenue.

Post-Analysis Observations:
Analysis: Year of Manufacture vs Price
- By Average price, Cars manufactured in 2022 are more pricey, they are sold for $59,023. 2022  Porsche is the most priced Model with an average of $112,659. 2022 car models with 4-5 engine size are the most sold, they are sold for an average of $146,092. 2022 petrol cars are more pricey than hybrid and diesel, they are sold for an average of $62,046.
- Cars manufactured in 2021 are sold for $49,717 which is almost similar in price with that of 2022. 2021  Porsche is the most priced Model with an average of $100,542. 2021 car models with 4-5 engine size are the most sold, they are sold for an average of $135,136. 2021 hybrid cars are more pricey than diesel and petrol cars, they are sold for an average of $50,894.
- Cars manufactured 2020 are sold for $46,211. 2020  Porsche is the most priced Model with an average of $90,549. 2020 car models with 4-5 engine size are the most sold, they are sold for an average of $120,090. 2020 hybrid cars are more pricey than diesel and petrol cars, they are sold for an average of $48,004.
- 2019 models are sold for $41,034. 2019  Porsche is the most priced Model with an average of $83,890. 2019 car models with 4-5 engine size are the most sold, they are sold for an average of $106,164. 2019 hybrid cars are more pricey than diesel and petrol cars, they are sold for an average of $43,677.
- 2018 models are sold for $36,073. 2018  Porsche is the most priced Model with an average of $74,532. 2018 car models with 4-5 engine size are the most sold, they are sold for an average of $96,823. 2018 hybrid cars are more pricey than diesel and petrol cars, they are sold for an average of $40,029. 


Analysis: Fuel Type vs Price
- By fuel type, Hybrid cars are more pricey than others, it is sold for  (AVG) $14,949. Petrol used cars are sold for $13,691 while Diesel cars are sold for $13,146
- Toyota is the most priced hybrid fuel type car (AVG $15,329), next is Ford ($12,600) and least is VW ($12,389). Hybrid fuel type cars with 2-3 engine size are sold for an average of  $19,987, 1-2 engine size is sold for $13,305. For age of car, 2022 hybrid cars are more pricey than hybrid cars produced before the year 2022 ($60,511).
- Porsche is the most priced Petrol fuel type car (AVG $29,205), next is BMW ($26,603), Toyota ($10,953), VW ($9,158) and Ford ($9,069). Petrol fuel type cars with 4-5 engine size are sold for an average of $37,175, 3-4 engine size is sold for $27,889, 2-3 engine size is sold for an average of  $15,981, 1-2 engine size is sold for $8,802. For age of car, 2022 Petrol cars are more pricey than hybrid cars produced before the year 2022 ($52,020).
- Porsche is the most priced Diesel fuel type car (AVG 28,247) BMW (18,148), Ford ($12,570) and VW ($11,924). Diesel fuel type cars with 4-5 engine size are sold for an average of $28,773, 3-4 engine size is sold for $22,361, 2-3 engine size is sold for an average of  $14,622, 1-2 engine size is sold for $11,878. For age of car, 2022 Diesel cars are more pricey than hybrid cars produced before the year 2022 ($62,046).

Analysis: Engine Size vs Price
- By Average price, Engines with size 4-5 are higher in price than those that are 1-4. Engines with size 4-5 are sold for $36,885, Engines that are size 3-4 are sold for $26,170, size 2-3 are sold for $16,497 while size 1-2 are sold for $10,751.
- For 4-5 engine size, BMW is the most priced, it is sold for an average of $39,911, next is Porsche, which is sold for $27,512 (Toyota, Ford and VW do not have this available). For fuel type, Petrol cars with 4-5 engine size are the most priced, they are sold for an average of $37,175 while Diesel is sold for $28,773 (Hybrid fuel type cars do not have this size of engine available). For age of car, 2020 models with 4-5 engine size are the most priced, they are sold for an average of $120,090.
- For 3-4 engine size, Porsche is the most priced, it is sold for an average of $34,777, next is BMW which is sold for $18,524 (Toyota, Ford and VW do not have this available). For fuel type, Petrol cars with 3-4 engine size are the most priced, they are sold for an average of $27,889 while diesel is sold for $22,361 (Hybrid fuel type cars do not have this size of engine available). 2022 models with 3-4 engine size are the most priced, they are sold for an average of $108,268.
- For 2-3 engine size, Porsche is the most priced, it is sold for an average of  $25,973, next is BMW which is sold for $16,062, Toyota $19,717, Ford $13,643 and VW $11,893 (Toyota, Ford and VW do not have this available). For fuel type, hybrid fuel type cars with 2-3 engine size are the most priced, they are sold for an average of $19,987. Next is Petrol and then Diesel. 2022 models with 2-3 engine size are the most priced, they are sold for an average of  $71,294
- For 1-2 engine size, Toyota is the most priced, it is sold for an average of $12,552, Ford $10,159 and VW $9,949 (Porsche and BMW do not have this available). For fuel type, hybrid fuel type cars with 1-2 engine size are the most priced, they are sold for an average of $13,305. Next is Petrol and then Diesel. 2022 models with 1-2 engine size are the most priced, they are sold for $42,761.



Analysis: Top Manufacturer by Price
- By rank, 2022 Porsche is the most priced, next is BMW, Toyota, Ford and the least priced is VW.
- By count, Ford sold the highest number of cars, it sold 14956 cars. It sold 5057 Mondeo models, 4975 Focus and 4924 Fiesta. For engine size, 2-3 engine size is sold for an average of $13,643 while 1-2 engine size is sold for $10,159. For fuel type, hybrid fuel type is sold for an average of $12,600, Petrol fuel type is sold for $9,069 while diesel is sold for $12,590. The average price of hybrid fuel type for Ford is higher than petrol and diesel. 2022 Ford is sold for an average of $41,933 which is higher than those manufactured in 2021 and below.
- VW ranked 2nd by number of cars sold (14906). It sold 5049 Golf, 4988 Polo and 4869 Passat. 2-3 engine size is sold for an average of $11,893 while 1-2 engine size is sold for $9,949. For fuel type, hybrid is sold for an average of $12,389, Petrol fuel type is sold for $9,158 while Diesel fuel type is sold for $11,924. 2022 VW is sold for an average of $41,264 which is higher than those manufactured in 2021 and below.
- Toyota sold 12553 cars. It sold 4292 RAV4, 4171 Prius and 4090 Yaris. 2-3 engine size is sold for an average of $19,717, while 1-2 engine size is sold for $12,552. For fuel type, hybrid fuel type is sold for an average of $15,329, while Petrol is sold for $10,953. 2022 Toyota is sold for an average of $58,914 which is higher than those manufactured in 2021 and below.
- BMW sold 4964 cars. It sold 1687 Z4, 1645 M5 and 1632 X3. For engine size, BMW has 4-5 engine size which is sold for an average of $39,199, 3-4 engine size which is sold for $18,524 and 2-3 engine size which is sold for $16,062. The engine with the highest size has the highest price. For fuel type, petrol fuel type is sold for an average of  $26,603 while Diesel fuel type is sold for $18,148. The average price of a petrol fuel type BMW is higher than that of Diesel. 2022 BMW is sold for an average of $102,364 which is higher than those manufactured in 2021 and below.
- Porsche sold the least number of cars. It sold 872 911 Model, 870 Cayenne and 867 718 Cayman. For engine size, 4-5 engine size is sold for an average of $27,512, 3-4 engine size is sold for $34,777, and 2-3 engine size is sold for $25,973. For fuel type, petrol is sold for an average of $29,205 while Diesel is sold for $28,247. 2022 Porsche is sold for an average of $112,659 which is higher than those manufactured in 2021 and below.

Analysis: Manufacturer Popularity
- By count, Ford sold the highest number of cars, it sold 14956 models. For engine size, ford sold 12755 cars with 1-2 engine size and it sold 2201 cars with 2-3 engine size. Ford sold 8119 petrol used cars, 5824 diesel used cars and 1013 hybrid cars. 
- VW  sold 14906 models, it sold 11744 cars with 1-2 engine size and 3162 cars with 2-3 engine size. VW sold 8504 petrol used cars, 5889 diesel used cars and 513 hybrid cars.
- Toyota ranked 3rd by selling 12553 models, it sold 9419 cars with 1-2 engine  size and 3134 cars with 2-3 engine size. It sold 2835 petrol used cars and 9718 hybrid cars.
- BMW ranked 4th (4964), it sold 2379 cars with 2-3 engine size, 940 cars with 3-4 engine size and 1645 cars with 4-5 engine size. It sold 3689 petrol used cars and 1275 diesel used cars.
- Porsche ranked the least (2609), it sold 1243 cars with 2-3 engine size, 835 cars with 3-4 engine size and 531 cars with 4-5 engine size. It sold 2333 petrol used cars and 276 diesel used cars

Post-Analysis Insights:
Analysis: Year of Manufacture vs Price
- Newer models had the highest average price across all brands and should be considered more when restocking. This is because of its high and strong value.
- Hybrid cars had the highest average price for earlier years (2021-2018). With this, such cars should be made available for sale at all times.
- Cars produced in the earlier years have the lowest average prices and depreciate over time. Therefore, recently manufactured cars should be higher in restock than the early manufactured ones.

Analysis: Fuel Type vs Price
- Hybrid cars should be focused on because there is a strong market value for hybrid cars based on its average pricing.
- 2022 models have the highest pricing across all fuel types and should be considered more during restocking.
- Larger engines equals top pricing for petrol and diesel fuel type cars. Brands that meet these requirements should be constantly marketed to buyers who want a high performing car so as to drive sales and increase revenue.

Analysis: Engine Size vs Price
- Following the observation, larger engine sizes commands larger average prices which will in turn generate great revenue when sold. Therefore, brands with larger engine sizes should always be made readily available for sale.
- For engine sizes 2-4, Porsche takes the lead with the highest average pricing. With this, making it constantly available for sale can indeed boost revenue and drive sales growth.
- Hybrid fuel type cars have a higher value in smaller engine sizes according to the observation,which means it adds values in smaller engine cars and should always be in stock.
- For customers who may prefer luxury cars, BMW with larger engine types (4-5) should be marketed, as they are high in price and would generate more revenue.

Analysis:Top Manufacturer by Price
- Hybrid vehicles had the higher average prices for manufacturers like Ford, VW and Toyota. It also had the highest average price amongst the 3 fuel types. Therefore, Hybrid fuel type vehicles should be focused on (always available) so as to generate more profit.
- Vehicles manufactured in 2022 for all brands have higher average prices. This means that new models bring value. Therefore, newer models of all brand types should be readily available for sale so as to generate more revenue.
- Brands of cars with smaller engines should be readily available. This is because Smaller engine sizes (1-2) have lower average prices which will be the target for budget buyers.
- Top selling models like Ford's Mondeo, VW's Golf and Toyota's RAV4 should be focused on for market penetration and revenue generation.

Analysis: Manufacturer Popularity
- Ford cars using petrol seem to be the most sold in the Ford brand and should be made readily available for sale.
- Feedbacks should be gathered from customers so as to understand their purchasing needs.
- The Porsche brand cars should be looked into to understand why it sold the least cars.
- Smaller engine cars had high sales. This may be because they fit into the small budget of customers. Therefore, such cars should be considered when restocking.  

Conclusion: 
The analysis of car sales data provides key takeaways in the automotive industry, showcasing trends and patterns in car sales that will contribute to a more efficient market. 
Reference: kaggle.com 






