# Various add-on actions for todo.sh from http://todotxt.com

## hamster action

### Usage

```
todo.sh hamster 42
```
Starts registering task #42 in Hamster Time Tracker.

### Changelog

#### v1.0 (10/01/2017)

- Cut off the creation date
- Prints the task before exiting

#### v1.1 (11/01/2017)

Handle hamster tags

#### v1.2 (11/01/2017)

Replaces "," with " " in task

## addpri action

### Usage

```
todo.sh addpri A Make the world happy due:now +BigProject @Dream
```
Creates the task "Make the world happy due:now +BigProject @Dream" with priority set to A.

### Changelog

#### v1.0 (11/01/2017)

Tests if priority is set before prioritization.

## startadd action

### Usage

```
todo.sh startadd A Make the world happy due:now +BigProject @Dream
```
Creates the task "Make the world happy due:now +BigProject @Dream" with priority set to A and starts the task in Hamster Time Tracker.

Depends on ''hamster'' action.

### Changelog

#### v1.0 (11/01/2017)

Test if priority is set before prioritization.
Starts the task in Hamster Time Tracker.

