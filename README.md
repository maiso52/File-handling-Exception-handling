📖 File Read & Write + Error Handling Program
🚀 Overview

This Python program demonstrates how to:

Read text from a file.

Modify the content (convert to uppercase).

Write the modified content to a new file.

Handle common errors like missing files or permission issues.

It’s a simple but practical exercise in file handling and error management.

📝 Features

Reads a user-specified file.

Converts the text to uppercase.

Writes the result to modified_output.txt.

Handles errors gracefully:

File not found

Permission errors

Any other unexpected error

⚙️ Usage

Make sure you have Python 3 installed.

Save the program as file_handler.py.

Run the program:

python file_handler.py


When prompted, enter the name of the file you want to read (e.g., input.txt).

If the file exists, the modified content will be saved in modified_output.txt.

📂 Example

Suppose input.txt contains:

Python is awesome.
File handling is important.


After running the program, modified_output.txt will contain:

Modified Content:
PYTHON IS AWESOME.
FILE HANDLING IS IMPORTANT.

🔐 Error Handling

If the file doesn’t exist → ❌ Error: The file 'input.txt' was not found.

If permission is denied → ❌ Error: You don't have permission to read 'input.txt'.

Any other error → Prints a general error message.
