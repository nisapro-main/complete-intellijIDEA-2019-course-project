# complete-intellijIDEA-2019-course-project
					---------------------------------------------
					Intellij IDEA PROJECT DESCRIPTION
					---------------------------------------------

--------------------------------
 TITLE
-------------------------------- 
Online flight reservation system (server side)

--------------------------------
 OBJECTIVES
--------------------------------
To acquire practical experience with Intellij IDEA by applying the fundamental concepts and techniques taught in the course.
By the end of this project you'll be equiped with the skills and experience to tackle with confidence the use of Intellij IDEA on any real-world Software system!
 
--------------------------------
 DESCRIPTION
-------------------------------- 
The project consists of refactoring an existing, simplified server side sub-system of an online flight reservation system.
The main class of this sub-system is 'ReservationManager.Java'.

This main class is deliberately poorly designed. Use the powerful refactoring features of Intellij IDEA to improve the overall design and implementation of the sub-system.
Tip: One way that you can go about uncovering the design of your system is through implementing state based tests: let your Junit tests guide the design of your system. A simple way to do this is to reason about, desgin and implement the tests for your system and then refactor the production code.

Note: It's recommended that you create a github account if you don't have one so that you can fork this project. 
However this is optional: you can just download the entire project sources using the "zip" (for Windows) or "dmg" (for Mac).


-------------------------------- 
 COMPLETION STEPS
-------------------------------- 
1) Create the IJ project using the provided sources (see IJ course lesson X)
2) Write tests for at least the following scenarios (the more the better):
	3.1) Boundary conditions
	3.2) search flights use case with any permutation of the input parameters
	3.3) book use case with any permutation of the input parameters
	3.4) Loading of the CSV with different contents (empty, with return flights, with one-way flights only, etc)
3) Refactor the ReservationManager class to improve the overall design (DAO.java and Codec.java classes are provided to simplify your refactoring)
	
Bonus points:
1) Create a github account so that you can share your project with others
