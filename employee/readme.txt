SSH login procedure:
1. Please call me and ask me my ip address. Let's assume my ip is my_ip.
2. Enter the following command into the terminal to login:
	ssh naresh@my_ip
3. Enter the following password: gpnaresh22

After successfully logging in to my computer:
  - First of all, enter the following command into the employee directory: "cd employee"
  - Then to run the loopback server, write the following command in the terminal: "slc run" (Make sure that you are in the employee folder)
  - Now your loopback server is running at "http://my_ip:3000/" (visit the url: my_ip:3000)
  - You will see the page with two panels in the url:
    1. Employee entry: You can enter employee details into the input fields and press the "Add employee" button to submit employee details.
    2. Employee List: You will get the list of employees(name and designation) that is saved in the mongo database.
    
  - Press "CTRL+C" in the terminal to stop the server.
  
To check the mongo database:
  - Write "mongo" in the terminal. Then you will enter into mongodb.
  - Write "use test" to enter into the database named test.
  - Then to check the employee entries, write the command "db.employee.find()" - It will retrieve all entries saved in the employee table.
