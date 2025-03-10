# Basic-Shell-Script-Commands

##File and Directory Management
```
ls          # List files and directories
cd          # Change directory
pwd         # Print current working directory
mkdir dir   # Create a new directory
rm file     # Remove a file
rm -r dir   # Remove a directory and its contents
cp src dest # Copy a file/directory
mv src dest # Move or rename a file/directory
find . -name "file.txt"  # Find a file
```



##File Content Manipulation
```
cat file.txt       # Display file content
nano file.txt      # Open file in nano editor
vi file.txt        # Open file in vi editor
echo "Hello" > file.txt  # Write to a file
echo "World" >> file.txt # Append to a file
grep "text" file.txt  # Search for text in a file
awk '{print $1}' file.txt  # Extract column from a file
sed 's/old/new/g' file.txt  # Replace text in a file
```

##Permissions & Ownership

```
chmod 755 file     # Change file permissions
chown user file    # Change file owner
chgrp group file   # Change file group ownership
```


##Networking
```
ping google.com        # Check internet connectivity
curl -O url           # Download a file
wget url              # Download a file
```

##Process Management
```
ps aux           # List running processes
top              # Show running processes interactively
kill PID         # Kill a process by ID
pkill process    # Kill a process by name
```

##System Monitoring
```
df -h           # Check disk space usage
du -sh *        # Check directory size
free -m         # Check RAM usage
uptime          # Show system uptime
```









