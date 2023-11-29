**Kapsir Coaches Booking System**

**Overview**
This is a simple console-based booking system for Kapsir Coaches. It allows users to create accounts, log in, view bus information, book seats, and manage bookings. The system is implemented in C programming language.

**Features**
User Authentication: Users can create accounts and log in with their username and password.
Bus Information Management: Authenticated users can add new bus records, display all bus records, and search for a bus by registration number.
Seat Booking: Users can book seats for a specific bus, and the system keeps track of available seats.
Booking Cancellation: Users can cancel their bookings, and the system updates the available seats accordingly.
Booking History: The system maintains a history of bookings, including booking ID, name, and quantity.


**How to Run**
Compile: Compile the program using a C compiler. For example, using GCC: gcc your_program.c -o booking_system.
Run: Execute the compiled program: ./booking_system (on Unix-based systems) or booking_system.exe (on Windows).
User Interface
The program has a simple console interface with menu-driven options. Users can navigate through different functionalities by entering the corresponding option number.

**File Handling**
The system uses file handling to store booking history. The booking history is saved in a file named history.txt. Each booking's information is appended to the file when a new booking is made.


The system supports a maximum of 100 users, 100 buses, and 5000 bookings.
User passwords are stored in plain text, which is not recommended for real-world applications. In practice, passwords should be hashed and stored securely.
