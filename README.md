# JavaFX Form Application
This JavaFX application is a simple form for managing user records. Users can input their information and save it to a file, search for records by ID, and view the results in a separate window.

# Features
Input Fields: Allows users to enter full name, ID, gender, home province, and date of birth.
Gender Selection: Supports male and female options using radio buttons.
Province Selection: Dropdown menu for selecting a home province.
Date Picker: Easy selection of date of birth.
Record Management:
Save new records to a file (records.txt).
Search records by ID and display results.
Clear fields after saving a record.
User Interface: Simple, user-friendly interface built with JavaFX.
Installation
Prerequisites:

Java 8 or higher.
JavaFX SDK.
Clone or Download:

Clone the repository or download the source code.
Compile and Run:

Compile: javac --module-path <path_to_javafx_sdk> --add-modules javafx.controls Main.java
Run: java --module-path <path_to_javafx_sdk> --add-modules javafx.controls Main
File Details
Main.java: The main application code.
records.txt: Stores user records. Automatically created in the working directory.
How to Use
Launch the application.
Fill out the form fields:
Enter Full Name and ID.
Select Gender (Male/Female).
Choose a Home Province from the dropdown.
Pick a Date of Birth.
Click New to save the record.
To search for a record:
Enter an ID in the ID field.
Click Find to search and display the record.
Use the Close button to exit the application.
Features Breakdown
Buttons and Their Functions
New: Saves the record to records.txt and clears the fields.
Delete: (Currently not implemented).
Restore: (Currently not implemented).
Find Prev/Find Next: (Placeholders for future features).
Find: Searches for a record by ID and displays the result.
Criteria: (Placeholder for additional filtering options).
Close: Closes the application.
File Format
The saved records are stored in the following format:

Copy code
FullName,ID,Gender,HomeProvince,DOB
Example:

Copy code
John Doe,12345,Male,Lahore,2000-01-01
Future Enhancements
Implement Delete and Restore functionalities.
Add pagination for navigating through records.
Improve error handling and input validation.
Enhance the UI with better styling.
License
This project is licensed under the MIT License. Feel free to use and modify the code.
