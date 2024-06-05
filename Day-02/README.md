# CyberSecurityNotes
## Day-02

### In the 2nd day ,we discussed and learnt about basic linux commands like:-

pwd (Print Working Directory): Displays the current directory you are in.

cd (Change Directory): Changes the current directory.

cd /path/to/directory  # Change to a specific directory
cd ..                  # Move up one directory level
cd ~                   # Change to the home directory
cd                     # Change to the home directory (same as 'cd ~')


ls (List): Lists files and directories in the current directory.
ls                     # List files and directories
ls -l                  # List with detailed information
ls -a                  # List all files, including hidden files
ls -lh                 # List with detailed information and human-readable file sizes


2. Managing Files and Directories
mkdir (Make Directory): Creates a new directory.
mkdir directory_name

rmdir (Remove Directory): Removes an empty directory.
rmdir directory_name

rm (Remove): Removes files or directories.
rm file_name           # Remove a file
rm -r directory_name   # Remove a directory and its contents recursively
rm -f file_name        # Force remove a file without prompting for confirmation
rm -rf directory_name  # Force remove a directory and its contents recursively

cp (Copy): Copies files or directories.
cp source_file destination_file          # Copy a file
cp -r source_directory destination_directory  # Copy a directory recursively
mv (Move): Moves or renames files and directories.

mv old_name new_name                    # Rename a file or directory
mv file_name /path/to/destination       # Move a file to a different location
touch (Create Empty File): Creates an empty file or updates the timestamp of an existing file.
touch file_name


3. Viewing and Editing Files
cat (Concatenate): Displays the contents of a file.
cat file_name

more and less: View the contents of a file one screen at a time.
more file_name
less file_name


head and tail: View the beginning or end of a file.
head file_name         # Display the first 10 lines of a file
head -n 20 file_name   # Display the first 20 lines of a file

tail file_name         # Display the last 10 lines of a file
tail -n 20 file_name   # Display the last 20 lines of a file

nano and vi/vim: Text editors for editing files directly from the terminal.
nano file_name         # Open a file in the nano editor
vi file_name           # Open a file in the vi editor
vim file_name          # Open a file in the vim editor

4. System Information and Management
man (Manual): Displays the manual pages for a command.
man command_name

uname (Unix Name): Displays system information.
uname                  # Display basic system information
uname -a               # Display all system information

df (Disk Free): Displays disk space usage.
df                     # Display disk space usage
df -h                  # Display disk space usage in human-readable format



du (Disk Usage): Displays the disk usage of files and directories.
du                     # Display disk usage of the current directory
du -h                  # Display disk usage in human-readable format
du -sh directory_name  # Display total disk usage of a directory


top and htop: Displays real-time system performance and process information.
top                    # Display real-time system information
htop                   # Display real-time system information (requires installation)

ps (Process Status): Displays information about active processes.
ps                     # Display processes for the current shell session
ps aux                 # Display all running processes


kill (Terminate Process): Terminates a process by its PID (Process ID).
kill PID               # Terminate a process with a specific PID


## we learnt about lan,wan,nat which are:
### Network Address Translation (NAT) is a method used in networking to modify network address information in the IP header of packets while they are in transit across a traffic routing device. The primary purpose of NAT is to improve security and decrease the number of IP addresses an organization needs. 
### A Wide Area Network (WAN) is a telecommunications network that extends over a large geographical area for the primary purpose of computer networking. WANs are typically used to connect multiple local area networks (LANs) and other types of networks so that users and computers in one location can communicate with users and computers in other locations.
### Network Address Translation (NAT) is a technology used in computer networking to modify network address information in the IP header of packets while they are in transit across a traffic routing device. NAT is commonly implemented in routers and firewalls to enable multiple devices on a local network to share a single public IP address for accessing the Internet, thereby conserving public IP addresses and enhancing network security


### Then we discussed about kali linux that is first thing that we need to do is update upgrade and change password by using following commands:
sudo apt update
sudo apt upgrade
sudo passwd kali - change passwrd
sudo su  - switch user
