# Task 1
-Q2. How many ports are open with a port number under 1000?
+ 3

-Q3. What is this machine vulnerable to? (Answer in the form of: ms??-???, ex: ms08-067)
+ ms17-010

# Task 2
-Q2. Find the exploitation code we will run against the machine. What is the full path of the code? (Ex: exploit/........)
+ exploit/windows/smb/ms17_010_eternalblue

-Q3. Show options and set the one required value. What is the name of this value? (All caps for submission)
+ RHOSTS

# Task 3
-Q1. If you haven't already, background the previously gained shell (CTRL + Z). Research online how to convert a shell to meterpreter shell in metasploit. What is the name of the post module we will use? (Exact path, similar to the exploit we previously selected) 
+ post/multi/manage/shell_to_meterpreter
-Q2. Select this (use MODULE_PATH). Show options, what option are we required to change?
+ SESSION

# Task 4
-Q1. Within our elevated meterpreter shell, run the command 'hashdump'. This will dump all of the passwords on the machine as long as we have the correct privileges to do so. What is the name of the non-default user? 
+ Jon
-Q2. Copy this password hash to a file and research how to crack it. What is the cracked password?
+ alqfna22

# Task 5
Flag1? This flag can be found at the system root. 
+ flag{access_the_machine}

Flag2? This flag can be found at the location where passwords are stored within Windows.
+ flag{sam_database_elevated_access}

flag3? This flag can be found in an excellent location to loot. After all, Administrators usually have pretty interesting things saved. 
+ flag{admin_documents_can_be_valuable}
