

File Handling in Python

Overview

This project demonstrates basic file handling operations in Python through two tasks:

1. Reading from a File and Handling Errors


2. Writing to and Appending Data in a File



These tasks are designed to help beginners understand how to work with text files in Python, including reading, writing, appending, and handling file-related errors.


---

Task 1: Read a File and Handle Errors

Functionality:

Opens and reads a text file named sample.txt.

Prints each line of the file with line numbers.

Gracefully handles the case when the file does not exist, by displaying an error message.


Example Output:

If sample.txt exists:

Reading file content:
Line 1: This is a sample text file.
Line 2: It contains multiple lines.

If sample.txt does not exist:

Error: The file 'sample.txt' was not found.


---

Task 2: Write and Append Data to a File

Functionality:

Takes input from the user and writes it to output.txt.

Appends additional user input to the same file.

Finally reads and displays the content of output.txt.


Example Output:

Enter text to write to the file: Hello, Python!
Data successfully written to output.txt.

Enter additional text to append: Learning file handling in Python.
Data successfully appended.

Final content of output.txt:
Hello, Python!
Learning file handling in Python.


---

How to Run

1. Make sure you have Python installed.


2. Run the Python files for each task:

python task1.py for reading from file

python task2.py for writing/appending data



3. Follow the on-screen prompts.




---

Requirements

Python 3.x

No external libraries required


