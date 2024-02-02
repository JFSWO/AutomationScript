Automation Script

The goal of this project is to automate the script execution and data recollection for servers in a client environment.
Using python as the main progamming language and libraries such as paramiko to establish SSH conections.
The program will work by loading the list of IP addresses with their respective password to establish an SSH connection.
Once a connection is established the program will use the SFTP protocol to send the script files to be executed.
The program will execute the scripts and save the output on the machine then using SFTP the files will be transferred back to the main machine 
