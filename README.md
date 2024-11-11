# MyProject220302381
# Command-Line Calendar Project

Project overview:
 The Command-Line Calendar project is a simple text based program designed to run in the command-line.

Goals:
 The goal of this project is to make a simple command-line calendar where the user can easily manage tasks by adding 
 reminders or events to specific days. This project is an exercise in creating a file-based task manager, simulating basic 
 calendar functions through the JavaScript programing language and the Node.js runtime.

Features:
 View Calendar Feature:
 Display the current month or year.
 Show a specified month of a selected year.
 View the current weeks tasks.
  Task Management:
  Add a task to a specific date.
  View all the tasks for today or any specified day.
  Edit or delete tasks by date and name.
   File Storage:
   Tasks and calendar data are stored in a JSON file.

Technologies used:
 JavaScript:The programing language that is used for this project.
 Node.js:The java run time used to run the program in the command-linr
 JSON:Used to store data for calendar information
 
Setup and Run
 Clone the Repository: 
  git clone <repository-url>
  cd command-line-calendar
  
Install Dependencies: This project has no external dependencies but uses built-in Node.js libraries.
Run the Application: 
 Execute commands by running:
  node calendar.js <command>

Usage Examples:
 Show currant month calander:
 node calendar.js show

 Show currant year calendar:
 node calendar.js show -y

 Display specific month:
 node calendar.js show -m 2024 11

 Add task to specific date:
 node calendar.js add 2024 11 15 "My Task"

 Delete task from specific date:
 node calendar.js delete 2024 11 15 "My Task"


 
 
 
Added initial README file
 

   
   

