# Airline Project
Here, a Flights Booking Dataset of various Airlines that is a scraped datewise from a website in a structured format. This dataset contains the records of flight travel details between the different cities in India.
Multiple features are present like Source & Destination City, Arrival & Departure Time, Duration & Price of the flight etc. I will analyse this data with Python in a Jupyter notebook. 
## The various features of the cleaned dataset are explained below: 
1. Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines 
2. Flight: Flight stores information regarding the plane's flight code. It is a categorical feature
3. Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities 
4. Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 ufique time labels 
5. Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities 
6. Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time 
7. Destination City: City where the flight will land. It is a categorical feature having 6 unique cities 
8. Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy. 
9. Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours 
10. Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.
11. Price: Target variable stores information of the ticket price.

After cleaning the data and looking at the data and basic of the data the info i looked up was:
1.No. of Airlines, with their frequencies of flights.
2.Flights with different Departure & Arrival Times.
3.Flights based on Source City & Destination City.
4.Variation in Ticket Prices with Airlines.
5.Change in the Ticket Price based on Departure & Arrival Time.
6.Change in the Ticket Price based on Source & Destination.
7.Effect on Ticket Price before 1 or 2 days the departure of flights.
8.Variation in Ticket Price between Economy & Business Class.
9.Filter the data based on the conditions.
10.Suppose we want to find out “what will be the Average Price of Vistara airline for a flight from Delhi to Hyderabad in Business Class?"

