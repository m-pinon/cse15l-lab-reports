Test Screenshot:
![Lab1WhereAmI](https://user-images.githubusercontent.com/97760668/149583347-2b621c67-1d66-4f46-9728-525c06b99654.PNG)

Week 2 Lab Report:

Installing VScode:
1. Go to the Week 1 page in the course website.
2. Click the link in **Part 2 - Visual Studio Code** and follow the instructions to download and install.
![Lab1VSC](https://user-images.githubusercontent.com/97760668/149586204-a24a34db-4226-4538-806e-ecb49af3b18a.PNG)

Remotely Connecting:
1. Find out your CSE15L acount
2. Install OpenSSH by using the links in **Part 3 - Remotely Connecting**
3. Open a terminal in VSCode
4. Use the comand *ssh (user account)@ieng6.ucsd.edu*
5. Enter your cse15l account password (which may or may not be your ucsd account password)
![Lab 1 SSH Connect](https://user-images.githubusercontent.com/97760668/149586862-e14c6c43-fe7d-4ef8-b358-7b27e59cda04.PNG)


Trying Some Commands:
1. Run some commands to get familiar with VSCode and being logged in remotely.
2. Some useful commands include cd, ls, pwd, mkdir, and cp
![Lab 1 Run Commands](https://user-images.githubusercontent.com/97760668/149587037-034b7134-4218-4def-8de2-1a5eb7d37df1.PNG)

Moving Files with scp:
1. Create a file on your computer called WhereAmI.java with the contents specified on the course website
2. Run the file on your computer
3. In the directory of the file run the command *scp WhereAmI.java (user account)@ieng6.ucsd.edu:~/*
4. Enter your password

![Lab 1 scp WhereAmI](https://user-images.githubusercontent.com/97760668/149587384-0abb27a0-26bc-4931-928b-849a2a332aae.PNG)

Setting an SSH Key:
1. On your own computer (not logged into ucsd account) use command *ssh-keygen*
2. SSH into your cse15 account
3. Run *mkdir .ssh*
4. Copy the public key into the .ssh directory
5. Logout. On your client, enter the command shown on the course website.
![Lab 1 key](https://user-images.githubusercontent.com/97760668/149587841-405ad046-da9f-4776-bcd6-53d4cf4828a1.PNG)

Optimizing Remote Running:
1. You can run a command at the end of an ssh command to immediately run it on the remote server.
2. You can use semicolons to run multiple commands at once

![Lab1MakingRunPleasant](https://user-images.githubusercontent.com/97760668/149588389-3cb65aa2-37a5-44f8-9c75-019315b2b822.PNG)
