# Orphanage-System-Backend
The aim of the project is to create an orphanage management system that would enable adding or deleting members, tracking their personal details, updating their details, and give feedback which would help maintain the records properly.

# FILES USED
Add1.CSV

Add2.CSV

feedback.CSV

marks.CSV

# CLASSES
1. class Add
In this class there are a set of functions for adding child and adult members to their respective files.

2. class Existence
This class contains a set of functions for viewing, updating, and deleting details of existing members.

3. class Track
This class helps in tracking of details of all members by the maintenance department (admin staff)

4. class Feedback
This class serves as a platform for the maintenance department to communicate details pertaining to a member.

5. class Bind
This is a derived class that inherits the properties of all the previously defined classes, binding the methods in one master unit

# FUNCTIONS:
**1. Under class Add**

a) __init__(): Constructor function

b) addChild(): writes the details of child members into the respective file.

c) addAdult(): writes the details of adult members into the respective file.

**2. Under class Existence**

a) View(): Displays details of existing members

b) Upadatechild(): Updates the values of certain arguments of a child member

c) Updateadult() : Updates the values of certain arguments of an adult member

d) Deletechild() : Deletes all the data of a child member

e) Deleteadult() : Deletes all the data of an adult member.

**3. Under class Track**

a) track(): Helps in accessing the data of particular member.

**4. Under class Feedback**

a) __init__() : Constructor function

b) inp() : Helps the admin staff to enter and store the feedback of a child.

c) marks() : Helps the admin staff to enter and store the marks of a child.

d) displayinp() : Displays the stored details of feedback.

e) displaymarks(): Displays the stored details of marks

**5. Under class Bind**

Contains all the previously mentioned functions of the classes mentioned above since this is a derived class.

# Get Started:
Clone this repository and add the relevant files used to get the orphanage management system up and running.
