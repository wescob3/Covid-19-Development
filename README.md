# Covid19Development
A project created using javascript, Java, MySql and HTML5.

Functionalities:

The patient's personal information is collected (name, DOB, age, ID). Every time a patient takes a covid test the results of that person and his personal information are saved to track the development of the pandemic. If a person has covid the date of the diagnosis is saved as well as the date of when that person started to feel sick. When a patient comes to a specific hospital to take a covid vaccine an appointment is automatically made for that person to ensure that the person has received the necessary doses according to the vaccine taken(Pfizer, Moderna, AstraZeneca, etc..).
The status of the person that has taken a vaccine can be first_dose, second_dose (even third dose for some vaccines), or fully vaccinated. The hospital's information such as an address, name, director's name, is necessary to attach when submitting data from a specific hospital in the United States.

# Implementation details

Import the "project.war" file into eclipse and import the "initializeDB" file in mySQL workbench. Apache is used as a server in eclipse. In the Dao files the username and password of the SQL project must be changed. Once everything is set up you have to run the file on an apache server.

