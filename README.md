# mybash

my MBP bash profile and rc backup


How to check which shell am I using:
Use the following Linux or Unix commands:

ps -p $$ – Display your current shell name reliably.
echo "$SHELL" – Print the shell for the current user but not necessarily the shell that is running at the movement.
echo $0 – Another reliable and simple method to get the current shell interpreter name on Linux or Unix-like systems.
readlink /proc/$$/exe – Another option to get the current shell name reliably on Linux operating systems.
cat /etc/shells – List pathnames of valid login shells currently installed
grep "^$USER" /etc/passwd – Print the default shell name. The default shell runs when you open a terminal window.
chsh -s /bin/ksh – Change the shell used from /bin/bash (default) to /bin/ksh for your account
