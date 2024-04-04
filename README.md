# School Catalogue

This is a school project for my Intermediate Python 3 course at Codecademy. 

## Goal
The goal of this project is to put my knowledge of classes to the test by creating a digital school catalog.

## Project briefing

>We need to create classes for primary and high schools. 
>Because these classes share properties and methods, each will inherit from a parent School class. 
>Our parent and three child classes have the following properties, getters, setters, and methods.

### School
- **Properties:** name (string), level (one of three strings: 'primary', 'middle', or 'high'), and numberOfStudents (integer)
- **Getters:** all properties have getters
- **Setters:** the numberOfStudents property has a setter
- **Methods:** A __repr__ method that displays information about the school.

#### Primary
Includes everything in the School class, plus one additional property <br>
- **Properties:** pickupPolicy (string, like "Pickup after 3pm")

#### Middle
Does not include any additional properties or methods. <br>

#### High
Includes everything in the School class, plus one additional property.
- **Properties:** sportsTeams (list of strings, like ['basketball', 'tennis'])
