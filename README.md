# Site_Blocker
A project to block the websites.

Here I have used datetime module from which you can get details like date, month, year and time.

127.0.0.1 is the loop back addreess. e.g when the server is down, the browser will redirect to this IP and unable to load the website.
website_list has the list of addreeses that I want to block.

Then I used the file handeling methods to change the host file on MAC accordingly.
e.g read and write methods so that I can change the files according the logic.

file.seek() method is used to take the pointer/cursor at the starting of the line.
fiel.truncate() resizes the file.

____________________________________________

This program is developed so that employees or students don't get distracted while doing their work or study. 
Yes you can also block the websites through third party applications , but why to use them if you have a programing language like python.
You can adjust the time accordingly in dt.now() condition
------------------------------------------------------------------------------------------------------

In the end you have to use crontab so that this program will run as a process and each time you don't have to run the program from terminal or cmd through system administrator.

COMMANDS are-
sudo crontab -e
@reboot python 3.8 [path of file]/site_blocker.py


