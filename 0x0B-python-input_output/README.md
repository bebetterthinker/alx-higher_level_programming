# _**0x0B. Python - Input/Output_**
_ _ _
In this project, I practiced file handling in Python. I used the builtin `with`, `open`, and `read` functions with the `json` module to read and write files and serialize and deserialize objects with JSON.


## **Function Prototypes**

<p>Prototypes for functions written in this project:</p>
<table border='1'>
  <tr>
    <th>File </th>
    <th> Prototype</th>
  </tr>
  <tr>
    <td>0-read_file.py</td>
    <td>def read_file(filename=""):</td>
  </tr>
  <tr>
    <td>1-number_of_lines.py</td>
    <td>def number_of_lines(filename=""):</td>
  <tr>
    <td>2-read_lines.py</td>
    <td>def read_lines(filename="", nb_lines=0):</td>
  </tr>
  <tr>
    <td>3-write_file.py</td>
    <td>def write_file(filename="", text=""):</td>
  </tr>
   <tr>
    <td>2-append_write.py</td>
    <td>def append_write(filename="", text=""):</td>
  </tr>
  <tr>
    <td>3-to_json_string.py</td>
    <td>def to_json_string(my_obj):</td>
  <tr>
    <td>4-from_json_string.py</td>
    <td>def from_json_string(my_str):</td>
  </tr>
  <tr>
    <td>5-save_to_json_file.py</td>
    <td>def save_to_json_file(my_obj, filename):</td>
  </tr>

  <tr>
    <td>6-load_from_json_file.py</td>
    <td>def load_from_json_file(filename):</td>
  </tr>
  <tr>
    <td>8-class_to_json.py</td>
    <td>def class_to_json(obj):</td>
  </tr>
  <tr>
    <td>d12-pascal_triangle.py</td>
    <td>def pascal_triangle(n):</td>
  </tr>
  <tr>
    <td>100-append_after.py</td>
    <td>def append_after(filename="",search_string=""</td>
  </tr>
</table>

## __task w ill solve in this project include the following tasks__

* _task -->_ **0. Read file**
  * [0-read_file.py](./0-read_file.py): Python function that prints the contents of a UTF8 text file to standard output.
_ _ _
* _task -->_  **1. Write to a file**
  _ _ _
  * Python function that writes a string to a UTF8 text file and returns the number of characters written.

* _task -->_  **2. Append to a file**
  _ _ _
  * Python function that appends a string to the end of a UTF8 text file and returns the number of characters appended.

* _task -->_  **3. To JSON string**
  _ _ _
  *  Python function that returns the JSON string representation of an object.

* _task -->_  **4. From JSON string to Object**
  _ _ _
  *  Python function that returns the Python object represented by a JSON string.

* _task -->_  **5. Save Object to a file**
  _ _ _
  *  Python function that writes an object to a text file using JSON representation.

* _task -->_  **6. Create object from a JSON file**
  _ _ _
  *  Python function that creates an object from a `.json` file.

* _task -->_  **7. Load, add, save**
  _ _ _
  *  Python script that stores all command line arguments to a Python list saved in the file `add_item.json`.

* _task -->_  **8. Class to JSON**
  _ _ _
  *  Python function that returns the dictionary description for simple Python data structures (lists, dictionaries, strings, integers and booleans).

* _task -->_  **9. Student to JSON**
  _ _ _
  * Python class `Student` that defines a student. Includes:
    * Public instance attributes `first_name`, `last_name`, and `age`.
    * Instantiation with `first_name`, `last_name`, and `age`: `def __init__(self, first_name, last_name, age):`.
    * Public method `def to_json(self):` that returns the dictionary representation of a `Student` instance.

* _task -->_  **10. Student to JSON with filter**
  _ _ _
  *  Python class `Student` that defines a student.
    * Public method `def to_json(self, attrs=None):` that returns the dictionary representation of a `Student` instance.
    * If `attrs` is a list of strings, only the attributes listed are represented in the dictionary.

* _task -->_  **11. Student to disk and reload**
  _ _ _
  *  Python class `Student` that defines a student.
    * Public method `def reload_from_json(self, json):` that replaces all attributes of the `Student` instance using the key/value pairs listed in `json`.
    * The method assumes `json` is a dictionary containing attributes with name/value corresponding to key/value.

*_task -->_  **12. Pascal's Triangle**
_ _ _
  *  Python function that returns a list of lists of integers representing Pascal's triangle of size `n`.
  * Assumes the size parameter `n` is an integer.
  * If `n` is less than or equal to `0`, returns an empty list.

*_task -->_  **13. Search and update**
 _ _ _
  *  Python function that inserts a line of text to a file after each line containing a specified string.

* _task -->_  **14. Log parsing**
  _ _ _
  * Python script that reads lines from standard input. After every 10 lines or the input of a keyboard interruption (`CTRL + C`), computes the following metrics:
    * Total file size up that point: `File size: <total size>`
    * Status code of each read line, printed in ascending order:  `<status code>: <number>`
  * Input format: `<IP Address> - [<date>] "GET /projects/260 HTTP/1.1"
  <status code> <file size>`

