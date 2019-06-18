# Official Requirements Document

Authors: Amico Alessandro, Barberis Alessio, Barello Edoardo, Castrogiovanni Andrea, Marino Fulvio

Date:10/06/2019

Version: 1

# Contents
- [Abstract](#abstract)
- [Stakeholders](#stakeholders)
- [Context Diagram and interfaces](#context-diagram-and-interfaces)
	+ [Context Diagram](#context-diagram)
	+ [Interfaces](#interfaces) 
	
- [Stories and personas](#stories-and-personas)
- [Functional and non functional requirements](#functional-and-non-functional-requirements)
	+ [Functional Requirements](#functional-requirements)
	+ [Non functional requirements](#non-functional-requirements)
- [Use case diagram and use cases](#use-case-diagram-and-use-cases)
	+ [Use case diagram](#use-case-diagram)
	+ [Use cases](#use-cases)
	+ [Relevant scenarios](#relevant-scenarios)


# Abstract
Biologic farms cannot use chemicals to disinfect their own crops from pests that populate them ...
Our project allows the use of new technologies, that is, the release from a drone commanded of other insects (called insectivores) which eliminate the parasites in a natural and ecological way.
Furthermore TAKE OFF being a simulation program, it allows to practice driving the drone without causing structural damage that would affect the total cost.
# Stakeholders

| Stakeholder name  | Description | 
| ----------------- |:-----------:|
|Administrators| People who developed the project|
|Users| Biologic farms who used the program for the practice|
# Context Diagram and interfaces

## Context Diagram
|Administrators| People who developed the project|
|Users| Biologic farms who used the program for the practice
## Interfaces
| Actor | Logical Interface | Physical Interface  |
| ------------- |:-------------:| -----:|
|Administrators| GUI | Virtual Reality Kit| 

# Stories and personas
Marco is an employee of the Alce Nero organic farm. He is responsible for the production and defense of crops from pest attacks of harmful insects.
He also successfully completed the drone driving certification course for agricultural / food purposes. Marco, however, has decided that next year he will change his job, so he was joined by Paolo, a young colleague without certifications and experience driving a drone.Thanks to the take off project Paolo and anyone else with no experience on drone work can practice without increasing costs.

# Functional and non functional requirements

## Functional Requirements

| ID        | Description  |
| ------------- |:-------------:| 
|  FR1     |Drone flight simulation  |  
|  FR2     |Release of insectivorous agents|


## Non Functional Requirements

| ID        | Type (efficiency, reliability, .. see iso 9126)           | Description  | Refers to |
| ------------- |:-------------:| :-----:| -----:|
|  NFR1  |   Usability | Application should be used with no training by any colleague in the bio farms  | All FR |
|  NFR2    | Portability | The application (functions and data) should be portable from a PC to another PC in less than 5 minutes | All FR | 



# Use case diagram and use cases

## Use case diagram
left to right direction actor Administrator as a 
a-- (FR1 Flight simulation drone starts)
a-- (FR2 Release of insectivorous agents )
## Use Cases

### Use case 1, UC1 - FR1  Record usage of capsules by colleague

| Actors Involved        |Users |
| ------------- |:-------------:| 
|  Precondition     | Buy a computer, Buy take off, Install take off |  
|  Nominal Scenario     |Administrators sell Take off to the Users,who practice a simulation of a drone flight and a release of insectivouros agents |
|  Variants     | Computer doesn't support the program |



# Relevant scenarios

## Scenario 1

| Scenario ID: SC1        | Corresponds to UC1  |
| ------------- |:-------------| 
| Description | Administrators release take off |
| Precondition | Users buy take off  |
| Step#        |  Step description   |
|  1     | Administrators release take off| 
|  2     | Users buy take off |
|  3     | Users practice with the program |
| 4 | Users learn how to pilot a drone flight |

