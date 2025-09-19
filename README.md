# Employee Management System (EMS)

## Description

The **Employee Management System (EMS)** is a Java-based console application that allows for managing employee information. The system provides options to add, view, update, and remove employee details. Employee information is stored in individual text files, with each file named after the employee's ID.

## Features

* **Add Employee**: Add a new employee's details (name, father’s name, employee ID, email, position, contact, and salary).
* **View Employee**: View the details of an employee by entering their ID.
* **Remove Employee**: Remove an employee's details from the system by entering their ID.
* **Update Employee**: Update any detail of an employee by entering their ID and the specific field to be updated.
* **Exit**: Exit the system with a thank you message.

## Prerequisites

* **Java Development Kit (JDK)** version 8 or higher.
* Basic knowledge of Java programming and file handling.

## How It Works

1. **Add Employee**:

   * The program will ask for employee details such as name, ID, email, position, contact, and salary.
   * This information will be saved to a text file named `file<employee_id>.txt`.

2. **View Employee**:

   * By providing the employee ID, the program will display the employee’s details from their respective file.

3. **Remove Employee**:

   * By entering the employee's ID, the corresponding text file will be deleted, effectively removing the employee from the system.

4. **Update Employee**:

   * The user can choose a field (like Name, Email, Salary, etc.) to update. The old value is replaced with the new value provided by the user.

5. **Exit**:

   * When the user selects to exit, a thank-you message will be displayed, and the program will close.

## Usage Instructions

1. **Compile the Code**:
   Open a terminal and navigate to the directory containing the `MainMenu.java` file. Then, compile the Java program using the following command:

   ```
   javac EmployManagementSystem.java
   ```

2. **Run the Program**:
   To run the program, use the following command:

   ```
   java EmployManagementSystem
   ```

   This will display the menu with the following options:

   ```
   Press 1 : To Add an Employee Details
   Press 2 : To See an Employee Details
   Press 3 : To Remove an Employee
   Press 4 : To Update Employee Details
   Press 5 : To Exit the EMS Portal
   ```

3. **Select an Option**:

   * Enter the option number corresponding to the action you want to perform.
   * For adding, viewing, or removing an employee, you will be prompted to enter additional details (like employee ID).
   * For updating, you’ll need to provide the field to be updated and the new value.

4. **Exit the Program**:
   To exit the program, select option 5 and the system will print a thank-you message.

## Example

### Adding an Employee

* Select **1** to add a new employee.
* Enter the employee's details when prompted.
* The system will save the details in a text file.

### Viewing an Employee

* Select **2** and enter the employee ID to view their details.

### Removing an Employee

* Select **3** and enter the employee ID to remove their details.

### Updating an Employee

* Select **4** and enter the employee ID, followed by the field you want to update (e.g., Name, Email).
* Enter the updated information when prompted.

### Exiting the Program

* Select **5** to exit the system and display a thank-you message.

## File Structure

* The program creates text files for each employee in the format: `file<employee_id>.txt`.
* Each text file contains the following employee details:

  * Employee ID
  * Name
  * Father's Name
  * Email
  * Position
  * Contact Info
  * Salary

## Code Structure

* **MainMenu.java**: Displays the menu options for the user.
* **Employee\_Add.java**: Handles adding new employee details.
* **Employee\_Show\.java**: Handles displaying employee details.
* **Employee\_Remove.java**: Handles removing an employee’s record.
* **Employee\_Update.java**: Handles updating an employee’s details.
* **CodeExit.java**: Handles the system exit and displays a thank you message.
* **EmployManagementSystem.java**: The main entry point of the program, where the menu is displayed and the user input is handled.

## Contributions

If you have suggestions or improvements, feel free to fork the repository, make changes, and submit a pull request.

## License

This project is open-source. Feel free to use and modify the code for educational purposes.

## Contact

For any queries or issues, contact **Romish Yadav** (developer).
