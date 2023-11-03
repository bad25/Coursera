<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/IDSN.png" width="200">

# Hands-on Lab -  Hello World in 11 Programming Languages
Estimated Time: 15 minutes

A software design is abstract and needs to be given a tangible form by code. Code is created using programming languages or scripting languages. In this lab, you will see how most commonly used languages are means to get to the end and provide similar output. The way you write the program and run the code will differ from one language to another. A software engineer can be proficient in one or more languages. In this lab you will begin your journey to become multilingual in computer programming by learning to say **&quot;Hello World!&quot;** in 10 popular languages: C, Java, Go, Python, Node JS, Ruby, PHP, PERL, Bash, C++ and a bonus markup language, HTML.

## Learning Objectives:

After completing this exercise, you should be able to perform the following tasks:

- Understand how to write and run code
- Display &quot;Hello World!&quot; in several languages: C, Java, Go, Python, Node JS, Ruby, PHP, PERL, Bash, C++ and HTML.
- Obtain same output using different languages

### Pre-work - Open terminal

1. Click on **Terminal** in the top menu and click on **New Terminal**.
<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/new_terminal.png" width="50%">

2. This will open up a new terminal window where you can execute commands.
<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/terminal.png" width="50%">

### Exercise 1: Display Hello World using C

C is one of the oldest languages. It is a programming language. You cannot run it as is. You need to compile it to obtain an executable form.

1. Click on the **File** menu and click on **New File** to create you first C program.
<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/new_file.png" width="50%">

2. Enter the file name as &#x60;helloworld.c&#x60; and press &#x60;OK&#x60;. 

> C programs have the extension **.c**.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/newfile-name-save.png" width="50%">

3. This will open the file.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/code_space.png" width="50%">

4. Copy and paste the following code into the file. In the &#x60;printf&#x60; statement, makes sure there is the newline character &#x60;\n&#x60; after the message on the output window, when you run the code.

``` c
#include <stdio.h>

int main(void) {
  printf("Hello World!\n");
  return 0;
}
```
This is how the file would appear on your window, after you paste the code and save it.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/c_code.png" width="50%">

5. Click on **File** menu and choose **Save** to save the changes.

6. In the terminal now compile the code by typing or copying and pasting the following command followed by **Enter** or **return** key. **gcc** is a C program compiler. **-o** specifies the name of the output file.

``` bash
gcc -o hello helloworld.c
```

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/compile_on_terminal.png" width="50%">

7. To run the compiled file, type or copy paste the following command in the terminal and press enter. You will see the output of your first c program.

``` bash
./hello
```

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/c_hw.png" width="50%">

### Exercise 2: Display Hello World using Java


Java is an Object Oriented Programming language and is based on C++. It is one of the most used langauges for building secure and robust applications.

1. Click on the **File** menu and click on **New File** to create you first Java program.

2. Enter the file name as &#x60;helloworld.java&#x60; and press &#x60;OK&#x60;. 

> Java programs have the extension **.java**.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/newfile-name-save.png" width="50%">

3. This will open the file.

4. Copy and paste the following code into the file.

``` java
public class helloworld {
    public static void main(String s[]){
        System.out.println(&quot;Hello World!&quot;);
    }
}
``` 
This is how the file would appear on your window, after you paste the code and save it.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/java_code.png" width="50%">

5. Click on **File** menu and choose **Save** to save the changes.

6. In the terminal now compile the code by typing or copying and pasting the following command followed by **Enter** or **return** key. **javac** is a Java program compiler. By default the compilation output is stored in a file will the same name and **.class** extension.

``` bash
javac helloworld.java
``` 

7. To run the compiled file, type or copy paste the following command and press enter. You will see the output of your first Java program.

``` bash
java helloworld
``` 

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/java_hw.png" width="50%">

### Exercise 3: Display Hello World using Python

Python is a scripting language. It is run as is and you cannot compile and create executable file from them.

1. Click on the **File** menu and click on **New File** to create you first Python program.

2. Enter the file name as &#x60;helloworld.py&#x60; and press &#x60;OK&#x60;. 

> Python scripts have the extension **.py**.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/newfile-name-save.png" width="50%">

3. This will open the file.

4. Copy and paste the following code into the file.


``` python
print(&quot;Hello World!&quot;)
``` 
This is how the file would appear on your window, after you paste the code and save it.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/python_code.png" width="50%">

<Yes! That&#x27;s right. It is just a one line code in Python.

5. Click on **File** menu and choose **Save** to save the changes.

6. There is no compilation for Python code. To run the compiled file, type or copy paste the following command in the terminal and press enter. You will see the output of your first Python program.

``` bash
python helloworld.py
``` 

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/python_hw.png&quot; style&#x3D;&quot;width:75%;margin_bottom:1cm&quot;<
<img src="" width="50%">

### Exercise 4: Display Hello World using Node JS

JavaScript is a scripting language. Javascript was initially used only for executing code in the web pages. Node JS is scripting language for writing code that can be run. It is run as is and you cannot compile and create executable file from them just like Python.

1. Click on the **File** menu and click on **New File** to create you first Node js program.

2. Enter the file name as &#x60;helloworld.js&#x60; and press &#x60;OK&#x60;. 

<  Node.js scripts have the extension **.js**.

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/newfile-name-save.png&quot; alt&#x3D;&quot;Save file&quot; width&#x3D;&quot;65%&quot;< &lt;br<
<img src="" width="50%">

3. This will open the file.

4. Copy and paste the following code into the file.

``` js
console.log(&quot;Hello World!&quot;);
``` 
This is how the file would appear on your window, after you paste the code and save it.

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/node_code.png&quot; style&#x3D;&quot;width:50%;margin_bottom:1cm&quot;<
<img src="" width="50%">

<Yes! That&#x27;s right. It is just a one line code in Node.js too. This is why most people start learning coding with scripting languages.

5. Click on **File** menu and choose **Save** to save the changes.

6. There is no compilation for Node.js code. To run the compiled file, type or copy paste the following command in the terminal and press enter. You will see the output of your first Node.js program.

``` bash
node helloworld.js
``` 

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/node_hw.png&quot; style&#x3D;&quot;width:75%;margin_bottom:1cm&quot;<
<img src="" width="50%">

### Exercise 5: Display Hello World using Go

Go is a programming language. It is created by Google and is an Object-Oriented Programming language just like Java. It is now increasing in popularity.

1. Click on the **File** menu and click on **New File** to create you first Go program.

2. Enter the file name as &#x60;helloworld.go&#x60; and press &#x60;OK&#x60;. 

<  Go programs have the extension **.go**.

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/newfile-name-save.png&quot; alt&#x3D;&quot;Save file&quot; width&#x3D;&quot;65%&quot;< &lt;br<
<img src="" width="50%">

3. This will open the file.

4. Copy and paste the following code into the file.

``` go
package main

import &quot;fmt&quot;
func main() {
    fmt.Println(&quot;Hello World!&quot;)
}
``` 
This is how the file would appear on your window, after you paste the code and save it.

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/go_code.png&quot; width&#x3D;&quot;50%&quot;<
<img src="" width="50%">

5. Click on **File** menu and choose **Save** to save the changes.

6. Go code has to be compiled and executed like C and Java. But you can do that with one command. To comnpile and run the compiled file, type or copy paste the following command in the terminal and press enter. You will see the output of your first Go program.

``` sh
go run helloworld.go
``` 

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/go_hw.png&quot; style&#x3D;&quot;width:75%;margin_bottom:1cm&quot;<
<img src="" width="50%">

The exercises below are optional. It is only for you to do if you want to get a taste of more languages. You also have a bonus exercise at the end.

### (Optional) Exercise 6: Display Hello World using Ruby

Ruby is also a scripting language. It is predominantly used in data science and data analytics. It is run as is and you cannot compile and create executable file from them just like Python.

1. Click on the **File** menu and click on **New File** to create you first Ruby program.

2. Enter the file name as &#x60;helloworld.rb&#x60; and press &#x60;OK&#x60;. 

<  Ruby scripts have the extension **.rb**.

3. This will open the file.

4. Copy and paste the following code into the file.

``` ruby
puts &quot;Hello World!&quot;;
``` 
This is how the file would appear on your window, after you paste the code and save it.

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/ruby_code.png&quot; style&#x3D;&quot;width:50%;margin_bottom:1cm&quot;<
<img src="" width="50%">

<Yes! That&#x27;s right. It is just a one line code in Ruby as in other scripting languages too. This is why most people start learning coding with scripting languages.

5. Click on **File** menu and choose **Save** to save the changes.

6. There is no compilation for Ruby code. To run the compiled file, type or copy paste the following command in the terminal and press enter. You will see the output of your first Ruby program.

``` bash
ruby helloworld.rb
``` 

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/ruby_hw.png&quot; style&#x3D;&quot;width:75%;margin_bottom:1cm&quot;<
<img src="" width="50%">

### (Optional) Exercise 7: Display Hello World using PHP

PHP is also a scripting language. It stands for Hypertext Preprocessor. It is used for server side scripting. It is run by embedding it within special tags which recognize it as PHP code.

1. Click on the **File** menu and click on **New File** to create you first PHP program.

2. Enter the file name as &#x60;helloworld.php&#x60; and press &#x60;OK&#x60;. 

<  PHP files have the extension **.php**.

3. This will open the file.

4. Copy and paste the following code into the file.

``` php
<?php
Print &quot;Hello, World!\n&quot;;
>
``` 
This is how the file would appear on your window, after you paste the code and save it.

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/php_code.png&quot; style&#x3D;&quot;width:50%;margin_bottom:1cm&quot;<
<img src="" width="50%">

<Yes! That&#x27;s right. It is just a one line code in PHP as in other scripting languages too but it has to be embedded within the php tags for the interpreter to understand it is php script.

5. Click on **File** menu and choose **Save** to save the changes.

6. There is no compilation for PHP code. To run the compiled file, type or copy paste the following command in the terminal and press enter. You will see the output of your first PHP program.

``` bash
php helloworld.php
``` 

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/php_hw.png&quot; style&#x3D;&quot;width:75%;margin_bottom:1cm&quot;<
<img src="" width="50%">

### (Optional) Exercise 8: Display Hello World using C++

C++ is one of the first Object Oriented Programming languages that has been widely used for a few decades now. Java, Go and C# are all based on C++. You cannot run it as is. You need to compile it to obtain an executable form.

1. Click on the **File** menu and click on **New File** to create you first C++ program.

2. Enter the file name as &#x60;helloworld.cpp&#x60; and press &#x60;OK&#x60;. 

<  C++ files have the extension **.cpp**.

3. This will open the file.

4. Copy and paste the following code into the file.

``` C++
#include &lt;iostream<

int main() {
  std::cout &lt;&lt; &quot;Hello World!\n&quot;;
  return 0;
}
``` 
This is how the file would appear on your window, after you paste the code and save it.

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/cpp_code.png&quot; style&#x3D;&quot;width:50%;margin_bottom:1cm&quot;<
<img src="" width="50%">

5. Click on **File** menu and choose **Save** to save the changes.

6. In the terminal now compile the code by typing or copying and pasting the following command followed by **Enter** or **return** key. **g++** is a C++ program compiler. The executable output is stored in the filename specified.


``` bash
g++  -o helloworld_cpp helloworld.cpp
``` 

7. To run the compiled file, type or copy paste the following command in the terminal and press enter. You will see the output of your first C++ program.

``` bash
./helloworld_cpp
``` 

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/cpp_hw.png&quot; style&#x3D;&quot;width:75%;margin_bottom:1cm&quot;<
<img src="" width="50%">

### (Optional) Exercise 9: Display Hello World using Perl

Perl is also a scripting language. It is one of the older scripting languages and has been around for nearly 35 years. It is run as is and you cannot compile and create executable file from them just like Python.

1. Click on the **File** menu and click on **New File** to create you first Perl program.

2. Enter the file name as &#x60;helloworld.pl&#x60; and press &#x60;OK&#x60;. 

<  Perl scripts have the extension **.pl**.

3. This will open the file.

4. Copy and paste the following code into the file.

``` perl
print(&quot;Hello World\n&quot;);
``` 
This is how the file would appear on your window, after you paste the code and save it.

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/perl_code.png&quot; width&#x3D;&quot;50%&quot;<
<img src="" width="50%">

<Yes! That&#x27;s right. It is just a one line code in Perl too, as in other scripting languages too.

5. Click on **File** menu and choose **Save** to save the changes.

6. There is no compilation for Perl code. To run the file, type or copy paste the following command and press enter. You will see the output of your first Perl program.

``` bash
perl helloworld.pl
``` 

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/perl_hw.png&quot; style&#x3D;&quot;width:75%;margin_bottom:1cm&quot;<
<img src="" width="50%">

### (Optional) Exercise 10: Display Hello World shell script

Shell scripts are unique to UNIX operating system. It is one of the older scripting languages and is used for running system procedures predominantly. It is run as is like other scripting languages.


1. Click on the **File** menu and click on **New File** to create you first shell script.

2. Enter the file name as &#x60;helloworld.sh&#x60; and press &#x60;OK&#x60;. 

<  Shell scripts have the extension **.sh**.

3. This will open the file.

4. Copy and paste the following code into the file.

``` sh
echo &quot;Hello World!&quot;
``` 
This is how the file would appear on your window, after you paste the code and save it.
&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/sh_code.png&quot; style&#x3D;&quot;width:50%;margin_bottom:1cm&quot;<
<img src="" width="50%">

5. Click on **File** menu and choose **Save** to save the changes.

6. There is no compilation for Perl code. To run the file, type or copy paste the following command and press enter. You will see the output of your first shell script.

``` sh
sh helloworld.sh
``` 

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/sh_hw.png&quot;<
<img src="" width="50%">

### (Bonus) Exercise: Display Hello World with HTML on your browser

We worked on many programming and scripting languages. There is another kind called the Mark-up language. Many will be familiar with the most common markup language called the HTML. It stands for Hypertext Markup Language and is used for web-pages.


1. Click on the **File** menu and click on **New File** to create you first HTML code.

2. Enter the file name as &#x60;helloworld.html&#x60; and press &#x60;OK&#x60;. 

<  HTML code, usually referred to as HTML pages have the extension **.html**.

3. This will open the file.

4. Copy and paste the following code into the file.

``` html
&lt;html<
  Hello World!
&lt;/html<
``` 

This is how the file would appear on your window, after you paste the code and save it.

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/html_code.png&quot; style&#x3D;&quot;width:50%;margin_bottom:1cm&quot;<
<img src="" width="50%">

5. Click on **File** menu and choose **Save** to save the changes.

6. There is no compilation for HTML code. It is interpreted by the browser while rending. Right click on the filename and click **Download** to download it in your local machine.

&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/download_html.png&quot; width&#x3D;&quot;50%&quot;< &lt;br<
<img src="" width="50%">

7. Open on the downloaded file and it automatically opens in your default browser as below.


&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CS0131EN-SkillsNetwork/labs/Module_3/images/html_hw.png&quot; border&#x3D;&quot;2&quot;<
<img src="" width="50%">

### Practice Exercises

1. Create a python script named **greetings.py**. Display &quot;Hello &lt;yourname<! Good (Morning/Day/Evening/Night)&quot; using your python script.


&lt;details<&lt;summary<Click here for sample solution&lt;/summary<

``` python
print(&quot;Hello Liz! Good Evening!&quot;)
``` 
&lt;/details<

2. Create a php script named **oneliners.php**. Display three of your favorite oneliners, one after the other using your php script.


&lt;details<&lt;summary<Click here for sample solution&lt;/summary<

``` php
&lt;?php
Print &quot;If you don’t like the road you’re walking, start paving another one.\n&quot;;
Print &quot;The time is always right to do what is right.\n&quot;;
Print &quot;It is never too late to be what you might have been.\n&quot;;
?<
``` 
&lt;/details<

#### Congratulations! You just started your coding journey experimenting with different languages!

## Tutorial details

**Author:** Lavanaya T S

**Contributors:** Pallavi Rai

**Change Log**

| Date | Version | Changed by | Change Description |
|------|--------|--------|---------|
| 2022-09-09 | 1.0 | Lavanaya T S | Initial version created |
| 2023-10-06 | 1.1 | K Sundararajan | Instructions updated based on Beta testing  |

## <h3 style="align:center;">IBM Corporation 2023. All rights reserved. <h3>
