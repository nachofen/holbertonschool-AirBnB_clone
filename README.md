![Logo](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230706%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230706T184223Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=4f302852e92a588dd5de315c34b523f8a1ee4347d65710fc388c798832c25975)


# AirBnB clone - The console
Below is a brief description of our first console project in Python!

## description of the project
The project consists of writing a command interpreter to manage your AirBnB objects.
This is the first step in creating your first full web app – the AirBnB clone.

This first step is very important because it will integrate what we built during this project with all the other projects that follow:
HTML/CSS templates, database storage, API, front-end integration...

## description of the command interpreter:
This repository contains the Airbnb console clone.

It is a command interpreter:
The command interpreter, like a shell, can take input from the user and perform certain tasks to manipulate object instances.

It is also an interpreter of classes:
The BaseModel class and several other classes that inherit from it: Amenity, City, State, Place, Review

### how to start it
For installation: clone a follow repository
```
https://github.com/toleman84/holbertonschool-AirBnB_clone.git
```

### how to use
| Commands   | Functionality                                |
| ---------  | -------------------------------------------- |
| `help`     | displays all commands available              |
| `create`   | creates a new object (ex. a new User, Place) |
| `update`   | updates attribute of an object               |
| `destroy`  | destroys specified object                    |
| `show`     | retrieve an object from a file, a database   |
| `all`      | display all objects in class                 |
| `quit`     | exit the console                             |

### examples
```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
-========================================
EOF  help  quit

(hbnb) 
```

- But also in non-interactive mode: (like the Shell project in C)
```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
```

## Authors
- [@nachofen](https://github.com/nachofen)
- [@Hiojam](https://github.com/Hiojam)
- [@toleman84](https://github.com/toleman84)
