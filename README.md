# SQLite3 embed database over TCP (no auth)
SQLite Server over TCP

Put this script to any folder where you want to create SQLite database and execute below command.

## It uses `expect` scripting TCL extention on Linux

# Server side
```
$ chmod +x SQLite.exp
nc -l -p 6667 -e ./SQLite.exp -k
```

# Client Side
```
$ telnet ServerIP 6667
```
