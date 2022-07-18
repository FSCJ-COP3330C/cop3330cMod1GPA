### COP3330C Module 1 Programming Assignment

In this module we have learned about Agile practices and associated development frameworks, one of which was Scrum. 
For this assignment you will create a Java Scrum Workflow Manager application. The assignment will allow you to use Java techniques from this module as well as reinforce the foundational Scrum concepts.

The application will include classes for the Scrum Master, the Product Owner, and members of the development team with roles of Developer, QATester, and System Architect (read the following instructions closely so you do this correctly).

A **ScrumWorkflowManager** class should contain a main method which acts as the primary application driver. 
The development team is cross-functional; any development team member can assume a different role over time (note: Product Owner and Scrum Master are not interchangeable). **Create a  superclass for the team members with private member variables using their last name and first name. Create subclasses which represent the team member roles. Create a ScrumTeam class which contains a private ArrayList member variable  which stores instances of a Scrum team members.**

Your application should create the following team your ScrumTeam class containing instances of the following members:
•	Product Owner  
•	Scrum Master  
•	Developer  
•	QATester  
•	System Architect  

**Sample output:**

Welcome to the Scrum Workflow Manager  
    Team Creation: Team formed for Scrum Workflow Manager  
    Product Owner: Bill Bixby  
    Scrum Master: Hulk Hogan  
    Team Member 1: Anthony Stark, Role: Developer  
    Team Member 2: Luke Charles, Role: Developer  
    Team Member 3: Thor Odinson, Role: QA Tester  
    Team Member 4: Harry Cleese, Role: System Architect  
