# PRODIGY_SD_03

Develop a program that allows users to store and manage contact information. The program should provide options to add a new contact by entering their name, phone number, and email address. It should also allow users to view their contact list, edit existing contacts, and delete contacts if needed. The program should store the contacts in memory or in a file for persistent storage.

explanation:
Main Components:
Contact List Initialization:

An empty array is initialized to store the contacts.
Adding a Contact:

Prompts the user to enter the contact's name, phone number, and email address.
Creates a contact object with the provided details and adds it to the contact list.
Confirms that the contact was added successfully.
Viewing Contacts:

Checks if there are any contacts in the list.
If there are contacts, it displays each contact's details (name, phone, email) with an index number.
If the list is empty, it notifies the user that there are no contacts.
Editing a Contact:

Checks if the contact list is empty.
Prompts the user to enter the name of the contact they want to edit.
Searches for the contact by name.
If the contact is found, prompts the user to enter new phone and email information and updates the contact.
Confirms that the contact was updated, or notifies if the contact was not found.
Deleting a Contact:

Checks if the contact list is empty.
Prompts the user to enter the name of the contact they want to delete.
Searches for the contact by name.
If the contact is found, removes it from the contact list.
Confirms that the contact was deleted, or notifies if the contact was not found.
Saving Contacts to a File:

Converts the contact list to a string format suitable for saving to a file.
This is a placeholder function since actual file handling requires a server or browser's file API.
Prints a message indicating that contacts have been saved (for demonstration purposes).
Loading Contacts from a File:

Loads contacts from a predefined set of data for demonstration.
This is a placeholder function since actual file handling requires a server or browser's file API.
Prints a message indicating that contacts have been loaded (for demonstration purposes).
Main Program Loop:

Loads contacts from a file (using placeholder data).
Continuously displays a menu with options to add, view, edit, delete, save, and exit.
Prompts the user to enter a choice and executes the corresponding function.
If the user chooses to save and exit, the program saves the contacts and terminates.
If the user enters an invalid choice, it prompts them to try again.
