# Hands-on lab: Getting started with an IDE

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/IDSNlogo__5_.png" width="200">

Estimated Time: 30 minutes

In this lab, you will become familiar with using an Integrated Development Environment (IDE). The IDE that you will be using is called Skills Network Cloud IDE which is based on an open-source project called Theia.  This IDE is very similar to the popular Visual Studio (VS) Code IDE. In this lab, you will explore the IDE and use it to create and run a simple Python application. You will create a code file, save it, and edit it to make changes.

## Objectives:

- Explore the IDE interface.
- Create a simple Python program using the IDE.
- Execute the program.
- Edit the source code and re-run the program.

# About the lab environment


**Two Components of the Skills Network Lab environment:**

- The instructions that you will follow to complete this lab are displayed on the left side of the screen.

- The area on the right side of the screen is the actual IDE where you will use the menus, terminals, and tools to develop your code.
  
<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/ide.PNG" width="75%">

# Exercise 1: Explore the IDE interface

**Explore the menus, terminals, and tools**

Let us now explore the IDE interface. Please click on each of the icons and menu items highlighted in red boxes in the following screenshots to become familiar with their purpose.

**1.** In the **Explorer** menu, you will find your folders, files (created or cloned), and pre-requisites installed.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/explorer.PNG" width="75%">

**2.** In the **Search** menu, you can search for particular folders or files that were created or cloned.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/search.PNG" width="75%">

**3.** In the **Source Control** menu, you will find the cloned repository.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/source_control.PNG" width="75%">

**4.** In the **Debug** menu, you can debug and troubleshoot your code.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/debug.PNG" width="75%">

**5.** In the **Extensions** menu, you can check the recommended, installed, and built-in software already provided as the pre-requisites. 

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/extention.PNG" width="75%">

**6.** In the **Skills Network Toolbox**, you will find options to use database, big data, cloud, and other tools to complete lab exercises in other courses.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/toolbox.PNG" width="75%">

**7.** Explore the menu options at the top of the IDE: File, Edit, Selection, View, Go, Run, Terminal, Help. You will be using some of these menu items in subsequent exercises. A summary of what they are used for is provided below.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/menu.PNG" width="75%">

- **File:** This menu is used to create a new file or folder and save the file.

- **Edit:** This menu is used to undo, redo, cut, paste and find the file.

- **Selection:** This menu is used to Select All, Copy line up or down and Move line up or down in the file.

- **View:** This menu is used to view the other menus like explorer, extensions, and search.

- **Go:** This menu is used to Go back, view the last edit location, and go to the files.

- **Run:** This menu is used for debugging and Adding configurations.

- **Terminal:** This menu is used to open the New terminal and run the tasks.

- **Help:** This menu is used to view the list of extensions and get started a file.

Click on each menu and explore them.

**You will learn about folder and file creation and how to use the terminal to run the commands later in this lab.**

# Exercise 2: Create a simple Python program using the IDE

**1.** On the window to the right, click on the File menu and select **&quot;New Folder&quot;** option, as shown in the image below.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/folder.PNG" width="75%">

Name the folder **&quot;welcome101&quot;**.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/folder_2.PNG" width="75%">

**2.** Right-click on the folder welcome101 and click on **&quot;New File&quot;**.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/file.PNG" width="75%">

Create a new file and name it **&quot;welcome.py&quot;**.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/file2.PNG" width="75%">

**3.** Paste the below code to the welcome.py file and save it using Ctrl+S.

``` Python
Welcome to the world of programming!
print(message)
``` 
<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/welcome.PNG" width="75%">

# Exercise 3: Execute the program

**1.** Open a terminal window by using the menu in the editor: Terminal &gt; New Terminal.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/new-terminal.png" width="75%">

In the terminal, you will be running all the commands used to complete the lab.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/terminal1.PNG" width="75%">

**2.** Verify that python is installed.

``` bash
python --version
```

You should see output similar to this, though the versions may be different:

```
Python 2.7.17
```

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/python_version.PNG" width="75%">

**3.** Change the directory for this lab by using the command shown below in the terminal.

``` bash
cd welcome101
```

**4.** Run the program in the terminal using the below command:

``` bash
python welcome.py
```

**You will get an invalid syntax error because the source code is incorrect.**

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/code.PNG" width="75%">

# Exercise 4: Edit the source code and re-run the program

**1.** Replace the source code with the code shown below:

``` python
message= "Welcome to the world of programming"
print (message)
```
<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/correct_code.PNG" width="75%">

**2.** Run the program in the terminal using the command below:

``` bash
python welcome.py
```

You should see an output similar to this.

```
Welcome to the world of programming!
```

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/correct_output.PNG" width="75%">

Practice Exercises


**1.** Create a new folder called **software 101**.

On the window to the right, click on the File menu and select the **&quot;New Folder&quot;** option, as shown in the image below. Name the folder **&quot;software101&quot;**.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/folder.PNG" width="75%">

**2.** In it, create a new file called &quot;software.py&quot;.

Right-click on the folder software101 and click on **&quot;New File&quot;** and create a new file and name it **&quot;software.py&quot;**.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/hint.PNG" width="75%">

**3.** Write code to print &quot;software engineering is awesome&quot;.

Write a code to print the message: &quot;software engineering is awesome&quot;. 

Paste the code below to the software.py file and save it using Ctrl+S.

``` python
message= "software engineering is awesome"
print(message)
```

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/hint2.PNG" width="75%">

**4.** Run the program.

Run the program in the terminal using the below command:

``` bash
python software.py
```

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/hint3.PNG" width="75%">

**5.** Edit the software.py file and make &quot;s&quot; &amp; &quot;e&quot; in &quot;software engineering is awesome&quot; to uppercase.

Change the message from &quot;software engineering is awesome&quot; to &quot;Software Engineering is awesome&quot; in software.py.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/hint_5.PNG" width="75%">

**6.** Run the update file.

Run the program in the terminal using the below command:

``` bash
python software.py
```
<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module%202/Getting%20started%20with%20IDE/images/hint_6.PNG" width="75%">

Congratulations! You have completed this lab and know how to run python programs in an IDE.

 

## Tutorial details

**Author:** Pallavi Rai

**Change Log**

| Date | Version | Changed by | Change Description |
|------|--------|--------|---------|
| 2023-05-04 | 1.2 | Eric Hao | Updated Page Frames and Formattings |
| 2022-07-28 | 1.1 | Rav Ahuja | Instructions and formatting updated |
| 2022-07-22 | 1.0 | Pallavi Rai | Initial version created |

## &lt;h3 align&#x3D;&quot;center&quot;&gt; &amp;copy;IBM Corporation 2023. All rights reserved. &lt;h3/&gt;
