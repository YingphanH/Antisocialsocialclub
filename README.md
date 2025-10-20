# Antisocialsocialclub
## Chipotle Restaurant Analysis

### สมาชิก

###### 1.ฐิติกมล การเนตร 6720422006
###### 2.กมลพรรณ กันทะวงศ์ 6720422002
###### 3.ยิ่งพันธ์ เหมจั่นเพ็ชร 6720422025
###### 4.ณิชาลักษณ์ สวัสดิสรณ์ 6720422019

## Order Contribution 
<img width="500" alt="image" src="https://github.com/user-attachments/assets/1ecf3e30-327d-4818-ab61-d6d4977e8891" />

__Top Order item is__   
1.Chicken Bowl  
2.Chicken Burrito  
3.Chips and Guacamole  
4.Steak Burrito  
5.Canned Soft Drink  
6.Chips  
7.Steak Bowl  
8.Bottled Water  
9.Chips and Fresh Tomato Salsa  
10.Canned Soda

## Sales Contribution
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/16a402e7-4415-486c-9cb6-bf4db7b323cf" />

__Top Sale item is__   
1.Chicken Bowl  
2.Chicken Burrito  
3.Steak Burrito  
4.Steak Bowl  
5.Chips and Guacamole  
6.Chicken Salad Bowl  
7.Chicken Soft Tacos
8.Veggie Burrito  
9.Barbacoa Burrito  
10.Veggie Bowl

Compared Top sale vs Top order, All of Top sale item is food, whil Top order item have a Snacks and Beverages.
that means there are demand for snack and beverage too. So let's bring the new strategy - Bundled item together  
(Food-Food, Food-snack, Food Beverage) to increase Customer's basket size. as current data, there are 4,622 entries,  
and there are only 1,246 entries which have no additional request (26.95%), so in the customer prefer to request something else than the menue in the majority.
Let's Take a look at Top sale item and the average add on value.




## Add on and bundle 
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/11f75249-a69e-4eab-86dd-d133b0171b32" />

As shown on table, there are a huge gap between initail price and maximum add on price, while the mean price for each item is still at least 10% higher than initial price on average
So let's zoom in. Which item should fit for the bundle?  

## Popular add on item
<img width="237" height="355" alt="image" src="https://github.com/user-attachments/assets/0a8a71e9-852f-41b1-affc-41bab03773c2" />

As shown on the table. Canned soft drink is the top choice for bundled with no argument. so we must prioritize this first.
for the next 3, there are both food and beverage, let's take these to bundle as family pack.

