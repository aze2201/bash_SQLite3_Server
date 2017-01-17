# bash_SQLite3_Server
SQLite Server over TCP


put this script to any folder where you want to create SQLite database and execute below command.

# Server side
nc -l -p 6667 -e ./expect.exp -k

# Client Side
telnet <remote ip> 6667

