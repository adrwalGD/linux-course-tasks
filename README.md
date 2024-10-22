# linux-course-tasks
## Lab 1: Configuring a default boot target

### Learning Objectives
1. Check the default target
2. Change the default target
3. Check the Default Target again

### Solution
![image](./Screenshot%202024-10-22%20at%2013.08.14.png)


## Lab 2: Installing and Managing Packages on Debian/Ubuntu Systems

### Learning Objectives
1. Install the Apache Web Server Package
2. Verify the Server is Running and Capture the Result

### Solution
![image](./Screenshot%202024-10-22%20at%2013.26.33.png)
![image](./Screenshot%202024-10-22%20at%2013.26.07.png)


## Lab 3: Installing and Managing Packages on Red Hat/CentOS Systems

### Trivia
Your development team is working on their new web-based API. During testing, they decided to use a terminal-based web browser to perform tests on a separate system. This way, they won't have to leave their terminal window. They found a terminal browser they like, but the version they need to run is a bit different from the version in the official repository. They managed to download the appropriate package for their system and architecture but are unable to install it because of several missing dependencies. They have asked you to resolve the issue and have provided you with credentials and connection information to their client testing system. You will need to install the `elinks` package in the `/home/cloud_user/Downloads` directory successfully. You can resolve the unmet dependencies however you choose, but the version that has already been downloaded is the version that will need to be installed. Once you verify the application is installed and running properly, you can turn the system back over for their use.

### Learning Objectives
1. Install Available Elinks Application
2. Verify Elinks Package RPM Exists

### Solution
![image](./Screenshot%202024-10-22%20at%2013.42.01.png)
![image](./Screenshot%202024-10-22%20at%2013.42.34.png)
![image](./Screenshot%202024-10-22%20at%2013.43.00.png)

## Lab 4: Modify a Text File Using Sed

### Trivia
You are working at a firm that is collecting information about ancient Greece that will be published in a new book.

A member of your team has contributed a text file that contains the fable of the "The Ants and the Grasshopper." However, the text is incorrect as all of the instances of the word 'ants' has been replaced with the word 'cows'.

You will need to modify this file using a sed command so that the file will have the correct text. All instances of the word 'cows', regardless of case, needs to be replaced with the word 'ants'.

Once you have accomplished this task, leave the file on the system so that your editor can review your work.

NOTE: You only need to ignore case sensitivity

### Learning Objectives
1. Use `sed` to Change a Word in the File
2. There Should Be No Other File in the Home Directory

### Solution
![image](./Screenshot%202024-10-22%20at%2013.57.01.png)


## Lab 5: Creating a Directory Structure in Linux
### Learning Objectives
1. Create the 'Projects' Parent Directories
2. Create the 'Projects' Subdirectories
3. Create 'Projects' Empty Files for Next Step
4. Rename a 'Projects' Subdirectory

### Solution
![image](./Screenshot%202024-10-22%20at%2014.03.37.png)

## Lab 6: Working with Compressed Files in Linux
### Learning Objectives
1. Try out different compression methods
2. Create tar files using the different compression methods.
3. Practice reading compressed text files.

### Solution
![image](./Screenshot%202024-10-22%20at%2014.18.19.png)

## Lab 7: Working with Basic Regular Expressions

### Trivia
The following reports have been requested:

- Create a file called http-services.txt in the cloud_user's home directory that contains the values from /etc/services containing lines that begin with 'http' but not containing an 'x' at the end of the term for http.
- Next, create a file called lpic1-ldap.txt in the cloud_user's home directory that contains the values from /etc/services containing lines that begin with 'ldap' but not containing an 'a' after the term ldap (in other words, the 'a' should not be the sixth term).
- Finally, remove any value from http-services.txt containing the word 'service' at the END of the string and concatenate those values to a new file in the cloud_user's home directory called http-updated.txt

### Learning Objectives
1. Use regular expressions to locate information on http services.
2. Use regular expressions to find port information for LDAP services.
3. Create a new file based off of http-services.txt.

### Solution
![image](./Screenshot%202024-10-22%20at%2014.25.41.png)

## Lab 8: Adding a New Hard Disk to a Linux System

### Learning Objectives
1. Create a New PartitionP
2. Create the File System
3. Mount the new File System and Make it Permanent

### Solution
![image](./Screenshot%202024-10-22%20at%2014.39.23.png)

![image](./Screenshot%202024-10-22%20at%2014.38.18.png)

![image](./Screenshot%202024-10-22%20at%2014.39.33.png)


## Lab 9: Managing File Attributes and Permissions

### Trivia
Your organization's development team is working on their new Web-based API. They have just had another developer leave the team and they were working on a key component of the API. The directory he was working in will not allow anyone else on the system to even view the files within the directory. You have been asked to provide the team with a view into that directory by resetting the file and directory permissions. First, you have been provided with the credentials and connection information to the server in question and asked to change the permissions on the /opt/myapp directory so that everyone can change to and read the files within that directory. They have also requested that you ONLY change the permissions of the files and directories within the /opt/myapp directory so that everyone has read and write (but not execute). Please be sure to apply those permissions to all subdirectories recursively. Once you verify the files and directories are accessible, you can turn it back to the development team to continue their work.

### Learning Objectives
1. Reset Permissions on /opt/myapp Directory
2. Permissions on Files and Folders Within /opt/myapp

### Solution
![image](./Screenshot%202024-10-22%20at%2014.54.37.png)

![image](./Screenshot%202024-10-22%20at%2014.55.03.png)

![image](./Screenshot%202024-10-22%20at%2014.55.18.png)

## Lab 10: Working with Links in Linux

### Learning Objectives
1. Create a Symbolic (soft) Link
2. Check the Inode Numbers for the Link
3. Create a Hard Link
4. Attempt to Create a Hard Link Across File Systems
5. Attempt to Create a Symbolic Link Across File Systems

### Solution
![image](./Screenshot%202024-10-22%20at%2015.05.57.png)

![image](./Screenshot%202024-10-22%20at%2015.06.06.png)
