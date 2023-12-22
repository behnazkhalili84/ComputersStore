Computer Store Management System

This repository contains a Java program for managing a computer store's inventory. The program allows the computer store owner to add new computers, update information about existing computers, display computers by brand, display computers under a certain price, and quit the application.
Assignment Purpose

The assignment aims to reinforce concepts related to classes, loops, arrays, arrays of objects, static attributes, and static methods. It involves designing and implementing a Computer class with specific functionalities, including initialization, modification, display, and comparison of computer objects.
Part A: Computer Class

The Computer class is designed to represent individual computers in the inventory. It includes constructors for initialization, accessor and mutator methods for attribute modification, a toString method for displaying information, a method to find the number of created computers, and an equals method for object comparison.
Part B: Computer Store Management System

The driver program, named ComputerStoreManagementSystem, serves as the main application. It prompts the user for the maximum number of computers the store can contain, creates an empty array for inventory, and displays a menu with options for different operations.

    Enter New Computers (Password Required):
        Requires a password for access.
        Allows the owner to enter new computers with details such as brand, model, serial number, and price.

    Change Information of a Computer (Password Required):
        Requires a password for access.
        Allows the owner to update information about a specific computer, including brand, model, serial number, and price.

    Display All Computers by a Specific Brand:
        Prompts the user to enter a brand name.
        Displays information for all computers with the specified brand.

    Display All Computers Under a Certain Price:
        Prompts the user to enter a price value.
        Displays information for all computers with a price lower than the entered value.

    Quit:
        Ends the application with a closing message.
