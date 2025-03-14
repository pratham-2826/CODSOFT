# CODSOFT
Task 1 Contact Book

Overview: This program is of a Contact Book where the user can Choice yo Add and View a Contact on a computer. This prompts the user to choose Number then randomly they can Add Contact View Search Update and Delete Contact on computer and it Display Contact by a Contact Book

The Code Explanation

1. We create an empty dictionary contacts to store contacts.
2. We define five functions: add_contact, view_contacts search_contact update_contact and delete_contact.
3. The add_contact function takes in a name, phone number, and email address, and adds the contact to the contacts dictionary.
4. The view_contacts function prints out all the contacts in the contacts dictionary.
5. The search_contact function takes in a name and searches for the contact in the contacts dictionary. If found, it prints out the contact's details.
6. The update contact update the detail in the contact details.
7. the delete contact delete the contact in the cantact details.
8. The main program uses a while loop to repeatedly display a menu and ask the user for their choice.
9. Based on the user's choice, the program calls the corresponding function (add_contact, display_contacts, or search_contact).

Example Use Cases
1. Adding a new contact: Enter 1 in the menu, and then enter the name, phone number, and email address of the contact.
2. Viewing all contacts: Enter 2 in the menu.
3. Searching for a contact: Enter 3 in the menu, and then enter the name of the contact to search for.
4. Updateding a contact Enter 4 in the menu and enter the details and the contact updated.
5. Delete a contact Enter 4 in the menu and select the contact and delete.
6. Exit.


**Task 2**
 Calculator 

Overview:
This program is a calculator that can perform basic arithmetic operations such as addition, subtraction, multiplication, and division. It prompts the user to input two numbers and choose an operation, then performs the calculation and displays the result.

**Code Explanation:**

1. get_numbers Function:
- Prompts the user to input two numbers.
- Validates the input to ensure only numbers are entered.
- Returns the two numbers.

2. choose_operation Function:
- Prompts the user to choose an arithmetic operation (addition, subtraction, multiplication, or division).
- Validates the input to ensure a valid operation is chosen.
- Returns the chosen operation.

3. perform_calculation Function:
- Takes two numbers and an operator as arguments.
- Performs the chosen arithmetic operation.
- Handles division by zero error.
- Returns the result of the calculation.

4. main Function:
- Welcomes the user to the calculator.
- Repeatedly performs calculations until the user decides to quit.
- Calls the above functions to get numbers, choose an operation, and perform the calculation.
- Displays the result.
- Asks the user if they want to perform another calculation.
- Thanks the user when they decide to quit.

**Example Usage:**
- Input two numbers: 10 and 5.
- Choose an operation: + (addition).
- Output: Result: 15.




**Task 3**
Password Genrator

Overview: This program generates a random password of a specified length. The password includes a mix of lowercase and uppercase letters, digits, and punctuation characters to ensure it is strong and secure.

Code Explanation:

Function Definition:
--Purpose: To generate a random password. --Details: The function generate_password takes one argument, length, which specifies the desired password length.

Length Check:
--Purpose: To ensure the password is long enough. --Details: The function raises an error if the password length is less than 4 to ensure it can include at least one of each character type: lowercase, uppercase, digit, and punctuation.

Character Sets:
--Purpose: To define possible characters for the password. --Details: The function combines all letters, digits, and punctuation characters into a single string for random selection.

4.Ensuring Character Variety:

--Purpose: To include at least one of each character type. --Details: The function ensures that the password includes one lowercase letter, one uppercase letter, one digit, and one punctuation mark.

Filling the Password:
--Purpose: To complete the password to the desired length. --Details: The function randomly selects additional characters from the combined set until the desired length is reached.

Randomizing Order:
--Purpose: To ensure the password is randomized. --Details: The password list is shuffled to randomize the order of characters.

Returning the Password:
--Purpose: To output the final password. --Details: The list of characters is joined into a string and returned as the final password.

Example Usage:

Generates a password of desired length 0 to exit  and prints it





