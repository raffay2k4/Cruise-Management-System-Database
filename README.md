# Cruise-Management-System-Database
The objective for this project was to design and implement a relational database to manage a cruise system. The database handles various entities such as ports, cruise companies, cruises, staterooms, users, cruise trips, bookings, fares, and travelers.

### Tables and Relationships:

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

### Key Operations:

1. Inserts: Add records to tables, including ports, companies, cruises, trips, bookings, fares, and travelers.
2. Updates: Modify existing records, such as updating port names, cruise capacities, and trip details.
3. Deletes: Remove records from tables.
4. Joins: Retrieve combined information across multiple tables, such as cruise names with company names and bookings with user details.
5. Aggregate Functions: Perform calculations like finding cruises with capacity above the average.
6. Correlated Subqueries: Complex queries to find specific data, like users who have booked multiple trips.

This system facilitates comprehensive management of cruises, including detailed tracking of ports, ships, trips, bookings, and associated users.

# Skills
- SQL
- RDBMS

