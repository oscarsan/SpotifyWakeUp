A bit of an explanation how to use this script to wake up

# first
sudo touch /etc/crontab
crontab -e

When vim is opened write down
	50 22 * * 1-5 osascript /Users/oscar/Documents/play.scpt

This means that the script will be executed each monday to friday at 22:50


#second

Go to energy setting and schedule you computer to wake up 1 minute before the script.


