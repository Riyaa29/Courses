# Courses
This project displays the courses details for winter semester 2022 and also enables the user to create their own course schedule and the number of courses they want to take for a particular semester.

Languages/tools/editors:
1.	Language : C++20 : ISO/IEC 14882:2020 (informally known as C++20)
2.	Tools : Codeblocks-20.03mingw-setup.exe
3.	Editor : Riya Nagpal

START
1.	Declare a struct Courses
2.	Struct Variables : string course_number, string title, double hours_per_week, string session
3.	Declare an array of the struct courses[9999]
4.	Global Variable : int quantityOfCourses
5.	Declaring a function displayAvailableData()
6.	PRINT Course Details 
7.	End function displayAvailableData()
8.	Declare function get_data()
9.	Local Variable int userEntry = 0
10.	Write “Enter the number of courses you want to take : “
11.	Read userEntry
12.	FOR (int i = quantityOfCourses; i < (userEntry + quantityOfCourses); i++)
13.	Write “Number of courses : “
14.	Read courses[i].course_number
15.	Write “Title : “
16.	Read courses[i].title
17.	Write “Hours per week : “
18.	Read courses[i].hours_per_week
19.	Write “Session : “
20.	Read courses[i].session
21.	END FOR
22.	quantityOfCourses += userEntry
23.	Declare function displayData()
24.	FOR (int i = 0 ; i < quantityOfCourses; i++)
25.	PRINT the details entered by the user 
26.	END FOR
27.	End displayData()
28.	Declare MAIN ()
29.	PRINT name and information 
30.	Local variables : int option
31.	DO
32.	Print Menu
33.	Read option
34.	Write option
35.	SWITCH(option)
36.	Case 1: Call displayAvailableData()
37.	Case 2: Call get_data()
38.	Case 3: Call displayData()
39.	END SWITCH
40.	WHILE option != 0
41.	END DO-WHILE
END

the functions (prototypes) :

1.	void displayAvailableData() :	Displays the course details available for the Winter Semester 2022.
2.	void get_data() :	It enables the user to enter the course details for the chosen number of courses they want to take. 
3.	void displayData(Courses& courses) :	It displays the data entered by the user. 
