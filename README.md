# AirBnB_clone
Welcome to the AirBnB clone project!

# AirBnB Clone - The Console

## Table of Contents
- [Introduction](#0x01-introduction)
- [Environment](#0x02-environment)
- [Installation](#0x03-installation)
- [Testing](#0x04-testing)
- [Usage](#0x05-usage)
- [Additional Improvements](#0x06-additional-improvements)
- [Authors](#-authors)

## 0x01 Introduction
Team project to build a clone of AirBnB.

The console is a command interpreter to manage objects abstraction between objects and how they are stored.


The console will perform the following tasks:

- Create a new object
- Retrieve an object from a file
- Do operations on objects
- Destroy an object

**Storage:**
All the classes are handled by the Storage engine in the FileStorage Class.

## 0x02 Environment
- **Terminal:** Suite CRM terminal
- **Programming Language:** Python 3.10.12
- **Editors:** VIM 9.1.2269, VSCode 1.8.6, Atom 1.58.0
- **Version Control:** Git 2.43.0

**Style Guidelines:**
- Pycodestyle (version 2.8.*)
- PEP8

## 0x03 Installation
```bash
git clone https://github.com/K-tosh/AirBnB_clone.git
cd AirBnB_clone
./console.py
```

## 0x04 Testing
All tests are defined in the `tests` folder.

**Documentation:**
- Modules: `python3 -c 'print(__import__("my_module").__doc__)'`
- Classes: `python3 -c 'print(__import__("my_module").MyClass.__doc__)'`
- Functions: `python3 -c 'print(__import__("my_module").my_function.__doc__)'`

**Python Unit Tests:**
- Unittest module
- File extension: .py
- Files and folders start with test_
- Organization: for `models/base.py`, unit tests in: `tests/test_models/test_base.py`
- Execution command: `python3 -m unittest discover tests`

## 0x05 Usage
**Start the console in interactive mode:**
```bash
$ ./console.py
(hbnb) help
```

**Commands:**
- `create`: Creates a new instance of a given class.
- `show`: Retrieves and displays information about an instance.
- `destroy`: Deletes an instance of a given class.
- `all`: Prints all instances of a given class.
- `count`: Prints the number of instances of a given class.
- `update`: Updates an instance based on the class name, id, and kwargs passed.

**Examples:**
```bash
$ ./console.py
(hbnb) create BaseModel
6cfb47c4-a434-4da7-ac03-2122624c3762
(hbnb) show BaseModel 6cfb47c4-a434-4da7-ac03-2122624c3762
(hbnb) destroy User 0c98d2b8-7ffa-42b7-8009-d9d54b69a472
(hbnb) all BaseModel
(hbnb) update User 1afa163d-486e-467a-8d38-3040afeaa1a1 email "ericmusanyi8@gmail.com"
```


## Authors
Eric Lugaya Musanyi
```
