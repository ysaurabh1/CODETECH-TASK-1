# CODETECH-TASK-1

#Name: Saurabh Yadav 
#Company:CODETECH IT SOLUTIONS 
#ID: CT0806GK 
#Domain: SQL 
#Duration: 12/12/24 to 12/1/25

Overview of Task 1: Database Joins
<img width="1154" alt="Screenshot 2025-01-03 at 4 12 06 PM" src="https://github.com/user-attachments/assets/f6bed276-e24d-4369-b83d-5611b63b7299" />
<img width="1154" alt="Screenshot 2025-01-03 at 4 11 02 PM" src="https://github.com/user-attachments/assets/28f113bd-10f5-449a-b555-216125411a7b" />
<img width="1154" alt="Screenshot 2025-01-03 at 4 10 33 PM" src="https://github.com/user-attachments/assets/c4ee8f3f-745e-416b-a4ac-0aa3adcf71d1" />
<img width="1154" alt="Screenshot 2025-01-03 at 4 09 37 PM" src="https://github.com/user-attachments/assets/5b551430-2f98-4d93-9da2-c57759b1bcb5" />






#Objective:
The primary aim of Task 1 was to perform various types of SQL joins—INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL OUTER JOIN—on an airline database to extract meaningful insights by combining data from multiple tables. The task focused on utilizing join operations to explore relationships between tables such as Passengers, Tickets, Flights, and Destinations and generating outputs that showcase the integration of this data.

#Database Structure:
The database comprised the following key tables:

Passengers: Contains passenger details, such as PassengerID, FirstName, LastName, Gender, and Age.
Tickets: Includes ticket information, such as TicketID, PassengerID, FlightID, BookingDate, and SeatNumber.
Flights: Stores flight details, including FlightID, FlightNumber, DepartureTime, ArrivalTime, Origin, and DestinationID.
Destinations: Holds destination data, with fields like DestinationID, City, and Country.
Each table is interconnected using foreign key relationships. For example, the PassengerID in the Tickets table links to the Passengers table, while FlightID in the Tickets table connects to the Flights table. These relationships facilitated meaningful joins between tables.

1. Inner Join:
An INNER JOIN returns only the rows that have matching values in both tables. This join was used to identify passengers who have booked tickets and the flights associated with those tickets.
2. Left Join (Left Outer Join):
A LEFT JOIN returns all records from the left table (Passengers) and the matched rows from the right table (Tickets). Unmatched rows from the right table return NULL values.
3. Right Join (Right Outer Join):
A RIGHT JOIN does the opposite of a LEFT JOIN, returning all rows from the right table (Tickets) and matching rows from the left table (Passengers).
4. Full Join (Full Outer Join):
A FULL OUTER JOIN returns all rows when there is a match in either table. If no match is found, NULL values are included for the unmatched side.
#Challenges and Insights:
Handling NULL Values: Outer joins (LEFT, RIGHT, and FULL) introduced NULL values in the output for unmatched rows. Interpreting these NULL values correctly was essential to avoid misrepresenting the data.
Data Integrity Issues: During testing, unmatched records revealed potential issues such as passengers without tickets or flights without bookings. This highlighted areas for database maintenance.

#Conclusion:
Task 1 successfully demonstrated the power of SQL joins in combining data from multiple tables. The insights derived from these joins showcased how database relationships could be leveraged for operational analysis and decision-making. The task also highlighted the importance of maintaining data integrity for effective database operations.
