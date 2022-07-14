#COP3330C Module 1 Programming Assignment

In this module we have learned about Agile practices and associated development frameworks, one of which was Scrum. 

For this assignment you will create a Java Scrum Workflow Manager application which will log events based on a simple workflow example. The assignment will allow you to use Java techniques from this module as well as reinforce the foundational Scrum concepts.

The application will include classes for the Scrum Master, the Product Owner, and members of the development team with roles of Developer, QATester, and System Architect (read the following instructions closely so you do this correctly).

A ScrumWorkflowManager class should contain a main method which acts as the primary application driver. 
The development team is cross-functional; any development team member can assume a different role as the timeline progresses (note: Product Owner and Scrum Master are not interchangeable). Create a  superclass for the team members, and use inheritance to represent the team member roles. Represent role changes using polymorphism.
Your application should track the team status on the workflow timeline by logging events which include the following:

    1. team creation (output: date/time stamp, project name, team members by name and role)
    2. hold the first daily scrum (meeting)  (output: date/time stamp, meeting purpose, attending members and roles)
    3. modify the roles of at least two team members (output: date/time stamp, list member names who have new roles and their roles)
    4. hold a second daily scrum (output: date/time stamp, list attending members and roles, including members with modified roles)

Design an Event class which is used to log events.

You can use an instance of the Instant object reference to simulate the passage of time.

Sample output:
2022-07-14T20:17:32.932889600Z: Welcome to the Scrum Workflow Manager
2022-07-16T20:17:32.944490100Z: EVENT: Team Creation: Team formed for Scrum Workflow Manager
2022-07-16T20:17:32.944490100Z:     Product Owner: Bill Bixby
2022-07-16T20:17:32.944490100Z:     Scrum Master: Hulk Hogan
2022-07-16T20:17:32.944490100Z:     Team Member 1: Anthony Stark, Role: Developer
2022-07-16T20:17:32.944490100Z:     Team Member 2: Luke Charles, Role: Developer
2022-07-16T20:17:32.944490100Z:     Team Member 3: Thor Odinson, Role: QA Tester
2022-07-16T20:17:32.944490100Z:     Team Member 4: Harry Cleese, Role: System Architect
2022-07-17T20:14:28.178329443Z: EVENT: Standup: Scrum Workflow Manager 1
2022-07-17T20:14:28.178329443Z:     Agenda Summary: Team Member Introduction, Project Overview
2022-07-17T20:14:28.178329443Z:     Attendees:
2022-07-17T20:14:28.178329443Z:     Product Owner: Bill Bixby
2022-07-17T20:14:28.178329443Z:     Scrum Master: Hulk Hogan
2022-07-17T20:14:28.178329443Z:     Team Member 1: Anthony Stark, Role: Developer
2022-07-17T20:14:28.178329443Z:     Team Member 2: Luke Charles, Role: Developer
2022-07-17T20:14:28.178329443Z:     Team Member 3: Thor Odinson, Role: QA Tester
2022-07-17T20:14:28.178329443Z:     Team Member 4: Harry Cleese, Role: System Architect
2022-07-18T20:09:17.089713224Z: EVENT: Role Modification
2022-07-18T20:09:17.089713224Z:     Team Member 3: Thor Odinson, Current Role: QA Tester, New Role: Developer
2022-07-18T20:17:32.089713224Z:     Team Member 3: Anthony Stark, Current Role: Developer, New Role: QA Tester
2022-07-20T20:14:27.676658132Z: EVENT: Standup: Scrum Workflow Manager 2
2022-07-20T20:14:27.676658132Z:     Agenda Summary: Purpose: Backlog Review
2022-07-20T20:14:27.676658132Z:     Attendees:
2022-07-20T20:14:27.676658132Z:     Product Owner: Bill Bixby
2022-07-20T20:14:27.676658132Z:     Scrum Master: Hulk Hogan
2022-07-20T20:14:27.676658132Z:     Team Member 1: Anthony Stark, Role: QA Tester
2022-07-20T20:14:27.676658132Z:     Team Member 2: Luke Charles, Role: Developer
2022-07-20T20:14:27.676658132Z:     Team Member 3: Thor Odinson, Role: Developer
2022-07-20T20:14:27.676658132Z:     Team Member 4: Harry Cleese, Role: System Architect