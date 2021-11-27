----------------------------------------------------------------------------
             Hardware Resources Booking Tool (HRBT) Release 1.0
----------------------------------------------------------------------------
                                  Readme
                              November 27, 2021
----------------------------------------------------------------------------

Usage Notes
----------------------------------------------------------------------------
Hardware Resources Booking Tool (HRBT) provides a Graphical User Interface(GUI)
platform to book and track all available hardware resources in a project.
The user can book any free hardware or can raise a request to borrow any 
pre-occupied hardware.

There will be two types of user: 
Only one user with admin privilege who can update the resource inventory and 
other created users will have limited right access to view and book the
resources

System/Browser Requirements for Services
----------------------------------------------------------------------------
Prerequisites:
- Before running any command make sure the system should have node.js 
  with version v14.17.3 or above installed in it.
- Check your version with command: node --version

To install and operate the Hardware Resources Booking Tool the following
minimum criteria are required:

Necessary Hardware:

Processor: x86 compatible 64 bit CPU with 4 cores
RAM: 4 GB
HDD: 250GB
Supported Operating Systems: Windows 10/Linux/Mac
Supported Browser: Google Chrome

Installation Notes
----------------------------------------------------------------------------
- Login to a machine with admin rights
- Open cmd/terminal on the machine
- Create one folder where the user can clone the repository 
    e.g C:\Users\xyz>md <new_directory_name> - on Windows
- Go under the created directory and clone the below repository
    https://github.com/kartik-3/hardware-resources-booking-tool.git

e.g C:\Users\xyz> cd new_directory_name
    C:\Users\xyz\new_directory_name> git clone https://github.com/kartik-3/hardware-resources-booking-tool.git
    
- Go to folder "hardware-resources-booking-tool\server" and run "npm install" and "npm run start"
    C:\Users\xyz\new_directory_name\hardware-resources-booking-tool\server> npm install
    C:\Users\xyz\new_directory_name\hardware-resources-booking-tool\server> npm run start

- Open another cmd terminal and go to folder "hardware-resources-booking-tool" and 
  run "npm install" and "npm run serve"
    C:\Users\xyz\new_directory_name\hardware-resources-booking-tool> npm install
    C:\Users\xyz\new_directory_name\hardware-resources-booking-tool> npm run serve

- Launch the application by opening recommended web browser
  and enter URL: http://localhost:8080/

- Login page should be visible.
  Enter default user credentials to access the application
    Default admin credentials: admin@incedoinc.com/admin
    Need to signup to create other users

- To close the application, use ctrl+c and close all running process on both terminals

Note
----------------------------------------------------------------------------
If cloning from git hub, One time setup is required:
    Update .env file under folder "hardware-resources-booking-tool\server" and add content mentioned in the zip file.

Helpline
----------------------------------------------------------------------------
Kartik Sehgal || kartik.sehgal@incedoinc.com  || 9958571972
Parakh Gupta  || parakh.gupta@incedoinc.com   || 9716611069
Sandeep Kumar || sandeep.kumar3@incedoinc.com || 9643000626
