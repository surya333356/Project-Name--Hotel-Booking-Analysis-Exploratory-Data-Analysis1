# Project-Name--Hotel-Booking-Analysis-Exploratory-Data-Analysis1
# Project Type - EDA/Regression/Classification/Unsupervised
# Contribution - Individual-SURYA SINGH

# Define Your Business Objective:

The objective of this project is to conduct an Exploratory Data Analysis (EDA) on a dataset containing hotel bookings information. 
The analysis aims to uncover insights, identify patterns, and extract meaningful information that can help hotel management improve booking strategies,
enhance customer experience, and optimize revenue management.

# Project Summary:

This project is related to Hotel Booking having two hotel description i.e City Hotel and Resort Hotel. In this dataset contains total rows 119390 and 32 columns.
In this we divide data manipulation workflow in three category Data Collection ,Data cleaning and manipulation and EDA(Exploratory Data Analysis).
As Further moved i.e Data collections first step to find different columns which is done by coding Head(), tail(), info(), describe(), columns() and some others method used for data collections,
some of the columns name is updated here i.e hotel,is_canceled,lead_time,arrival_date_year,arrival_date_month,arrival_date_week_number,arrival_date_day_of_month,stays_in_weekend_nights.
As we further moved we find unique value of each columns and generate a list in tabular form and also check the dataset type of each columns’ find some columns not in accurate data types which correct it
later done in Data cleaning part and as well as duplicates data items must be removed as we find duplicates items equal to 87396 which is dropped from dataset later.

Before visualize any data from the data set we have to do data wrangling. For that, we are checked the null value of all the columns. After checking, when we are getting a column which has more number of null values,
dropped that column by using the 'drop' method. In this way, we are dropped the 'company' column. When we are find minimal number of null values, filling thse null values with necesary values as per requirement by using .fillna()

Different charts are used for data visualization so that better insights and Business objective is attained.

# Problem Statement:
1. Which type of hotel is most preferred by the guests?

2. What is the Percentage of hotel booking cancellation?

3. Which type of meal is most preferred by the guests?

4. Which type of hotel got more revenue?

5. Which distribution channel is most used in booking?

6. Which room type is most preferred by guests?

7. Top 5 agents in terms of most bookings.

8. What is the percentage of repeated guests?

9. Which market segment has most booking?

10. Which deposit type is most preferred?

# Business Objective:

To achieve the business objectives of increasing bookings, reducing cancellations, and optimizing revenue, the client should leverage data insights to:

Implement targeted marketing campaigns and dynamic pricing strategies.

Offer flexible booking policies and improve customer communication to reduce cancellations.

Enhance revenue management practices and control operational costs to improve profitability.

By focusing on these strategies, the client can enhance their competitiveness in the market, improve customer satisfaction, and achieve sustainable growth.

# Conclusion:
1. City Hotel seems to be more preferred among travellers and it also generates more revenue & profit.

2. Room Type A is the most preferred room type among travellers.

3. City Hotel retains more number of guests.

4. Around one-fourth of the total bookings gets cancelled. More cancellations are from City Hotel.

5. New guest tends to cancel bookings more than repeated customers.

6. As we have seen, BB (Bed & breakfast) meal is most prefered by guests in both the hotels. So Hotel can give more delisious dishes in this meal to get customer repeat & attaract new customer

Agent 9 is the highest-performing agent with 28,759 bookings, significantly more than any other agent. This agent likely has a strong customer base or partnership with the hotel.

7. We have seen that most guests prefer or are more likely to book accommodations without the need for an upfront payment.

8. Here, we have seen that the number of repeated guests is very less as compared to overall guests.

9. We have seen clearly that online/TA market segment has most bookings.

10. Peak Season: Both hotels experience their peak ADRs during the summer months, with Resort Hotel showing a sharper increase, likely due to higher demand for resort-type accommodations during vacations.

Off-Peak Season: The lowest ADRs are observed in January and November, suggesting these are the off-peak months with lower demand.

11. Based on the correlations, we have observed some interesting relationships:

'stays_in_week_nights' and 'total_stay_in_nights' have a very high positive correlation (0.95), indicating that they are almost perfectly linearly related.

'adults' and 'total_guest' have a strong positive correlation (0.80), suggesting that the total number of guests is strongly related to the number of adults.

'arrival_date_year' and 'arrival_date_week_number' have a moderate negative correlation (-0.51), indicating an inverse relationship between the year and the week number.

# EDA Charts:

![image](https://github.com/user-attachments/assets/5f6ea228-ad68-44b1-9c04-2df5a44a9c8b)

![image](https://github.com/user-attachments/assets/def32893-52e5-42c8-9e82-3f5d36e77972)

![image](https://github.com/user-attachments/assets/8f4f00dd-6af4-48db-98c7-15850c7af046)

![image](https://github.com/user-attachments/assets/32a82af5-68c9-403c-adcc-69404809f9b3)

![image](https://github.com/user-attachments/assets/3466952a-daee-44b8-bba8-3f9b4b5fc412)

![image](https://github.com/user-attachments/assets/1bec0f26-15d5-48d3-8f85-970757dfc910)

![image](https://github.com/user-attachments/assets/b90c57b3-9540-4bb0-9126-2f2f6aee0028)

![image](https://github.com/user-attachments/assets/e57be67f-278b-4c8d-b3bc-8a1b7bda98f2)

![image](https://github.com/user-attachments/assets/937dbeec-80d4-4a00-bcd7-ac1b716ddb7f)
















