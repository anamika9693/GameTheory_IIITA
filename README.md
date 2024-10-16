Overview
The GameTheory is designed to facilitate the operations team of a sports technology company in managing bookings across multiple centers. The application allows users to manage bookings for various sports, ensuring a smooth experience for both the operations team and customers.

Features
Multiple Centers: Supports operations across various locations (e.g., Indiranagar, Koramangala).
Multiple Sports per Center: Each center offers various sports (e.g., badminton, squash).
Multiple Courts/Resources: Each sport has dedicated courts/resources (e.g., badminton has 2 courts, squash has 3).
Booking Slots: Each booking slot is 60 minutes long.
Customer Bookings: Customers can book slots at their convenience.
Operations Management: Operations team members can manage all bookings for their respective centers.
Technical Requirements
Data Models
Centers: Represents different locations where sports are offered.
Sports: Represents the types of sports available at each center.
Courts/Resources: Represents the courts or resources available for each sport.
Bookings: Represents customer bookings for specific courts, sports, and time slots.
Backend Development
APIs:

View Bookings API: Retrieves bookings for a specific center, sport, and date.
Create Booking API: Allows the creation of a new booking, ensuring there are no conflicts with existing bookings.
Data Handling:

Logic implemented to prevent double bookings of the same slot and court.
Basic error handling and input validation included.
Authentication (Optional):

Optional authentication implementation (e.g., JWT tokens or sessions) to secure APIs.
Frontend Development
User Interface:

Simple UI for the operations team to:
Select a center and a sport.
View bookings for that day for all resources (courts) of the selected sport.
Create new bookings.
Core Features:

View Bookings: Displays bookings for all resources (courts) of the selected sport on the selected date.
Create Bookings: Allows the user to create a new booking by selecting a time slot and court/resource.
Usability:

Intuitive and straightforward UI design.
Feedback provided for successful operations and basic error messages.
