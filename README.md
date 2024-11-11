# File Systemm Management:searching and sorting techiques
This C++ application is a simple file management system that allows users to store, search, sort, and manipulate files within a list. Each file is represented by a File object that holds a name and size in kilobytes. The system supports various operations such as adding, deleting, displaying, searching, and sorting files. The core features of the application include:

Linear Search: Search for a file by its name using a simple linear search algorithm.
Binary Search: Search for a file by its name using a binary search algorithm (requires sorted list).
Sorting: Sort files by their name or size using the QuickSort algorithm.
Add New File: Add a new file to the list with its name and size.
Delete File: Delete a file from the list by its name.
Features
Display Files: Lists all the files with their name and size in kilobytes.
Linear Search: Allows the user to search for a file by its name using a linear search.
Binary Search: Allows the user to search for a file by its name using a more efficient binary search (requires sorted list).
Sorting: The user can sort files either by name or by size using the QuickSort algorithm.
Add New File: Users can add a new file with a specified name and size to the list.
Delete File: Allows users to delete a file from the list by its name.
Key Functions:
File Class: Represents a file with a name and size (in KB). The class has a constructor to initialize the file and a display() method to print the file’s details.
Search Functions:
linearSearch(): Performs a linear search to find a file by name.
binarySearch(): Performs a binary search to find a file by name (after sorting the list).
Sorting:
quickSort(): Sorts the files by name or size using the QuickSort algorithm. The sorting method is determined by the user's choice.
Menu System: A menu-driven interface allows users to select different operations to interact with the file list.
