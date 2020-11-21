### What is SSH and LXPLUS? 

Google them. 

Some useful links: 
1) Beginners Guide to SSH (5:59): https://www.youtube.com/watch?v=qWKK_PNHnnA
2) SSH Crash Course | With Some DevOps (55:01): https://www.youtube.com/watch?v=hQWRp-FdTpc

### Login onto LXPLUS

Type the following command to access LXPLUS via SSH.

```bash
ssh username@lxplus.cern.ch
```

Then it will ask you to enter a password. It is your CERN account password.  
Now you have access to the remote server, LXPLUS.

(username is not your CERN email address. username is your CERN account name.)  

### Download a file from LXPLUS  

Open the local folder where you want to download the file from LXPLUS. Open the terminal by right clicking in that folder. (You may also use terminal commands to get that directory.)

Type the following to download the file into the folder you opened terminal in. (`./` refers to the current directory) 

```bash
scp -r username@lxplus.cern.ch:/the_path_of_the_file/ ./
```

