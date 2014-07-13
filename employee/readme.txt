First of all enter into employee directory.
Then to run loopback server write command in terminal: " slc run " (Please make sure that you are in employee folder)
Now your loopback server is running at "http://ip:3000/" (capy and paste this link in url)
There are two panels in url:
  1. Employee entry: You can enter employee details in input fields and press "Add employee" button to submit employee details.
  2. Employee List: You'll get employees list (name and designation) that saved in mongodb database.
  
SSH login procedure:
1. Ask me my ip
2. ssh naresh@my_ip
3. enter password gpnaresh22
4. visit the url: my_ip:3000
5. You will see the page
start the server before visiting the url
  
To check mongodb database:
  - Write "mongo" in terminal. Then you'll entered into mongodb.
  - Write "use test" to enter into database named test.
  - Then to check the employee entries: write command "db.employee.find()" - It will get all entries saved in employee table.
