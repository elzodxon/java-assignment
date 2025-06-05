This Hotel Management tool helps manage various operations such as storing customer information, booking rooms across four different categories, placing food orders for specific rooms, cancelling room bookings, and generating bills. It also allows users to check room features and current availability. The application is menu-driven and continues running until the user chooses to exit.

To preserve the hotel's current status—such as customer data, room bookings, and food orders—the program uses file handling to save this information when it exits. Upon restarting, it reads from the saved file to restore the previous state. File writing is handled in a separate thread to allow parallel execution. A custom exception is thrown if an attempt is made to book a room that’s already occupied, and comprehensive exception handling ensures the program can manage unexpected errors effectively.

Key Concepts Covered:

Classes and Objects

Inheritance

File Handling with Objects

ArrayList

Interface Implementation

User-Defined Exceptions

Exception Handling
