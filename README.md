Welcome to SSH automation

This is a simple bash script for any one (specially for SysAdmins) whose his major deal is working with servers and other devices. It lets you select the 
destination where you wanna connect to using SSH, just by typing a number that is associated with your destination in the list of destinations.

To use this script you must at first create a list of destinations that you deal with them most often. This list is defined with hostname or IP address of 
destinations. In this script our assumption is that you wanna connect to your devices using public key authentication which is more secure than password 
authentication. On the other, if you wanna use username and password you must enter your credentials in the script which make the script so vulnerable.

So,at first you will execute the script and will "Make your list" by giving the required information to the script such as Hostname/IP address,username that you use to login and your favorite name 
for your destination.After completeing the list it will be saved in your home directory and you can check it out or edit it anytime you want. you can use "-e" option with the script to edit your 
list. So, if you have already run the script and the "destination.list" file exist on your system the script will only show you your own list and ask you about the destination you wanna connect just by 
entering a number.


I hope you enjoy it !
