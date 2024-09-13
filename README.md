# AirBnB Clone - Command-Line Interface

This is the initial phase of creating a full-stack replica of the AirBnB web application. The objective of this project is to develop a command-line interface that can manage various entities such as users, locations, and cities. This CLI will act as a basic tool for data management and will pave the way for future enhancements involving HTML/CSS, API development, and database integration.

## Command-Line Interface

The command-line interface is a shell-like application for managing AirBnB entities.

### How to Launch It

Execute the following command in your terminal:
```bash
./console.py
```
This command will start an interactive prompt where you can input commands to handle your entities.


### How to Use It

Once you are in the command-line interface, you can perform these operations:

- Create a new object (ex: a new User or a new Place)

```bash
(hbnb) create User
```
- Retrieve an object from a file, database, etc.

```bash
(hbnb) show User 1234-1234-1234
```
- Update an object (ex: change the name of a City)

```bash
(hbnb) update City 1234-1234-1234 name "San Francisco"
```
- Destroy an object

```bash
(hbnb) destroy User 1234-1234-1234
```
- Quit the program

```bash
(hbnb) quit
```

### Supported Entities

The command-line interface supports the following entities:

- User
- City
- State
- Amenity
- Place
- Review
