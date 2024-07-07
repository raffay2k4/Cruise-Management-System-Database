# Cruise-Management-System-Database
The objective for this project was to design and implement a relational database to manage a cruise system. The database handles various entities such as ports, cruise companies, cruises, staterooms, users, cruise trips, bookings, fares, and travelers. The system also supports CRUD (Create, Read, Update, Delete) operations, as well as complex queries and aggregations.

Tables and Relationships:

1. PORTS: Stores details of ports.
2. CRUISE_COMPANY: Stores information about different cruise companies.
3. CRUISE: Contains details about individual cruises, linked to cruise companies.
4. CRUISE_PORT_ACCESS: Links cruises to ports they access.
5. STATEROOM: Details about staterooms on each cruise.
6. END_USER: Stores user information.
7. CRUISE_TRIP: Details of cruise trips including departure and arrival ports and dates.
8. BOOKS: Links users to their booked cruise trips.
9. FARE: Contains fare details for each trip.
10. TRAVELLER: Records travelers and their assigned rooms on cruises.
