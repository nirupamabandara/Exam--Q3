# Exam--Q3

Answers

Q3)

A)
a) /etc/passwd is the file where the user information such as the User ID, Group ID, Location of the file, Directory information are saved. This is a text file.

b)/etc/shadow is the file where encrypted passwords are saved. The information such as password change date, password expiration date, maximum and minimum period between password changers are recorded in the shadow file. When a new user is created a shadow file will be created in the system.

c)setuid bit is set in order to provide special permissions on files. if setuid bit is set to an executable file the the process that runs in the file will grant permissions of the owner of the file regardless of the user who is running the file. This special permission allows a user to access files and directories that are only available for the owners. 

d)chroot command is used to change its current and root directories to the directory that is provided and then it will run the command given.

B) ls -l will display a list of files in the current working directory in a long list 

lsattr command lists the file attributes on asecond extendad file system.

C) Least privilege principal is providing minimum privileges required to perform a job. In Android it forces apps to declare the permissions they require when they install them. Then the users by knowing or unknowing the seriousness of the permissions are forced to simply allow the permissions in order to get the installation done. This practice trains users to agree to permissions requests and makes permissions seems less serious.

A) Access Control Lists extends the standard unix permissions. The Access Control Lists allows the Administrators to manage access permissions in a more easier way. Compared to Unix permissions the ACL are easy to understand. and also it increases the level of complexity. In unix the Files and directories have permission sets for the owner of the file, the group associated with the file and all other users of the system. In this method the main limitation is that different permissions cannot be configured for differnt users. The Access Control Lists were implemented as a attempt of overcoming this limitations.

B) EUID - is effective user ID

The EUID is used to determine the level of access the user has. When EUID is zero it means the user has unlimited access.

RUID - is the real user ID
 
The RUID is used to identify who the actual user is.
the RUID is created at the initiation of the session and it will remain until the session is terminated. RUID cannot be changed. only the root can chage this RUID.

C)

	 
