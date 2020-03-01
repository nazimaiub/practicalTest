follow the instruction to run this project--

1)in dot net application 
=> go to appsettings and change the connection string server name to your local server name
=>go to nuget package manage console and run these two commands
add-migration initial
update-database

it will create the data base and tables
2)angular
=>open angular app and and do the command
npm install
=>base url is on services folder dbservice file
chnage the url according to ur dot net application portnumber


--------------------
in this project i have used code first approch so i didnt give the database backup file.databse will create automatically by migration
authentication has been done for two type of user one is admin another is employee.
first signup page will create admin user.and admin will create task,create employee and delete task
employee user can only see the task after login.
thank u.


