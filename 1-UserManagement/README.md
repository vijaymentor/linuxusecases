- Manager want to implement an on boarding process. Whenever new employee joined in the project, their UserId. How to force a user to reset his password upon next login ?
**
****Answer :-
We can use passwd or chage command for this requirement,
Method 1 :- (using passwd commad)
passwd --expire username
chage -l username
**
**Method 2 :- (using chage commad)
chage --lastday 0 username******

- In one of the support project 100 Linux admins are working in 24/7 support. Project want to monitor all the system admin support activity.How to log commands executed by all the users in Linux?
- What is the command to create a user with a pre defined uid, shell and home directory?
- If I delete a user, does it's home directory gets deleted? If not then what is the command to delete the home directory of user along with the user
- What are the details you get with finger command?
- How can you give a normal user all the root level privileges?
- How can you give sudo access to any user without asking him to provide passord every time he runs a command?
- Which files stores the user min UID, max UID, password expiration settings, password encryption method being used etc.,?
- How do you make a file copied to a new user account automatically upon user account creation?
- Which commands are normally recommended to edit “/etc/passwd”, “/etc/shadow”, “/etc/group” and “/etc/gshadow” files?
- Whenever an user tries to login via terminal, system would throw up the error “The account is currently not available”, otherwise, via GUI when user enters password, it looks to be logging in, however, comes back to the login prompt. How could this issue be fixed?
- Create users home directory in /home1 directory instead of default /home directory. This gets applicable to any new users who gets created i.e the home directory of that user should be /home1/<UserName>/
- How do you make/grant complete access (rwx) on files created for a user and deny any level of access to others including group?
- How to check if an user account has been locked?
- How to find out the shadow password encryption method being used in Linux? How could this be changed (example : from md5 to sha512)?
- What are the possible causes when an user failed to login into a Linux system (physical/remote console); despite providing proper credentials?
- How to manually add user without using “useradd/adduser” or “system-config-user” utilities?
- 
