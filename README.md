#COP3330C Module 1 Programming Assignment

In this module we have learned about Agile practices and associated development frameworks, one of which was Scrum. 

For this assignment you will create a Java Scrum Workflow Manager application which will simulate simple Scrum workflow example. The assignment will allow you to use Java techniques from this module as well as reinforce foundational Scrum concepts.

The application must include the following classes:

	- A class representing a Scrum team member. The class must include the following private fields:
		- a unique ID that can be used as a database key
		- a last name field
		- a first name field
		- a role that is represented by an enum type with the following values: product owner, scrum team master, developer, QA tester, architect 
		- an object reference to their team. 
		Provide all necessary constructors, mutators, and accessors (the id field is read-only, do not provide a mutator for it).
        	Provide a toString method which returns a String containing the team member's state.
	- A class which represents a Scrum team with various members. The team members must be stored in an ArrayList.
	- A ScrumWorkflowManager class which contains a main method that acts as the primary application driver. 

Your application should log the team's creation, including project name and team members by name and role (refer to the sample output included below).

Sample output:  
Welcome to the Scrum Workflow Manager  
Team Creation: Team formed for Scrum Workflow Manager  
Team Member 1: Bill Bixby, Role: Product Owner  
Team Member 2: Hulk Hogan, Role: Scrum Team Master  
Team Member 3: Anthony Stark, Role: Developer  
Team Member 4: Thor Odinson, Role: QA Tester  
Team Member 5: Harry Cleese, Role: Architect  
