# Lab Report 1

### Part 1 - Course On Boarding

Welcome to CSE 15 lab! This course aims to provide *“hands-on exploration of software development tools and techniques.”* We have amazing professor and a lot of TAs and tutors, who can help you throughout the course. 

### Part 2 - Activate your CSE 15L Account

The first thing you will do in the class is to find your CSE 15L course specific account. Here is the friendly guide on how to find your account. 

- **Step 1.** Go to [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php).

- **Step 2.** Put your username for UCSD account and student ID in **Account Lookup** section.

![Screen Shot 2023-01-14 at 3.42.43 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/627e8ab0-af40-454e-bdc6-7476a2a771e9/Screen_Shot_2023-01-14_at_3.42.43_PM.png)

- **Step 3.** You will be lead to **Account Lookup Results** page. Then you will find your username for this specific course in **Additional Accounts** section. The username should be in this format: cs15lwi23*** (The last 3 *** is your own username.)

![Screen Shot 2023-01-14 at 3.45.45 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e5d8df41-b412-40ee-9861-7b3906f81fe7/Screen_Shot_2023-01-14_at_3.45.45_PM.png)

- **Step 4.** Now you have to reset the password. Click [UC San Diego Active Directory (AD) Password Change Tool](https://sdacs.ucsd.edu/~icc/password.php) to reset.
    - (*Once you filled all the blanks, do not press ‘Check Password’ button. Just click your mouse on the last input field, and click ENTER/RETURN on your keyboard)

- **Step 5.** You are all set to your course specific account!

### Part 3 - Launch Visual Studio Code

Now we will launch a software called **Visual Studio Code**. 

- **Step 1.** Once you enter **[https://code.visualstudio.com/](https://code.visualstudio.com/)**, you will find an instruction to download the program. There are different versions for different type of operating system (like OSX for Macs and Windows for PCs).

- **Step 2.** If you finish launching it and setting basic settings like color, you will see an empty screen like this.

![Screen Shot 2023-01-14 at 3.57.02 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0079e775-487d-469e-8df2-dcded583b492/Screen_Shot_2023-01-14_at_3.57.02_PM.png)

### Part 4 - Remotely Connecting

Next step is to remotely connect to your course specific account. 

- **Step 1.** Type “X@ieng6.ucsd.edu” (for X, type your course specific username starts with cs15lwi23) in a terminal in VScode.

- **Step 2.** Once you type the line, you will need to insert password. Even though you type the password, it will not show on the screen. Just type the password and press enter bar.

![Screen Shot 2023-01-16 at 5.13.13 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f25c7911-3200-4f34-a801-b7df3c6d11d0/Screen_Shot_2023-01-16_at_5.13.13_PM.png)

- **Step 3.** Then you will see a screen like this. It means ‘you are currently logged into’ the course specific account.

![Screen Shot 2023-01-16 at 5.14.57 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6ca1c37f-d897-45b9-9f0f-b1fc7b28e3bb/Screen_Shot_2023-01-16_at_5.14.57_PM.png)

### Part 5 - Trying commands

When you get use to typing in **Visual Code Terminal**, now try some different commands. Here are some suggestions. 

- `cd ~`
- `cd`
- `ls -lat`
- `ls -a`
- `ls <directory>` where `<directory>` is `/home/linux/ieng6/cs15lwi23/cs15lwi23abc`, where the `abc` is one of the other group members’ username
- `cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/`
- `cat /home/linux/ieng6/cs15lwi23/public/hello.txt`

For example, if I put `ls -lat`, you will see a screen like it.

![Screen Shot 2023-01-16 at 5.51.54 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/eedc68d1-4b19-445d-9312-c68b62fbf790/Screen_Shot_2023-01-16_at_5.51.54_PM.png)

### Wrap up of Lab 01

Good job! You made through the whole steps from activating your course specific account to trying different commands on Visual Code. If you want to log-out from the remote server, you can either press `Ctrl-D` or run the command `exit`.
