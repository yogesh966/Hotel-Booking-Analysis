# Hotel Booking Analysis - EDA

Click on the following link to checkout the video presentation and the colab file.
- [colab](https://colab.research.google.com/drive/1ykC2SYSOGjKJFe1DMUQhdhqo3DGt2-Fw?usp=sharing)
- [Video]()


---

## Problem Statement

Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyze the data to discover important factors that govern the bookings.

---

## Business Objective

- Analyse the data on bookings of City Hotel and Resort Hotel to gain insights on the different factors that affect the booking. This is undertaken as an individual project.

---

## Project Summary
In this project I began to explore the dataset in which Hotel Booking comprises of two types of hotels i.e City Hotel and Resort Hotel.

In this dataset, there are 119390 rows and 32 columns.

All the columns are divided into three dtypes : Object, float64 and int64.

AT the beginning I was shocked by seeing so many complex data in csv file.I had no idea what to do ,how do I start the projet,from where to start.
In this dataset, there are both duplicates and missing values available. So, I have to deal with that and as a result i have replaced the null and missing values and also i dropped the duplicate values.

After that I understood that I need to clean the data by removing some dubplicate,null values.After that I did EDA on the data to make data suitable for the further analysis and operations.
So, in order to successfully complete this project the steps that I have follwed are aas follows:

1.First I took hotal bookings.csv file and link to our individual colab notebook to grab all the data of csv.

2.Created data(data frame) using csv file.

3.Then applied numpy arrays whose have an attribute called .shape that returns a tuple with each index having the number of corresponding elements.

4.Applied head() function in python which displays the first five rows of the dataframe by default,with transpose() were it is moving the rows data to column and column to rows 'T' is for rows to columns and columns to rows.

5.Used tail() function for displaying last five rows and columns of the dataframe by default.

6.Applied The info() method that gives prints information about the DataFrame.

7.Applied the describe() method that returns description of the data in the DataFrame.

8.Applied the columns property that returns the label of each column in the DataFrame.

9.Understood each variable in dataframe.

10.Removed duplicates,null values from dataframe.

11.Added some columns for further use.


after all this functions,some type of questions were came in my mind like when we book room in hotel and other stuff. I found some intresting questions which are almost 20 questions and then filter out them and I got 10 best questions are following:

1. What is preffered stay in each hotel?

2. What is the percentage of bookings in each hotel?

3. Which agent makes most no. of bookings?

4. Which meal type is most preffered meal of customers?

5. Which is the most common channel for booking hotels?

6. Which room type is in most demand and which room type generates highest adr?

7. From where most guests are coming?

8. Which hotel has higher lead time?

9. which hotel seems to make more revenue?

10. Which significant distribution channel has highest cancellation percentage?

11. which channel is mostly used for early booking of hotels?

12. which channel has longer average waiting time?

13. Which hotel has longer waiting time?

14. Which hotel has higher bookings cancellation rate?

After doing some random EDAs.I've gained some confidence.

Then I decided to do analysis.For which I took help of a bar chart and some lineplots.I made a DataFrame of which agent makes most number of bookings and dataframe of Which meal type is most preffered meal of customers?. made a Pie Chart for better visualisation.

I also realise that the high rate of cancellations can be due high no deposit policies.

Majority of the hotels booked are city hotel. Definitely need to spend the most targeting fund on those hotel.

this is the best EDA that I did and memorable experience for me in this project.

---

## Solution to Business Objective

1.The goal for this project is predicting which kind of customers need special request and predicting the possibility of a booking for a hotel by knowing different features. This will help the hotel booking company to make better decisions.

2.Set Non-refundable Rates, Collect deposits, and implement more rigid cancellation policies.

3.Encourage Direct bookings by offering special discounts.

4.Monitor where the cancellations are coming from such as Market Segment, distribution channels etc.

5.the latest supporting technologies to ensure hotel rooms and services are priced at the right rate regardless ofperiods of high or low demand.

6.hoteliers need to ensure that they have detailed data that is both historical and forward looking.

7.Any changes in price should be monitored closely for impact on levels of demand. This information can then be used to control demand accordingly, using daily revenue management and pricing strategies.

---

## Conclusion
(1) Around 60% bookings are for City hotel and 40% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. Also the overall adr of City hotel is slightly higher than Resort hotel.

(2) Mostly guests stay for less than 5 days in hotel and for longer stays Resort hotel is preferred.

(3) Both hotels have significantly higher booking cancellation rates and very few guests less than 3 % return for another booking in City hotel. 5% guests return for stay in Resort hotel.

(4) Most of the guests came from european countries, with most of guests coming from Portugal.

(5) Guests use different channels for making bookings out of which most preferred way is TA/TO.

(6) For hotels higher adr deals come via GDS channel, so hotels should increase their popularity on this channel.

(7) Not getting same room as reserved, longer lead time and waiting time do not affect cancellation of bookings. Although different room allotment do lowers the adr.

(8) BB (bed and breakfast) is the most prefered type of meal in hotel.

(9) For customers, generally the longer stays (more than 15 days) can result in better deals in terms of low adr.

(10 TA/TO is the most common channel for booking hotels.

(11) City hotel seems to be making more revenue than Resort hotel.

(12) Most guests are coming from portugal.

(13) Most Demand room type is A,but better adr rooms are of type H,G and c.

(14) The hotel which has higher lead time is City hotel. TA/To channel has highest cancellation percentage.

(15)
* Total stay length and lead time have slight correlation. This may means that for longer hotel stays people generally plan little before the the actual arrival

* adr is slightly correlated with total_people, which makes sense as more no. of people means more revenue, therefore more adr.
---

## Author

- [Yogesh Rode](https://www.linkedin.com/in/yogesh-rode-961878215/)
