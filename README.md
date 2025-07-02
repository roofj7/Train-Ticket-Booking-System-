
# Train Ticket Booking System (Java Swing GUI)

This is a desktop-based Train Ticket Booking application built using Java Swing. It allows users to input personal details, validates the information, calculates age from DOB, and identifies senior citizens. The app includes a flashing header and real-time UI updates.

# Features

- ✍️ Passenger Name input
- 🎂 Date of Birth input with Age auto-calculation
- 🚻 Gender selection (Dropdown)
- 🛏️ Berth Preference selection (Dropdown)
- ⚠️ Input validation and error messages
- 📜 Scrollable result display
- 💫 Flashing banner using multithreading

# Technologies Used

- Java
- Java Swing (GUI Framework)
- AWT (for layout and event handling)
- Multithreading

# Sample Output
<details> <summary>Click to expand</summary>
BOOKING TRAIN TICKETS

Name: Jessica  
Date of Birth: 03/15/2003  
Age: 21  
Gender: Female  
Berth Preference: Lower  
When inputs are valid, this will show the details including calculated age.

If there's an error (e.g., invalid DOB), the output area will show:

Error: Invalid Date of Birth format. Please use MM/dd/yyyy.

Or:

Error: Please select a Gender.

Or:
Error: You are a Senior Citizen.
</details>

# How to Run
  javac TrainTicketBooking.java
  java TrainTicketBooking
