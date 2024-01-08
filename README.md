0x00. AirBnB clone - The console


# AirBnB Clone Console - Overview

![AirBnB Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Airbnb_Logo_B%C3%A9lo.svg/1280px-Airbnb_Logo_B%C3%A9lo.svg.png)

## Project Description

This project marks the initial phase of constructing a comprehensive web application that mirrors the fundamental features of the widely used Airbnb platform. In this preliminary stage, the primary focus is on crafting a command-line interpreter (CLI) designed to manage Airbnb objects. This project forms the groundwork for subsequent development endeavors, encompassing HTML/CSS templating, database storage, API integration, and front-end design.

## Command Interpreter Overview

The command interpreter, which is implemented within `console.py`, acts as a versatile utility for interaction with and control of Airbnb objects. It empowers users to carry out various actions on these objects, encompassing their creation, retrieval, modification, and removal. The interpreter adopts a Shell-like interface and provides a set of commands for manipulation of Airbnb objects.

## Getting Started

To commence using the Airbnb Clone command interpreter, adhere to these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/AirBnB_clone.git
   ```

2. Navigate to the project directory:

   ```bash
   cd AirBnB_clone
   ```

3. Launch the command interpreter:

   ```bash
   ./console.py
   ```

## Usage Instructions

Once the command interpreter is up and running, you can employ the following commands to administer Airbnb objects:

- `create`: Generate a new Airbnb object (e.g., User, State, City, Place).
  Example:
  ```bash
  (hbnb) create User
  ```

- `show`: Retrieve details about a particular object by specifying its class name and ID.
  Example:
  ```bash
  (hbnb) show User 1234-5678-9012
  ```

- `all`: List all objects of a given class or list all objects if no class is specified.
  Example:
  ```bash
  (hbnb) all
  (hbnb) all State
  ```

- `update`: Modify attributes of an object by specifying its class name, ID, attribute name, and attribute value.
  Example:
  ```bash
  (hbnb) update User 1234-5678-9012 first_name "John"
  ```

- `destroy`: Erase an object by specifying its class name and ID.
  Example:
  ```bash
  (hbnb) destroy Place 9876-5432-1098
  ```

- `quit` or `EOF`: Exit the command interpreter.
  Example:
  ```bash
  (hbnb) quit
  ```

- `help`: Present a list of available commands or request assistance for a specific command.
  Example:
  ```bash
  (hbnb) help
  (hbnb) help show
  ```

## Usage Examples

Here are some examples of how to employ the Airbnb Clone command interpreter:

1. Create a new User object:
   ```bash
   (hbnb) create User
   ```

2. List all City objects:
   ```bash
   (hbnb) all City
   ```

3. Update the name attribute of a Place object:
   ```bash
   (hbnb) update Place 1234-5678-9012 name "Cozy Cabin"
   ```

4. Delete a State object:
   ```bash
   (hbnb) destroy State 9876-5432-1098
   ```

5. Exit the command interpreter:
   ```bash
   (hbnb) quit
   ```

The Airbnb Clone command interpreter furnishes a user-friendly approach to administer and manipulate Airbnb objects, establishing itself as an indispensable tool for the development of the full-featured Airbnb clone web application.
