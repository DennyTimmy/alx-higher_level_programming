This README file is for the Python - Input/Output project
In this project, I practiced file handling in Python

Function Prototypes
Prototypes for functions written in this project:

File	Prototype
0-read_file.py	def read_file(filename=""):
1-number_of_lines.py	def number_of_lines(filename=""):
2-read_lines.py	def read_lines(filename="", nb_lines=0):
3-write_file.py	def write_file(filename="", text=""):
3-to_json_string.py	def to_json_string(my_obj):
2-append_write.py	def append_write(filename="", text=""):
4-from_json_string.py	def from_json_string(my_str):
5-save_to_json_file.py	def save_to_json_file(my_obj, filename):
6-load_from_json_file.py	def load_from_json_file(filename):
8-class_to_json.py	def class_to_json(obj):
12-pascal_triangle.py	def pascal_triangle(n):
100-append_after.py	def append_after(filename="", search_string="", new_string=""):
Tasks
0. Read file

o 0-read_file.py: Python function that prints the contents of a UTF8 text file to standard output.

1. Write to a file

o 1-write_file.py: Python function that writes a string to a UTF8 text file and returns the number of characters written.

2. Append to a file

o 2-append_write.py: Python function that appends a string to the end of a UTF8 text file and returns the number of characters appended.

3. To JSON string

o 3-to_json_string.py: Python function that returns the JSON string representation of an object.

4. From JSON string to Object

o 4-from_json_string.py: Python function that returns the Python object represented by a JSON string.

5. Save Object to a file

o 5-save_to_json_file.py: Python function that writes an object to a text file using JSON representation.

6. Create object from a JSON file

o 6-load_from_json_file.py: Python function that creates an object from a .json file.

7. Load, add, save

o 7-add_item.py: Python script that stores all command line arguments to a Python list saved in the file add_item.json.

8. Class to JSON

o 8-class_to_json.py: Python function that returns the dictionary description for simple Python data structures (lists, dictionaries, strings, integers and booleans).

9. Student to JSON

o 9-student.py: Python class Student that defines a student. Includes:

   Public instance attributes first_name, last_name, and age.

   Instantiation with first_name, last_name, and age: def __init__(self, first_name, last_name, age):.

   Public method def to_json(self): that returns the dictionary representation of a Student instance.
10. Student to JSON with filter

o 10-student.py: Python class Student that defines a student. Builds on 11-student.py with:

   Public method def to_json(self, attrs=None): that returns the dictionary representation of a Student instance.

   If attrs is a list of strings, only the attributes listed are represented in the dictionary.
11. Student to disk and reload

o 11-student.py: Python class Student that defines a student. Builds on 12-student.py with:

   Public method def reload_from_json(self, json): that replaces all attributes of the Student instance using the key/value pairs listed in json.
 The method assumes json is a dictionary containing attributes with name/value corresponding to key/value.

12. Pascal's Triangle

o 12-pascal_triangle.py: Python function that returns a list of lists of integers representing Pascal's triangle of size n.

o Assumes the size parameter n is an integer.

o If n is less than or equal to 0, returns an empty list.

13. Search and update

o 100-append_after.py: Python function that inserts a line of text to a file after each line containing a specified string.

14. Log parsing

o 101-stats.py: Python script that reads lines from standard input. After every 10 lines or the input of a keyboard interruption (CTRL + C), computes the following metrics:

   Total file size up that point: File size: <total size>

   Status code of each read line, printed in ascending order: <status code>: <number>
o Input format: - [] "GET /projects/260 HTTP/1.1"
