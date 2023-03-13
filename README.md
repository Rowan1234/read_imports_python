# read_imports_python
A file for reading all your imports in a directory and then putting them in 1 requirements file.

Steps:

1. put file into directory
2. run
3. you now have a requirements.txt with every .py file import
4. you can run: "pip install -r requirements.txt" to install all imports you will need for that directory

# Warning!
there are cases where the import statements can make the script dysfunctional, such as:
- importing thing from package
- importing name is not package name
- importing something that is pre-installed ie: os
- etc.
