# BASHSCRIPT_SENIRO


🚀 Bash Scripting & Linux Automation (Simple Explanation)
1️⃣ Bash Script Fundamentals
Bash scripting means writing Linux commands in a file so they can run automatically.
Instead of typing the same commands again and again, we create a script to save time and reduce mistakes.
Example uses:
Automating server tasks
Managing files
Running commands automatically
Basic Bash Script Example:
#!/bin/bash
echo "Hello DevOps"
#!/bin/bash → tells Linux to run the script using Bash.
2️⃣ Variables in Bash
A variable stores information that we can use later in the script.
Example:
name="Qamar"
echo $name
Output:
Qamar
Use:
Store usernames
Store file paths
Store configuration values
3️⃣ Loops in Bash
A loop repeats a task multiple times automatically.
Loops are useful when we need to perform the same action again and again.
For Loop
Runs a command for each item.
Example:
for i in 1 2 3
do
echo $i
done
Output:
1
2
3
Use:
Creating multiple users
Processing multiple files
While Loop
Runs commands until a condition becomes false.
Example:
while condition
do
command
done
Use:
Monitoring systems
Running repeated checks
4️⃣ Positional Arguments
Positional arguments allow us to give input values when running a script.
Example:
Script:
echo $1
Run:
./script.sh Qamar
Output:
Qamar
Important arguments:
$1 → First input value
$2 → Second input value
$@ → All input values
$# → Number of inputs
Use: Making scripts flexible and reusable.
5️⃣ Automated Backup Script
A backup script automatically creates a copy of important files.
It helps protect data and saves time.
Example tasks:
Create backup folder
Copy files
Store backup safely
Use in real life:
Server backups
Database backups
Website backups
6️⃣ User Account Creation Script
A user creation script automatically creates Linux users.
Instead of creating users manually, the script does it quickly.
Example tasks:
Create new users
Assign permissions
Manage accounts
Use in real life:
Company servers
Cloud machines
Large IT environments
🌍 Real-World DevOps Uses
Server Automation
Automatically manages Linux servers and reduces manual work.
Cloud Automation
Used for managing AWS EC2 and other cloud servers.
Backup Management
Creates regular backups to prevent data loss.
CI/CD Automation
Runs commands automatically during software deployment.
🎯 Skills Learned
✅ Bash scripting basics
✅ Linux automation
✅ File management
✅ User management
✅ Backup automation
✅ DevOps workflow understanding