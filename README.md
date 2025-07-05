# Student Support Program 
# Introduction 
The Student Support Program is a C++-based application designed to assist students in finding 
suitable universities and scholarships based on their academic profiles. By leveraging data 
structures such as arrays, linked lists, stacks, queues, and binary search trees (BST), the program 
provides an efficient and user-friendly portal for students to explore educational opportunities 
and manage scholarship applications.  
# Objectives 
-  University Search: Enable students to find universities matching their GPA, preferred 
location, and program of study. 
- Scholarship Finder: Identify scholarships based on GPA and major, sorted by award 
amount. 
- Application Management: Allow students to apply for scholarships and track their 
applications. 
- Recommendation System: Provide personalized university recommendations based on 
the student's major. 
- History Tracking: Maintain a history of recommendations for quick reference. 
- Efficient Data Management: Utilize appropriate data structures to ensure fast and 
reliable operations.
# Scope 
The program targets students seeking higher education opportunities in universities worldwide. It 
includes a sample dataset of universities and scholarships but is designed to be scalable for larger 
datasets. The system supports basic CRUD (Create, Read, Update, Delete) operations for data 
management and provides a menu-driven interface for user interaction. 
# Significance 
This project addresses the challenges students face in navigating the complex landscape of 
university admissions and scholarship opportunities. By automating the search and application 
process, it saves time, reduces errors, and empowers students to make informed decisions about 
their education. 
# Procedures 
# System Workflow 
1. Initialization:  
- The program loads sample data for universities and scholarships into a BST and 
array, respectively. 
- Data structures (Stack for recommendation history, Queue for applications) are 
initialized. 
2. User Interaction: 
- Users interact via a menu-driven interface with options to: 
-  Find universities by GPA, location, and program. 
-  Find scholarships by GPA and major. 
-  Apply for scholarships by specifying the award amount. 
-  View scholarship applications. 
-  Get university recommendations based on major. 
-  View the most recent recommendation. 
-  Exit the program.
  
3. Data Processing: 
- University Search: Filters universities from the BST based on user criteria. 
- Scholarship Search: Matches scholarships from the array and sorts them by 
award amount. 
- Recommendations: Pushes matching universities to a stack for history tracking. 
- Applications: Enqueues scholarship applications for tracking. 
4. Output: 
- Results are displayed in a clear format, including university/scholarship details or 
error messages if no matches are found. 
