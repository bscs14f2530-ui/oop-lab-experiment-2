📌 Description

This is a simple C++ console-based program that takes a date input from the user in the format MM/DD/YYYY and validates it. The program ensures that the entered month, day, and year are within a valid range before accepting the input.

🧾 Features
Takes user input in MM/DD/YYYY format
Validates month (1–12)
Validates day (1–31)
Validates year (> 0)
Keeps asking until a valid date is entered
Displays the final valid date
🛠️ Technologies Used
C++
iostream
cstdio (for printf and scanf_s)
📂 Program Structure
Struct Used
struct Date {
    int month;
    int day;
    int year;
};

Stores date values in a structured format.

▶️ How It Works
The program prompts the user to enter a date in MM/DD/YYYY format.
It reads input using scanf_s.
It checks:
Month must be between 1 and 12
Day must be between 1 and 31
Year must be greater than 0
If invalid, it asks again.
If valid, it displays the date.
💻 Sample Input
Enter date (MM/DD/YYYY): 13/45/2020
Invalid date! Please enter again.

Enter date (MM/DD/YYYY): 12/25/2023
📤 Sample Output
Date is: 12/25/2023
