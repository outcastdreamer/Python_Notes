# Python_Notes
You can run the jupyter notebook online and learn while executing codes [here](https://colab.research.google.com/drive/17rIiiqaJVgtQjja44_Bdt_vg0ppateEH?usp=sharing) on google collab.
<br><b>Click on the file <u>"Python_Notes_by_Saket_Savarn.ipynb"</u> to get started with python!!<br></b>

<br>If you want to download and run the jupyter notebooks (.ipynb extension files) and are new to it and want to learn how to run it, refer to [this tutorial](https://www.youtube.com/watch?v=jZ952vChhuI).
<br>You can refer to the <b>html file</b> (Python_Notes_by_Saket_Savarn.html) as well but it can be only be used for viewing purposes (code execution is not possible).
<br>
<br>The reason for using jupyter notebooks is because it helps you add texts and run codes as well at the same time so it acts like an interactive textbook in which you can see the demo at that moment only.
<br> You can email me at saketsavarn07@gmail.com for any queries or doubts as well.
<br> I initially made this for my teaching assistant internship jobs.
<br><br> Hopefully you find them useful and easy to understand :D

<hr>
<br><br>
<b>--------------------------------------------------------------------------------------------------------</b>

<h1><center><font color = "red"><hr><b> Python 3.7 Class Notes </font></center></b></h1><hr>
<br>






<h1> Contents : </h1><br>

<a href="#Note from the Author">Note from the Author</a>
<br>
<br>
1. <a href="#1. Introduction to Python">Introduction to Python</a><br>
2. <a href="#2. Features of Python">Features of Python</a><br>
3. <a href="#3. Domain of Python">Domain of Python (What is Python used for?)</a><br>
4. <a href="#4. Installing and setting-up Python">Installing and setting up Python</a><br><br>
5. <a href="#5. Python Basic Fundamentals">Python Basic Fundamentals (Syntax Basics)</a><br>
    a. <a href="#5A Flow of Code">Flow of Code</a><br>
    b. <a href="#5B Semi-colons in Python">Semi-colons in Python</a><br>
    c. <a href="#5C Indentation in Python">Indentation in Python</a><br><br>
6. <a href="#6 Commenting in Python">Commenting in Python</a><br>
    a. <a href="#6A Single line commenting in Python">Single-line commenting in Python</a><br>
    b. <a href="#6B Multi-line commenting in Python">Multi-line commenting in Python</a><br><br>
7. <a href="#7 Variables & Variable Assignment in Python">Variables & Variable Assignment in python</a><br><br>
8. <a href="#8 Print function in Python">Print function in Python</a><br>
    a. <a href="#8A Single-line printing in Python">Single-line printing in Python</a><br>
    b. <a href="#8B Escape sequence in Python">Escape Sequence in Python</a><br>
    c. <a href="#8C Multi-line printing in Python">Multi-line printing in Python</a><br><br>        

9. <a href="#9 Primary data types in Python">Primary Data-types in Python</a><br>
    a. <a href="#9A Integer data type">Integer Data-Type</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;i. <a href="#9A i. Addition">Addition Operator</a>(+)<br>
    &nbsp;&nbsp;&nbsp;&nbsp;ii. <a href="#9A ii. Subraction">Subraction Operator</a>(-)<br>
    &nbsp;&nbsp;&nbsp;&nbsp;iii. <a href="#9A iii. Multiplication">Multiplication Operator</a>(\*)<br>
    &nbsp;&nbsp;&nbsp;&nbsp;iv. <a href="#9A iv. Division">Division Operator</a>(/)<br>
    &nbsp;&nbsp;&nbsp;&nbsp;v. <a href="#9A v. Double Division">Double Division Operator</a>(//)<br>
    &nbsp;&nbsp;&nbsp;&nbsp;vi. <a href="#9A vi. Modulus">Modulus Operator</a>(%)<br>
    &nbsp;&nbsp;&nbsp;&nbsp;vii. <a href="#9A vii. Exponential">Exponential Operator</a>(\**)<br>
    b. <a href="#9B Float data type">Float Data-Type</a><br>
    c. <a href="#9C String data type">String Data-Type</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;i. <a href="#9C i. Declaring string values">Declaring String Values</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;ii. <a href="#9C ii. String concatenation in python">String Concatenation</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;iii. <a href="#9C iii. Indexing and slicing strings">Indexing & Slicing Strings</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;iv. <a href="#9C iv. String properties">String Properties</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;v. <a href="#9C v. String methods & functions">Basic str methods & functions</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;vi. <a href="#9C vi. String methods">Methods used with str</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;> <a href="#9C vi.> Len and type">Some Important Functions in Python (len() & type())</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;vii. <a href="#9C vii.String functions">Functions used with str</a><br>
    d. <a href="#9D Boolean data type">Boolean Data-Type</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;i. <a href="#9D i. Comparison Operators">Comparison Operators in Python</a><br>
    e. <a href="#9E Complex data type">Complex Number Data-Type</a><br>
    f. <a href="#9F None data type">None Data Type</a><br><br>
10. <a href="#10. Looping Statements in Python">Looping Statements in Python (For & While Loops)</a><br>
    a. <a href="#10. i Need for looping statements in python">Need of Looping Statements</a><br>
    b. <a href="#10. ii For loop staments">For Loops in Python(Syntax & Usage)</a><br>
    c. <a href="#10. iii Nested for loop">Nested For Loops</a><br><br>




<br>
<br>
<a id="Note from the Author"></a>

---
<h3><b>Note from the Author</b></h3>

---

Hi! My name is [Saket Savarn](https://outcastdreamer.github.io/)!!<br>I am currently studying in my 3rd Year of B.Tech CSe at REVA University.
The reason for me writing and documenting these Python Notes is to make it easier for me to provide the notes for the workshops and my internships where I teach Python frequently.<br>
It also is for my reference purposes so that I can refer to all the concepts I have studied and also because it reinforces my python concepts as well.<br>
Having said that I am pretty sure there will be bugs, grammatical errors, and few other kinds of errors here and there that I still need to verify and rectify. <br>
In case you come across such bugs or errors feel free to email me at saketsavarn07@gmail.com and I will rectify them as soon as possible.
<br>
In the end I hope the notes are a useful resource to you and that my sessions where helpful in getting you started with python.<br>
I am also sorry for the huge delay it takes me in updating these notes. As I said before, I am held busy by my multiple internships and workshops at a time and hence don't get the time to keep updating it, but I still try my best to update it whenever I get the time.
<br>
With all that done, I hope you keep learning!!<br>
<br>
<b><u>Contact Info + Me around the web</u> : </b>
<ul><li><a href ="https://www.instagram.com/outcast_dreamer/">  Instagram or @outcast_dreamer </a></li>
<li><a href="https://github.com/outcastdreamer">Github Profile</a></li>
<li>Email : <a href="">saketsavarn07@gmail.com</a></li>


<br>
<br>
<a id="1. Introduction to Python"></a>

---
<h3> <b><u>1. Introduction to Python</b></u></h3>

---
Python is an interpreted, high-level, general-purpose programming language. Created by Guido van Rossum and first released in 1991
Python is dynamically typed and garbage-collected. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming. Python is often described as a "batteries included" language due to its comprehensive standard library. <br>
Python is considered both as a scripting and programming language by most developers as it has support of scripting language as well.
The reason for considering it as a "scripting language" is because of the ease of coding, automation, deployment and various other reasons. The topic of whether python is a scripting language or just proramming language is hugely debated till now by developers.
<br>
<br>
<u>Keywords to go through in above definition : </u><br>
<b>1. Interpreted Language :</b> Interpreted Language specifies that a language can be freely and directly be executed without the need of compiling the code. In case of python, when in *interpreter mode* , one can get the output then and there itself without the need of saving the file and then compiling it. This means even the errors are denoted then and there at that line only and it wll not wait till the completion of the code to tell all the errors in one go. One can go to interpreter by searching for "python" in windows search or typing it in cmd or terminal to directly enter it. In case of windows, if the *system environment variables* has been configured properly, you will see the python version and the prompt symbol ">>>". <br>
A <b>">>>"</b> (called 'python prompt') specifies an active line waiting for your command, while "..." specifies a continued line of code (in case of for loop, if-else, and basically any statements or code that is followed by a colon ":").<br><br><br>

<b>2. Dynamically typed language :</b> Dynamically typed language in layman language means that python doesn't statically limit the coder to one data type for any variable unlike in case of C,C++ or Java. <br><br>&nbsp;<b><u>Eg:</u></b> In case of C or C++ lang, if we declare : 

>
> > #include <stdio.h><br>
> > main() <br>
> > { <br>
> > &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;int a; <br>
> > &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a = "hello"; <br>
> > } 
>

&nbsp;you cannot declare, a = "hello" or a = 1.2, as 'a' variable is only int &nbsp;type and it will give error. We can only declare 'a' as a = 79, for example or integer type.
<br><br>But in case of python, we directly declare "value" and not the "data-type" because python by default understands the data-type based on the value you assigned to the variable. This also means you can change the data-type of the variable to any type. This is why python is called "Dynamically typed" and not "statically typed".
<br><br>&nbsp;<b><u>Eg:</u></b>



```python
a = 1
print (a)  #print() function is used to display output in python and is similar to printf(); in C language.

a= "Hello world!"
print (a)

a = 4.57
print (a)
```

    1
    Hello world!
    4.57
    

(I will be explaining "print" and how to declare variables in python in later stages of the notes, though it should be self explanatory for most of you.)<br> Here we can see that the value of variable 'a' is not declared specifically, we just declare the value, say a = 10. We don't say : <br>
>
> > int a = 10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//C or C++ example
>
>

We can also observe from the above code snippet that the value of a could be overwritten to any data type. Be it string, integer or float.
<br>
<br>
<br>
<b>3. Garbage-collected language :</b> Garbage collection (GC) is a form of automatic memory management. The garbage collector, or just collector, attempts to reclaim garbage, or memory occupied by objects that are no longer in use by the program and clears them without need of the programmer to do so on their own.  
<br>
<br>
<b>4. Functional programming language :</b> Functional programming language is most of the time built on Object-oriented programming and allows one to use functions to reduce the need of coding, in their place by using functions. Here these functions are imported using libraries or modules by python which are basically classes which have these functions which act like objects.<br><br> For example, we have functions for string data-type where-in string data-type also acts like a class/module/library and offers functions like lower(), upper(), join(), etc {More about this later}.




<br>
<br>
<a id="2. Features of Python"></a>

---
<h3> <b>2. <u>Features of Python</b></u></h3>

---
1. Human-friendly code readibility and understanding.
2. Easier to code with due to availability of "Functional-programming".
1. Vast number of libraries and modules that reduce the amount of coding needed to be done drastically.
2. Easy to work with in many domains of computer science.
1. Can be deployed across various platforms and OS.
2. Very simple and easy to learn even for beginners.
1. Free and open-source language that is easy to install, set-up and get started with.
2. It can be integrated with other languages such as C,C++ and Java. See [Cython](https://cython.org/), [Jython](https://www.jython.org/), etc.

<br>
<br>
<a id="3. Domain of Python"></a>

---
<h3> <b>3. <u>Domain of Python (What is Python used for?)</b></u></h3>

---
1. Python is used for making desktop applications using GUI programming for various OS like windows, linux, mac, etc. At times the front-end is made using languages like JAVA while back-end is made using python as JAVA is easier to use for making GUI or front-end while python is good for back-end.
2. It is used in the trending topics like Machine learning, artificial intelligence and deep learning. This is because any developer can install and import modules/libraries with all the machine learning algorithms already provided in them which can be used as functions (aspect of "functional prog.") hence all we need to do is provide the relevant datasets and information and train it by invoking the functions. Python supports all domains of ML, AI and DL like image processing, Natural Language Processing (NLP), chat bots, etc.
3. It's used by scientists in scientific researches (like by NASA scientists for space exploration,SUPER Computers, etc).
4. It's used for web-developement in back-end using modules like Flask and django.
5. It's used in various scripts in hacking and cyber security such as tracking sub-domains of websites, DDOS attacking, etc.
6. It's used in data-mining, web scrapping, to download data in back-end in bulk.
7. It's used in data-visualization for busiess analytics, etc.
8. It's used for automation of various tasks such as automated data-mining or automated sub-domain tracking,etc.
9. It's also used rarely for game and mobile app developement.
10. It's used in embedded systems like Rasberry pi, etc. for IoT (Internet of Things) products.
11. Many other domains like open-source projects, APIs, extensions, plugins construction and deployment, etc.
12. It also has applications in cloud computing, blockchain and many buisness enterprises.


<br>
<br>
<a id="4. Installing and setting-up Python"></a>

---
<h3> <b>4. <u>Installing and setting-up Python</b></u></h3>

---
First things first, make sure that you are sure about your system/laptop configurations. If you are on windows check so on by searching (Win key + s) "system information".
<br> If you have x64 based system then click on the following -> [link](https://www.python.org/ftp/python/3.7.4/python-3.7.4-amd64.exe).
<br> If you have x32 based system then click on the following -> [link](https://www.python.org/ftp/python/3.7.4/python-3.7.4.exe).
<br> The links above will download Python 3.7.4 which is the latest as of the time of writing this. (17th Oct, 2019).
In case you want to download or check for newer updates you can go to www.python.org and check for the same.

While installing make sure <b>"Add to path"</b> option is selected so that your python is added to the "system environment variables" which basically consists of path to tell the cmd where the applications are stored so that you can use it via your cmd or terminal.<br> 
<b>(Note : </b> Make sure that you don't have any other versions of python installed when choosing "Add to Path" option or there might be clash between the other versions of python which are already installed with this one.)<br><br>
After installation of python, open cmd (win key + r, and then type in cmd) and type in python (make sure it's all lowercase).

Similarly, I would suggest installing [Sublime Text Editor 3](https://www.sublimetext.com/3) as your editor and try to avoid installing Pycharm and such IDEs as they hamper growth by telling error beforehand hence stopping learning through mistakes and debugging for beginners. You can also set sublime to work from cmd by adding its installation path to environment variables and using the keyterm "subl" to run it from cmd.

In-case it says "python not found" in cmd, follow this [tutorial](https://www.youtube.com/watch?v=Y2q_b4ugPWk) to set-up environment variables.




<br>
<br>
<a id="5. Python Basic Fundamentals"></a>

---
<h3> <b>5. <u>Python Basic Fundamentals (Syntax Basics)</b></u></h3>

---
<a id="5A Flow of Code"></a>
<br><b>(a.)Flow of Code </b><br>
Just like how we read books from top to bottom and left to right, the flow of the code works in the same way usually in python as well (Just like how it's done in C, C++ or Java). The [python interpreter]() reads the code from the 1st line to the last line provided there aren't any jump statements like function calls or decision/conditional statements or looping statements that would make a piece of code loop again and again until a specific condition is met. This is important to keep in mind as we have to make sure the right line of code is being executed at the right time or else we won't get the desired results. 

<a id="5B Semi-colons in Python"></a>
<br><b>(b.) Semi-colons in Python </b><br>
Unlike C, C++ languages, Python doesn't require a semi-colon (;) to end a line of code. The python interpreter itself understands a new line as end of that line of code. Even though semi-colon isn't required, python still supports usage of semi-colon and is used the same way as in C & C++. It can be used to write two lines of code in one by using a semi-colon
to end them. Since, python reads the code from left to right as mentioned above, the left-most statement will be considered first then the ones following it after the semi-colon. Eg:<br>
<code>a = 1; b = 2;</code><br>
and
<code>
a = 1
b = 2</code><br>
Both are valid in python.
<br>

<a id="5C Indentation in Python"></a>
<br><b>(c.) Indentation in Python </b><br>
Another thing to keep in python is that unlike C & C++ which use Curly Braces {} to refer to a block of code belonging to
a conditional or loop statement (if-else, for or while loop), Python uses <b>Indentation</b> to indicate which block of code is under a conditional or loop statement. Since explaining in text is not easy, I would suggest [watching this](https://www.youtube.com/watch?v=igFtmXV_9vE) short video to get a clearer idea, with further examples in loopa and conditional statements below it will become clearer what indentation is.

      

<br>
<br>
<a id="6. Commenting in Python"></a>

---
<h3> <b>6. <u>Commenting in Python</b></u></h3>

---

Comments are used for adding personal instructions or lines that the compiler or interpreter ignores. This allows the developer to add lines to further explain his/her code to other developers who might go through your code later or even allow the creator to remember what a specific region of code did.

<h4><u><b>Why commenting is important : </u></b></h4>
<li> Sometimes you have projects spanning with over 100 to thousands of lines of codes. One person can't possibly remember what a specific region of code does in thousands line of codes and hence adding comments allows one to understand the context of the code.</li>
<li> It's a crucial part of documentation and is evident in many open source projects, etc that you will find online.</li>
<li> It allows other coders going through your code to understand your code better as everyone has different coding style. It's important if you are working on a project with a team.</li>
<br>
The best code practice is when your code is readiable from the get go though, without the need of explaining.
<br><br>
<b>NOTE : </b> Since this is a tutorial kind of book, I will be using a lot of comments through the code, kindly keep keen eye for them as I will be explaining in much more detail with them.


<a id="6A Single line commenting in Python"></a>
<u><b> (a.) Single-line commenting in Python: </b></u><br>
We use Hash<code>(#)</code> symbol while commenting in single line in python. This is handy if we want to comment a specific line of the code to disable it and see how the output of the code works. Eg : 


```python
#Example of single line commenting in python

a = 2
b = 4
print ("This statement will get printed")  #This statement won't be displayed or get printed as it is a comment
print ("Value of a is : ",a)
#print (b) 
#the above line is a comment just as this line. Try uncommenting by removing the hash (#) before print (b) statement.

```

    This statement will get printed
    Value of a is :  2
    

<a id="6B Multi-line commenting in Python"></a>
<br><br><b><u>(b.) Multi-line commenting in python</u> : </b>
<br>Mutli-line commenting means commenting multiple lines in one go. This is useful when you want to comment out a whole specific block of codes (multiple code statements) unlike just one or two statements. For example you can comment out a whole for loop if you think it's causing errors in your code and see if your code works with it or without it.<br><br>
You can do multi-line commenting in python using triple quotes <code>""".</code>Just type everything inside the triple quotes and enclose it by them.
<br>
<br>
Eg : 
  




```python
#Example of Multi-line commenting in python

#This is a single line comment using hash (#)
"""
Look this is the first line.
The second line.
The third line.
And all these lines are comments. The below code won't be executed : 
a = 2
print (a)
"""

print ("This is not a comment")
```

    This is not a comment
    

<br>
<br>
<a id="7 Variables & Variable Assignment in Python"></a>

---
<h3> <b>7. <u>Variables & Variable Assignment in Python</b></u></h3>

---
Variables are used to assign
<b><h4>Variable names :</h4></b>
Couple of rules to follow when naming your variables 
<ul>
<li>Variable names can contain letters, numbers, and the underscore.</li>
<li>Variable names cannot contain spaces.</li>
<li>Variable names cannot start with a number or contain any other symbols besides underscore.</li>
<li>Case matters—for instance, temp and Temp are different.</li>
<li>Since python is dynamically typed, declaring data-type with variables isn't required </li>
</ul><br><b>Eg : </b><br>

    



```python
a = 1   #Notice how we don't need to declare data-types for variables like in C & C++ due to dynamic-typing
        #as mentioned above Python automatically detemines variable, 'a' holding an int value.
b = "hello"  #Python automatically determines variable 'b' holding a string value
c = 4.2      #Python automatically determines varaible 'c' holding a float value

#We can also assign values in various other ways like :
a = 1; b = "hello"; c = 4.2;   #One line assignment using semi-colons

#We can also use another method for assigning values to variables :
a,b,c = 1,"hello",4.2  #This method unpacks the int value 1 to variable 'a' as both are on extreme left
                       #string value "hello" is assigned to variable 'b' as both are in middle
                       #float value 1.2 is asssigned to variable 'c' as both are on extreme right
        
#Even though we have assigned values to variables 'a', 'b' and 'c', we cannot display them or use them without
#printing or getting an output for them. This can be done using the print() function in python.
```

<br>
<br>
<a id="8 Print function in Python"></a>

---
<h3> <b>8. <u>Print function in Python</b></u></h3>

---
<code>print()</code> function is similar to <code>printf();</code> function in C & C++. But unlike C & C++ it doesn't need necessarily need a type specifier (%d, %s, %f) etc to print values of variables. You can directly print the value or the variable holding the value without using the type-specifier for the data-type that value belongs to. In python 2.7, print was a [keyword](https://www.programiz.com/python-programming/keywords-identifier#:~:text=Keywords%20are%20the%20reserved%20words,33%20keywords%20in%20Python%203.7.) and hence did not require any paranthesis or brackets () after it, but from Python 3, print() is a function and hence it requires paranthesis which in which we pass the values or variables we want to print the output of.
<br>
<a id="8A Single-line printing in Python"></a>
<b>(a.) Single line printing in Python</b><br>
Eg : 


```python
print ("This is a single line print ")
a,b,c = 1,"hello",4.2

#We use commas to seperate the values we want to print, below we are telling python to 
#print the string value "The value of a is" followed by a comma to tell python the next value we want to print
#after the string value "The value of a is" and after the comma we mention the variable "a" to make python
#Print it's value.

print ("The value of a is")        #Value of variable 'a' won't be printed as we haven't mentioned it here
print ("The value of a is : ",a)   #Notice how we don't need to necessarily use type-specifier %d to print value of var a.
print ("The value of b is : ",b)   #%s isn't necessarily required for printing value of b.
print ("The value of c is : ",c)   #
```

    This is a single line print 
    The value of a is
    The value of a is :  1
    The value of b is :  hello
    The value of c is :  4.2
    

<br><br>
<a id="8B Escape sequence in Python"></a>
<b>(b.) Escape Sequence in Python</b><br>The above statements are printed just fine but I feel like there is little too less gap between each print statement.
We can add empty new lines , empty tab spaces, etc using ["escape sequence or escape character"](http://www.python-ds.com/python-3-escape-sequences) to make our output more pretty.<br>
<b>"\n"</b> and <b>"\t"</b> are the two most commonly used escape sequences and are used in many other programming languages like C,C++,Java, etc.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<li><b>\n</b> : It is used to print an empty new line. Usually used to add spaces between two print statements.</li>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<li><b>\t</b> : It is used to print an empty tab space (Usually 4 to 8 combined spaces) before or after a statement.</li><br> 
<b>Eg: </b>


```python
print ("\n\nThe values of variables 'a','b' and 'c' are : ")
print ("\n\tThe value of a is : ",a,"\n")  #You can add \n at end as well to create the next new line 
print ("\tThe value of b is : ",b)   
print ("\n\tThe value of c is : ",c)       #Here the new line has been added in beginning instead of last of previous
                                           #print statement
```

    
    
    The values of variables 'a','b' and 'c' are : 
    
    	The value of a is :  1 
    
    	The value of b is :  hello
    
    	The value of c is :  4.2
    

---
<a id="8C Multi-line printing in Python"></a>
<b>(c.) Multi-line printing in Python</b> :<br>
We use <code>"""</code> triple quotes just like in case of multi-line in commenting (Topic 5 in contents) comments for multi-line printing. See the following examples below :  


```python
#Multi-line printing in python

print ("""
 This is a sentence. This is a second sentence!
 The third sentence. This sentence is fourth.
 Fifth sentence is this one. 
 """
)
```

    
     This is a sentence. This is a second sentence!
     The third sentence. This sentence is fourth.
     Fifth sentence is this one. 
     
    


```python
#Multi-line printing in python (Example 2)

print ("""
	\n
___________________________________ 
< I am an ASCII Art Dragon > 
 ----------------------------------- 
      \                    / \  //\ 
       \    |\___/|      /   \//  \\ 
            /0  0  \__  /    //  | \ \     
           /     /  \/_/    //   |  \  \   
           @_^_@'/   \/_   //    |   \   \  
           //_^_/     \/_ //     |    \    \ 
        ( //) |        \///      |     \     \ 
      ( / /) _|_ /   )  //       |      \     _\ 
    ( // /) '/,_ _ _/  ( ; -.    |    _ _\.-~        .-~~~^-. 
  (( / / )) ,-{        _      `-.|.-~-.           .~         `. 
 (( // / ))  '/\      /                 ~-. _ .-~      .-~^-.  \ 
 (( /// ))      `.   {            }                   /      \  \ 
  (( / ))     .----~-.\        \-'                 .~         \  `. \^-. 
             ///.----..>        \             _ -~             `.  ^-`  ^-_ 
               ///-._ _ _ _ _ _ _}^ - - - - ~                     ~-- ,.-~ 
                                                                  /.-~ 
\n
""")
```

    
    	
    
    ___________________________________ 
    < I am an ASCII Art Dragon > 
     ----------------------------------- 
          \                    / \  //\ 
           \    |\___/|      /   \//  \ 
                /0  0  \__  /    //  | \ \     
               /     /  \/_/    //   |  \  \   
               @_^_@'/   \/_   //    |   \   \  
               //_^_/     \/_ //     |    \    \ 
            ( //) |        \///      |     \     \ 
          ( / /) _|_ /   )  //       |      \     _\ 
        ( // /) '/,_ _ _/  ( ; -.    |    _ _\.-~        .-~~~^-. 
      (( / / )) ,-{        _      `-.|.-~-.           .~         `. 
     (( // / ))  '/\      /                 ~-. _ .-~      .-~^-.  \ 
     (( /// ))      `.   {            }                   /      \  \ 
      (( / ))     .----~-.\        \-'                 .~         \  `. \^-. 
                 ///.----..>        \             _ -~             `.  ^-`  ^-_ 
                   ///-._ _ _ _ _ _ _}^ - - - - ~                     ~-- ,.-~ 
                                                                      /.-~ 
    
    
    
    

<br>
<br>
<a id="9 Primary data types in Python"></a>

---
<h3><b>9. <u>Primary Data-types in Python</b></u></h3>

---
There are two types of data-types in python in layman terms. 
1. Primary Data type
2. Secondary Data type or Container Data type

<b>Primary Data type :</b> <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
It consists of the following data types :
* Int or Integer (Denoted by %d as a placeholder)
* Float or decimal numbers (Denoted by %f as  a placeholder)
* String (Denoted by %s as a placeholder)
* None data type
* Boolean data type (Denoted by True/1 or False/0 as reserved keywords)
* Complex Numbers <br>
<br>

<b>Secondary Data type :</b>
It contains primary data types (the ones mentioned above) as it's elements or values, basically they are container data types that consist of various primary data type values stored in them which allows us to store multiple values of any data type and assign to just one variable. This reduces of stating multiple variables for similar values.
* Lists (Arrays variation of C and C++ Lang for python)
* Tuples (Basically immutable python lists)
* Sets
* Dictionaries (Comsists of keys mapped to values, unordered (don't follow any order such as index, keys&Values can be in any order)
* Collections (ordered dictionaries)
* Numpy, etc (Numerical arrays for scientific and machine learning projects)


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; All these data types have unlimited memory allocation (which implies it depends on one's PC memory limits, this also means you don't need to assign size of array, string, etc like in case of C/C++ as python has unlimited memory allocation and also automated garbage collector which works hand in hand with dynamic typing.) Unlike in C/C++ where you initialize strings as : <br>
> char a[10];

<br>You can just declare,<br>
<code>a = "hello"</code> or <br><code>a = "This sentence can be as long as you want without the need of declaring the number of characters in it, really you can stretch it as long as you want it to."</code>
<br><br>
Here all the data types except int and float are also treated classes/modules/libraries because int and float data types are only meant to be used for mathematical operations like addtion, subraction, etc.
<br><br>

<hr><br>
<a id="9A Integer data type"></a>
<h3><u><b>(a.) Integer Data-Type (int)</b></u></h3><br>
<u><b>Declaring int value :</b></u><br>
We use '=' as the assignment operator which assigns values to the variable.<br> 
<code>a = 1<br>
b = 2<br>
a = 1; b = 2<br>
a, b = 1, 2 <br></code>All work. Here 'a' & 'b' are variables holding the values 1 and 2 throughout the whole example. You can use semi-colons like in C/C++ to seperate variables and statements but I wouldn't suggest to use them everywhere also keep in mind, if you do a,b = 1,2,3 you will get error as python expects at least 3 variables in this case, so you would have to do a,b,c = 1,2,3.<br><br><b>Note :</b> By the way, these declaration methods work for float, strings, and all other various data types. <br>
<br><u><i>Working with integers :</i></u><br>
Before working with integers you need to know what are operators and their uses. You must have used them in maths before (if you haven't, what are you doing in your life anyway :v)

<br>





<b> Operators in python :</b>
<ul><li> Addtion (+) </li>
<li> Subraction (-) </li>
<li> Multiplication (<b>*</b>) </li>
<li> Division (/) {Gives float value as quotient} </li>
<li> Double Division (//) {Gives int value as quotient} </li>
<li> Modulus (%) {Returns remainder} </li>
<li> Exponential (<b>**</b>) {Returns the raised to power of a number} </li></ul<

<br>

<hr><br>
<a id="9A i. Addition"></a>
<br><br><u><b>i.) Addition operator : '+'</b></u>
(Adds two or more numbers)<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Eg : >>> a = 1; b = 2; c = a+b+2
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> print (c)
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;#(Answer will be 5)
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> c + = 1 
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> print (c)
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;#(Answer will be 6 now)
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c + = 1 is equaivalent to c = c + 1 (since c = a+b+2 was equal to c = 5, c + = 1 implies,<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c = c + 1, which in turn implies, c = 5 + 1, c = 6)
<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Note :** In python pre-increment or post-increment like in case of C/C++ doesn't exist, therefore we cannot use a++ or ++a, but we can use a+=1.
<br><br>


```python
#Addtion Example (+)

a = 1; b = 2; c = a+b+2
print ("Initial value of c : ",c)
c+=1
print ("Updated value of c : ",c)
c+= 2
print ("The new updated value of c is : ",c) 
```

    Initial value of c :  5
    Updated value of c :  6
    The new updated value of c is :  8
    

<b>----------------------------------------------------------------------------------------------------------------------------------------------</b><br>
<a id="9B ii. Subraction"></a>
<u><br><br> <b>ii.) Subraction Operator : '-'</b></u> 
(Subracts two or more numbers)</u>
<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Eg : >>> a = 5; b = 7; b - = 1; a = a - b;
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> print (a)
<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(Answer is -1)<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; As b - = 1 => b = 7 - 1 => 6, and then a = a - b => a = 5 - 6 = -1<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; orrrrrrrr <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; just do the maths bruh.
<br>
<br>



```python
#Subraction (-)
a, b = 5, 7   #Here a=5,b=7
b-=1  
"""Sometimes, running the same command such as : b - = 1 (just added spaces in the same statement) causes errors. 
So we cannot use spaces everywhere."""
a = a - b;
print ("The value of a is : ",a)
```

    The value of a is :  -1
    

<b>----------------------------------------------------------------------------------------------------------------------------------------------</b><br>
<a id="9A iii. Multiplication"></a>
<b><u>iii.) Mutiplication Operator : '(\*)'</b></u> (Mutliplies two or more numbers)
<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Eg : >>> a = 5; b = 7;  c = a * b;
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> print (c)
<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(Answer is 35)
<br>
<br>



```python
#Multiplication (*)
a = 5; b = 7; c = a * b;
print (c)
```

    35
    


<b>----------------------------------------------------------------------------------------------------------------------------------------------</b>
<a id="9A iv. Division"></a>
<br><br><b><u>iv.) Division Operator : '/'</b></u>
 (Divides two or more numbers)
<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>Eg : >>> a = 15 ; b = 5 ;  c = 2 ; d = 150 ; e = a/b ; f = a/c ; g = a/d</code>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> print (e," and ",f," and ",g)
<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(Answer is 3.0 and 7.5 and 0.1)
<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Note :** Notice how the output is 3.0 and not 3, this shows just using a single / returns float value as quotient even if the output is completely divisible like in case of 15/5. Also notice how 15/150 is 0.1
<br>
<br>



```python
#Division (/)
a = 15; 
b = 5  
c = 2  
d = 150  
e = a/b; 
f = a/c ; 
g = a/d
print ("Value of e is :",e,",and of f is :",f,",while of g is :",g) 
#Compare this to output of below code block of double division operator
```

    Value of e is : 3.0 ,and of f is : 7.5 ,while of g is : 0.1
    


<b>----------------------------------------------------------------------------------------------------------------------------------------------</b><br><br>
<a id="9A v. Double Division"></a>
<u><b>v.) Double division Operator : '//'</b></u>
 (Divides two or more numbers but returns integer quotient instead of a float quotient)
<br></u> <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Eg : >>> a = 15; b = 5;   c = 2; d = 150; e = a//b; f = a//c; g = a//d
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> print (e," and ",f," and ",g)
<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(Answer is 3 and 7 and 0)
<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Note :** Notice how the output is 3 and not 3.0, this shows the output while using // is always int. We can observe the same for 15//2 which returns 7 and doesn't return the correct answer which is 7.5, hence it will ignore any value past decimal as in case of 15//150 which just returns 0 as quotient.
<br>
<br>



```python
#Double-division (//)
a = 15; b = 5; 
c = 2; d = 150
e = a//b; 
f = a//c; 
g = a//d
print ("Value of e is :",e,",and of f is :",f,",while of g is :",g) 
#Compare this to above code block output of division operator.
```

    Value of e is : 3 ,and of f is : 7 ,while of g is : 0
    


<b>----------------------------------------------------------------------------------------------------------------------------------------------</b>
<a id="9A vi. Modulus"></a>
<br><br><u><b>vi.) Modulus Operator : '%'</u></b>
 (Returns remainder)
<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Eg : >>> a = 15; b = 5;   c = 2; d = a%b; e=a%c
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> print (d," and ",e)
<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(Answer is 0 and 1, as the remainder for 15//5 is 0 and for 15//2 is 1)
<br>
<br>



```python
#Modulus (%)
a = 15; b = 5; c = 2; 
d = a%b; e=a%c
print ("Value of d is :",d,"\nand value of e is:",e)   
#\n is used to print to new line. \n is called an escape squence, 
#it is a special charater reserved in many coding languages.
```

    Value of d is : 0 
    and value of e is: 1
    


<b>----------------------------------------------------------------------------------------------------------------------------------------------</b>
<a id="9A vii. Exponential"></a>
<br><br><u><b>vii.) Exponential Operator : (\*\*)</b></u>(Raises two numbers)
<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Eg : >>> a = 4; b = 4;   
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> print (a<b>**</b>2," and ", a<b>**</b>b, " and ", a<b>**</b>0.5)
<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(Answer is 16 and 256 and 2.0)
<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Note :** 4^2 or 4 to the power 2 or 4 raised to 2 is 16 (4x4=16), 4^4 is 256 (4x4x4x4=256) and 4^0.5 is (4)^1/2 which basically means underoot of 4. Notice that the output is 2.0 for 4^0.5 not 2, as we are using 0.5 which is a float value so we get a float output. Similarly, if we did 
4^2.0 instead of 4^2 we would get 16.0 not 16. This is true for all operators, integer and operator and float = float ouptput. Eg : 4<b>*</b>2.0=8.0 (Here, ^ denotes <b> ** </b> operator)



```python
#Exponential (**)
a = 4; b = 4;
print ("\'a\' raised to power of 2 is:",a**2,"\nand \'a\' raised to power of b is :", a**b, "\nand \'a\' raised to 0.5 is:", a**0.5)

#\' \' Is used to treat single quotes here as raw string, meaning as string itself, as using them without slash (\) would make python think
#that we are using it to encapsulate a string (basically single quotes are also used to print and assign string value, so to not use them for
#declaration but for printing purposes we use the slash (\)).
```

    'a' raised to power of 2 is: 16 
    and 'a' raised to power of b is : 256 
    and 'a' raised to 0.5 is: 2.0
    

<br><br><hr><br>
<a id="9B Float data type"></a>
<h3><u><b>(b.) Float Data type (float)</b></u></h3><br>
<u><b>Declaring float value :</b></u><br>
We use '=' as the assignment operator which assigns values to the variable.<br> 
a = 1.2<br>
b = 2.5<br>
a = 1.2; b = 2.5<br>
a,b = 1.2,2.5 <br>All work. Here 'a' & 'b' are variables holding the values 1.2 and 2.5 through the whole example. Basically it's the same as declaring int or string  values.
<br><br><u><b>Working with floats :</b></u><br>
It's the same as integer values in python (I mean floats are just integers in the end but they have a point, so obviously it works just the same). Operators like addition, subraction, multiplication, division, modulus, all the operators mentioned above work.


```python
#Float data type

#Try using operators with float values like the above examples here. I have done one for you

a= 1.2 #spaces between variable and = (assignment operator) does not matter.
b =4.2
#though it is a good idea to practise standard spacing like in above examples, like this : a = 1.2
print ("The product of \'a\' and \'b\' is :",a*b)
```

    The product of 'a' and 'b' is : 5.04
    

<br><br><hr><br>
<a id="9C String data type"></a>
<h3><u><b>(c.) String Data type (str)</b></u></h3><br>
<br>
Unlike int and float values which can only be used for maths and with operators, we can do a lot with strings, like : concatenation of strings, reversing a string, slicing strings, capitalizing them, etc and hence python treats string not just like a datatype but as a module/library  also, meaning it has it's own sets of functions that can be used with strings.
This allows us coders to just call the function instead of typing multiple lines of codes to do the same thing. This is a feature of python as it's also a functional programming language as I mentioned in the features section of python. (2nd topic in Content).
<br><br>
String datatype consists of all alphabets letters, symbols, signs and alphanumeric values. They are represented inside quotes ("").



<b>----------------------------------------------------------------------------------------------------------------------------------------------</b><br>
<a id="9C i. Declaring string values"></a>
<br><u><b>(i.) Declaring String Values</b></u> :<br>
<code>var = "hello potato"</code> #You can make this sentence as long as you like <br>
<code>print (var)<br><br>
var1 = "hello potato this is a longer sentence which can stretch for many virtual kilometers provided you have the patience to type that much"
<br>
print (var1)</code><br><br>
Eg :


```python
#Declaring strings in python

var = "hello potato"  #Pretty self explanatory and I have explained the same in the beginning of introduction about Datatypes in python
#topic 6 in contents
print (var)
var1 = "hello potato this is a longer sentence which can stretch for many virtual kilometers provided you have the patience to type that much!" 
print (var1)  #No need to do : char var1[100] like in case of c/c++, it's technically unlimited memory allocation by default.
```

    hello potato
    hello potato this is a longer sentence which can stretch for many virtual kilometers provided you have the patience to type that much!
    


<b>----------------------------------------------------------------------------------------------------------------------------------------------</b><br>
<a id="9C ii. String concatenation in python"></a>
<br><b><u>(ii.) String concatenation in Python :</u></b><br>
String concatenation refers to the act of joining two strings together to make a new string consisting both the previous strings. Like this multiple strings can be joined together. String concatenation is very simple in python. You just add text as it is. Following example below will demonstrate everything.


```python
#Example of string concatenation in python

a = "hello"
b = " "  #empty space
c = "potato"
d = a+b+c+b #string concatenation
print (d)
print (d+d+"\n"+d+d+"!!")  #another example of string concatenation

e = "123" #Notice how variable 'e' is holding 123 as a string value, not as an integer. We can clearly notice this using the "" (Double quotes)
#around 123. We cannot do string concatenation for integer and string. String conct. is only possible for strings.
f = "Mic testing"
print ("\n"+f+b+e+b+f+b+e+" !!"+" "+d+",","can you hear me now ?")
```

    hello potato 
    hello potato hello potato 
    hello potato hello potato !!
    
    Mic testing 123 Mic testing 123 !! hello potato , can you hear me now ?
    


<b>----------------------------------------------------------------------------------------------------------------------------------------------</b><br>
<a id="9C iii. Indexing and slicing strings"></a>
<br><b><u>(iii.) Indexing and slicing strings in Python :</u></b><br>
<ul><li> <u>Definition of Index/Indices</u></li><ul> :
<br>It is a common method for keeping track of data so that it can be accessed quickly. Like an index in a book, it is a numeric value in which each entry contains the name of the item or element and its location. However, computer-based indexes may point to a physical location on a disk or to a logical location that points elsewhere to the actual location.<br>
Indices (plural of 'index') start from 0 (zero) and go on to n-1, where 'n' is the number of characters in the string in this case. For eg: the string "hello" has n = 5 value as "hello" has 5 characters, hence the indices will start from 0 and go on till n-1, i.e, 5 - 1 = 4.<br>
In python, indexing is represented as follows, say : a = "hello"; then a[index_number] is the syntax of using indices for string (as well as lists which will be explained later). So in this case, a[0], a[1], a[2], a[3] and a[4] are indices of the variable 'a'. Each of these indices, hold a character of that string assigned to the variable. Therefore, for a = "hello", a[0]=>'h', a[1]=>'e',a[2]=>'l', a[3]=>'l', a[4]=>'o'. We don't have a[5] as the length of "hello" is 5, and indices range from 0 to n-1 as I said before, so here it is 0 to 4 indices. Similar example : b = "Name", here indices of 'b' from 0 to 3 where, b[0]='N', b[1]='a', b[2]='m' and b[3]='e'. <br><br>
Unlike in C/C++, Python also has negative indices as well, meaning if a = "hello", then it will have that many negative indices as well, meaning, indices from -1 to -5 (as "hello" has 5 letters in it), but notice that the positive indices are start from 0 to n-1, or 5-1=4 (0 to 4 in case of "hello"). So negative indices are represented in the following way : a[-5], a[-4], a[-3], a[-2] and a[-1].
<br> So what's the difference between positive indices and negative indices you may think?
<br> Negative indices return characters from the other end or the right-end. This is useful when you got to print values from the other end of the string or don't exactly know what the last character of the string is. Eg : a="hello"; then a[-5]=>"h",a[-4]=>"e",a[-3]=>"l",a[-2]=>"l",a[-1]=>"o".<br>
So from the above you can understand that :<br>
<br> a[0] => a[-5] => "h";
<br> a[1] => a[-4] => "e";
<br> a[2] => a[-3] => "l";
<br> a[3] => a[-2] => "l";
<br> a[4] => a[-1] => "o";
<br><br> So the following indices hold the same value and can be used as per our likings or situation. Sometimes it's easier to use the negative indices while sometimes it's easier to use the positive indices (like in most cases) or in some cases it's easier to use both.
<br> <br>NOTE : I am using "=>" instead of "=" for a[0]=>"h" because "=" (equal to) is an assignment operator and will show error if you use a[0]="h" in our case, I am just trying to make you understand that a[0] holds the value "h" and this can only be presented using : print(a[0]).
<br>
<br> EG:


```python
#Example of indices in strings
a = "apple"
print (" ",a[0])                #Positive indices from 0 to 4 (coz "apple" has 5 characters so, it's from 0 to n-1, or 5-1 = 4)
print (" ",a[1],a[4])
print (" ",a[2],"",a[3])
print (" ",a[3]," ",a[2])
print (" ",a[4],"  ",a[1])
print ("---------",a)
print (" ",a[-1],"  ",a[-4])    #Negative indices from -1 to -5 (coz "apple" has 5 characters)
print (" ",a[-2]," ",a[-3])
print (" ",a[-3],"",a[-2])
print (" ",a[-4],a[-1])
print (" ",a[-5])

```

      a
      p e
      p  l
      l   p
      e    p
    --------- apple
      e    p
      l   p
      p  l
      p e
      a
    

<ul><li><u>Slices in strings </u></li></ul> :
<Br> So uptil now we have learned about indices in strings. Now moving to the next topic, which is slices. It uses the concept of indices to work. If you remember correctly, if a="apple", then a[0]=>"a". Here, we are just using one index, i.e., 0 (zero). But in actual, we can input upto three parameters inside the [ ] (square brackets).
<br>The important thing to remember is this :
 <ul><li> We can input upto three parameters inside the square brackets [ ]</li></ul>.
 <ul><li> Out of the three parameters, having at least one value or parameter when using the square brackets [ ] is compulsory (as in a[0]).</li></ul>
 <ul><li> So we can use either 1, 2 or upto 3 parameters in square brackets, and each of these parameters is seperated using "colons" (:)</li></ul>
 <ul><li> The parameters are denoted as follows -> [<i>start</i>:<i>stop</i>:<i>step</i>] (notice the colons been used to seperate the parameters as mentioned in the above point</li></ul>
 <ul><li> <i>start</i> parameter decides from which index we are supposed to start. </li></ul>
 <ul><li> <i>stop</i> parameter decides at which index we are supposed to stop (it goes upto n-1 index, so if we choose say (a[0:3]), we will get characters in "apple" from 0th index to 3-1=2 (n-1), so a[0:3] will return "app" from 0th, 1st and 2nd index). Here even though we just used [<i>start</i>:<i>stop</i>] in a[0:3], the <i>step</i> parameter was by default set to 1, i.e. in the back-end python was executing a[0:3:1], because by default, the <i>step</i> parameter is set at 1, when we use both <i>start</i> and <i>stop</i> parameters inside the square brackets.</li></ul>
 <ul><li> <i>step</i> parameter is used for skipping the characters or stepping on them as we count from left to right. For eg : a[0:5:2] (here we have purposefully used '2' as the step so python knows not to use "1" as the value for the step parameter by default).<br>So, for a[0:5:2], we will start at a[0]=>"a",jump two indices and go to a[2]=>"p" and go on until 5-1=4 index,so a[4]="e". So a[0:5:2]=>"ape" (Start at 0, stop at 5-1=4, jump two indices every step). Notice how we can use "5" as stop value as well because <i>stop</i> parameter only considers n-1 as a value.</li></ul>
 <ul><li> In case only one parameter is involved (like in a[0]), we get the value at that specific index ("a" in "apple" for a[0]). Because here, we only consider the value at that specific index, here a[0].</li></ul>
 <ul><li>In case two parameters are given then python only considers them as [<i>Start</i>:<i>Stop</i>] with <i>Step</i> set at 1 by default in the back-end by python itself. Eg : a[0:4]=>"appl" (From 0th index to n-1 (4-1=3) index).</li></ul>
 <ul><li> In case all three parameters are given [<i>start</i>:<i>stop</i>:<i>step</i>] it works the same way as explained in case of a[0:5:2] above.</li></ul>
 


```python
s = "hello world"
# Grab everything past the first term all the way to the length of s till the end
print (s[1:])
```

    ello world
    


```python
# Note that there is no change to the original s variable
s = "hello world"
print (s)
```

    hello world
    


```python
s = "hello world"
# Grab everything UP TO the 4th index (n-1 = 4-1 = 3rd index, indices till 3rd will be printed)
print (s[:4])
```

    hell
    


```python
#Everything
s = "hello world"
print (s[:])
```

    hello world
    


```python
# Grab everything but the last letter
s = "hello world"
print (s[:-1])    
#Start here is considered as "Everything", you can notice that only one single colon is used meaning [start:stop] parameters
#are used while step is considered as 1 by default by python. Stop parameter is set to n-1 (-1-1=-2) so return everything till -2 index
#step as 1 (set by python, even though we are only using the parameters [start:stop])
```

    hello worl
    


```python
# Grab everything, but go in steps size of 1
print (s[::1])  
#Here start and stop parameter are considered as "everything is included" and we are considering three parameters as you can notice
#unlike above example, we have two colons in square brackets so the parameters now include [start:stop:step] but since start and stop aren't
#mentioned, it will include everything.
```

    hello world
    


```python
# Grab everything, but go in step sizes of 2
s = "hello world"
print (s[::2])
#Here, yet again [start:stop:step] are used
#start = 0th index 
#stop = last index is included (Basically include everything as start and stop aren't mentioned implicitly)
#step = set as 2 by us.
```

    hlowrd
    


```python
# We can use this to print a string backwards
s = "hello world"
print (s[::-1])
#Grab everything but start from the last index (negative one step) and go on to the start parameter.
```

    dlrow olleh
    

<a id="9C iv. String properties"></a>
<br><br><b><u>(iv.) String Properties</u> :</b><br> 
It's important to note that strings have an important property known as *immutability*. This means that once a string is created, the elements within it can not be changed or replaced. For example:


```python
s = "hello world"
print (s)
```

    hello world
    


```python
# Let's try to change the first letter to 'x'
s = "hello world"
s[0] = 'x'
#This was the reason I was using "=>" To denote a[0]=>"a" in above examples, as saying a[0]="a" means you are trying to
#change the value/character at a[0] which is not allowed in string datatype.
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-99-21fdf30a429e> in <module>
          1 # Let's try to change the first letter to 'x'
          2 s = "hello world"
    ----> 3 s[0] = 'x'
          4 #This was the reason I was using "=>" To denote a[0]=>"a" in above examples, as saying a[0]="a" means you are trying to
          5 #change the value/character at a[0] which is not allowed in string datatype.
    

    TypeError: 'str' object does not support item assignment


---------------------------------------------------------------------------------
Notice how the error tells us directly what we can't do, change the item assignment!

Something we *can* do is concatenate strings!


```python
s = "hello world"
print (s)
```

    hello world
    


```python
# Concatenate strings!
s = "hello world"
print (s + '!! I am batman')
```

    hello world!! I am batman
    


```python
#Notice how the original value of variable s is not changed
#Make sure you have run the above 2 cells to see the output without error here
print (s)
```

    hello world
    


```python
# We can reassign the variable s completely though!
#Make sure you have run the above 3 cells to see the output without error here
s = s + ' I am batman!'

```


```python
#The value of s is now reassigned
#Make sure you have run the above 4 cells to see the output without error here
print (s)
```

    hello world I am batman!
    

<a id="9C v. String methods & functions"></a>
<br><br><b><u>(v.) Basic Built-in String methods and functions</u> : </b>

Objects in Python usually have built-in methods and functions. These methods are functions inside the object that can perform actions or commands on the object itself.

We call functions with a period/dot and then the function name. Functions are in the form:

object.function-name(parameters)

Where parameters are extra arguments we can pass into the method/functions. Don't worry if the details don't make 100% sense right now. Later on we will be creating our own objects and functions!

Here are some examples of built-in methods/functions in strings:


```python
help("str")  
#notice how I am using str with small 's'. Python is case-sensitive, never forget that
#This will return all the functions and methods we can use with strings.
#press 'q' on the keyboard if you are in interactive/terminal mode of python to exit the help menu.
#this is not the terminal/interactive mode of python by the way :P
```

    Help on class str in module builtins:
    
    class str(object)
     |  str(object='') -> str
     |  str(bytes_or_buffer[, encoding[, errors]]) -> str
     |  
     |  Create a new string object from the given object. If encoding or
     |  errors is specified, then the object must expose a data buffer
     |  that will be decoded using the given encoding and error handler.
     |  Otherwise, returns the result of object.__str__() (if defined)
     |  or repr(object).
     |  encoding defaults to sys.getdefaultencoding().
     |  errors defaults to 'strict'.
     |  
     |  Methods defined here:
     |  
     |  __add__(self, value, /)
     |      Return self+value.
     |  
     |  __contains__(self, key, /)
     |      Return key in self.
     |  
     |  __eq__(self, value, /)
     |      Return self==value.
     |  
     |  __format__(self, format_spec, /)
     |      Return a formatted version of the string as described by format_spec.
     |  
     |  __ge__(self, value, /)
     |      Return self>=value.
     |  
     |  __getattribute__(self, name, /)
     |      Return getattr(self, name).
     |  
     |  __getitem__(self, key, /)
     |      Return self[key].
     |  
     |  __getnewargs__(...)
     |  
     |  __gt__(self, value, /)
     |      Return self>value.
     |  
     |  __hash__(self, /)
     |      Return hash(self).
     |  
     |  __iter__(self, /)
     |      Implement iter(self).
     |  
     |  __le__(self, value, /)
     |      Return self<=value.
     |  
     |  __len__(self, /)
     |      Return len(self).
     |  
     |  __lt__(self, value, /)
     |      Return self<value.
     |  
     |  __mod__(self, value, /)
     |      Return self%value.
     |  
     |  __mul__(self, value, /)
     |      Return self*value.
     |  
     |  __ne__(self, value, /)
     |      Return self!=value.
     |  
     |  __repr__(self, /)
     |      Return repr(self).
     |  
     |  __rmod__(self, value, /)
     |      Return value%self.
     |  
     |  __rmul__(self, value, /)
     |      Return value*self.
     |  
     |  __sizeof__(self, /)
     |      Return the size of the string in memory, in bytes.
     |  
     |  __str__(self, /)
     |      Return str(self).
     |  
     |  capitalize(self, /)
     |      Return a capitalized version of the string.
     |      
     |      More specifically, make the first character have upper case and the rest lower
     |      case.
     |  
     |  casefold(self, /)
     |      Return a version of the string suitable for caseless comparisons.
     |  
     |  center(self, width, fillchar=' ', /)
     |      Return a centered string of length width.
     |      
     |      Padding is done using the specified fill character (default is a space).
     |  
     |  count(...)
     |      S.count(sub[, start[, end]]) -> int
     |      
     |      Return the number of non-overlapping occurrences of substring sub in
     |      string S[start:end].  Optional arguments start and end are
     |      interpreted as in slice notation.
     |  
     |  encode(self, /, encoding='utf-8', errors='strict')
     |      Encode the string using the codec registered for encoding.
     |      
     |      encoding
     |        The encoding in which to encode the string.
     |      errors
     |        The error handling scheme to use for encoding errors.
     |        The default is 'strict' meaning that encoding errors raise a
     |        UnicodeEncodeError.  Other possible values are 'ignore', 'replace' and
     |        'xmlcharrefreplace' as well as any other name registered with
     |        codecs.register_error that can handle UnicodeEncodeErrors.
     |  
     |  endswith(...)
     |      S.endswith(suffix[, start[, end]]) -> bool
     |      
     |      Return True if S ends with the specified suffix, False otherwise.
     |      With optional start, test S beginning at that position.
     |      With optional end, stop comparing S at that position.
     |      suffix can also be a tuple of strings to try.
     |  
     |  expandtabs(self, /, tabsize=8)
     |      Return a copy where all tab characters are expanded using spaces.
     |      
     |      If tabsize is not given, a tab size of 8 characters is assumed.
     |  
     |  find(...)
     |      S.find(sub[, start[, end]]) -> int
     |      
     |      Return the lowest index in S where substring sub is found,
     |      such that sub is contained within S[start:end].  Optional
     |      arguments start and end are interpreted as in slice notation.
     |      
     |      Return -1 on failure.
     |  
     |  format(...)
     |      S.format(*args, **kwargs) -> str
     |      
     |      Return a formatted version of S, using substitutions from args and kwargs.
     |      The substitutions are identified by braces ('{' and '}').
     |  
     |  format_map(...)
     |      S.format_map(mapping) -> str
     |      
     |      Return a formatted version of S, using substitutions from mapping.
     |      The substitutions are identified by braces ('{' and '}').
     |  
     |  index(...)
     |      S.index(sub[, start[, end]]) -> int
     |      
     |      Return the lowest index in S where substring sub is found, 
     |      such that sub is contained within S[start:end].  Optional
     |      arguments start and end are interpreted as in slice notation.
     |      
     |      Raises ValueError when the substring is not found.
     |  
     |  isalnum(self, /)
     |      Return True if the string is an alpha-numeric string, False otherwise.
     |      
     |      A string is alpha-numeric if all characters in the string are alpha-numeric and
     |      there is at least one character in the string.
     |  
     |  isalpha(self, /)
     |      Return True if the string is an alphabetic string, False otherwise.
     |      
     |      A string is alphabetic if all characters in the string are alphabetic and there
     |      is at least one character in the string.
     |  
     |  isascii(self, /)
     |      Return True if all characters in the string are ASCII, False otherwise.
     |      
     |      ASCII characters have code points in the range U+0000-U+007F.
     |      Empty string is ASCII too.
     |  
     |  isdecimal(self, /)
     |      Return True if the string is a decimal string, False otherwise.
     |      
     |      A string is a decimal string if all characters in the string are decimal and
     |      there is at least one character in the string.
     |  
     |  isdigit(self, /)
     |      Return True if the string is a digit string, False otherwise.
     |      
     |      A string is a digit string if all characters in the string are digits and there
     |      is at least one character in the string.
     |  
     |  isidentifier(self, /)
     |      Return True if the string is a valid Python identifier, False otherwise.
     |      
     |      Use keyword.iskeyword() to test for reserved identifiers such as "def" and
     |      "class".
     |  
     |  islower(self, /)
     |      Return True if the string is a lowercase string, False otherwise.
     |      
     |      A string is lowercase if all cased characters in the string are lowercase and
     |      there is at least one cased character in the string.
     |  
     |  isnumeric(self, /)
     |      Return True if the string is a numeric string, False otherwise.
     |      
     |      A string is numeric if all characters in the string are numeric and there is at
     |      least one character in the string.
     |  
     |  isprintable(self, /)
     |      Return True if the string is printable, False otherwise.
     |      
     |      A string is printable if all of its characters are considered printable in
     |      repr() or if it is empty.
     |  
     |  isspace(self, /)
     |      Return True if the string is a whitespace string, False otherwise.
     |      
     |      A string is whitespace if all characters in the string are whitespace and there
     |      is at least one character in the string.
     |  
     |  istitle(self, /)
     |      Return True if the string is a title-cased string, False otherwise.
     |      
     |      In a title-cased string, upper- and title-case characters may only
     |      follow uncased characters and lowercase characters only cased ones.
     |  
     |  isupper(self, /)
     |      Return True if the string is an uppercase string, False otherwise.
     |      
     |      A string is uppercase if all cased characters in the string are uppercase and
     |      there is at least one cased character in the string.
     |  
     |  join(self, iterable, /)
     |      Concatenate any number of strings.
     |      
     |      The string whose method is called is inserted in between each given string.
     |      The result is returned as a new string.
     |      
     |      Example: '.'.join(['ab', 'pq', 'rs']) -> 'ab.pq.rs'
     |  
     |  ljust(self, width, fillchar=' ', /)
     |      Return a left-justified string of length width.
     |      
     |      Padding is done using the specified fill character (default is a space).
     |  
     |  lower(self, /)
     |      Return a copy of the string converted to lowercase.
     |  
     |  lstrip(self, chars=None, /)
     |      Return a copy of the string with leading whitespace removed.
     |      
     |      If chars is given and not None, remove characters in chars instead.
     |  
     |  partition(self, sep, /)
     |      Partition the string into three parts using the given separator.
     |      
     |      This will search for the separator in the string.  If the separator is found,
     |      returns a 3-tuple containing the part before the separator, the separator
     |      itself, and the part after it.
     |      
     |      If the separator is not found, returns a 3-tuple containing the original string
     |      and two empty strings.
     |  
     |  replace(self, old, new, count=-1, /)
     |      Return a copy with all occurrences of substring old replaced by new.
     |      
     |        count
     |          Maximum number of occurrences to replace.
     |          -1 (the default value) means replace all occurrences.
     |      
     |      If the optional argument count is given, only the first count occurrences are
     |      replaced.
     |  
     |  rfind(...)
     |      S.rfind(sub[, start[, end]]) -> int
     |      
     |      Return the highest index in S where substring sub is found,
     |      such that sub is contained within S[start:end].  Optional
     |      arguments start and end are interpreted as in slice notation.
     |      
     |      Return -1 on failure.
     |  
     |  rindex(...)
     |      S.rindex(sub[, start[, end]]) -> int
     |      
     |      Return the highest index in S where substring sub is found,
     |      such that sub is contained within S[start:end].  Optional
     |      arguments start and end are interpreted as in slice notation.
     |      
     |      Raises ValueError when the substring is not found.
     |  
     |  rjust(self, width, fillchar=' ', /)
     |      Return a right-justified string of length width.
     |      
     |      Padding is done using the specified fill character (default is a space).
     |  
     |  rpartition(self, sep, /)
     |      Partition the string into three parts using the given separator.
     |      
     |      This will search for the separator in the string, starting at the end. If
     |      the separator is found, returns a 3-tuple containing the part before the
     |      separator, the separator itself, and the part after it.
     |      
     |      If the separator is not found, returns a 3-tuple containing two empty strings
     |      and the original string.
     |  
     |  rsplit(self, /, sep=None, maxsplit=-1)
     |      Return a list of the words in the string, using sep as the delimiter string.
     |      
     |        sep
     |          The delimiter according which to split the string.
     |          None (the default value) means split according to any whitespace,
     |          and discard empty strings from the result.
     |        maxsplit
     |          Maximum number of splits to do.
     |          -1 (the default value) means no limit.
     |      
     |      Splits are done starting at the end of the string and working to the front.
     |  
     |  rstrip(self, chars=None, /)
     |      Return a copy of the string with trailing whitespace removed.
     |      
     |      If chars is given and not None, remove characters in chars instead.
     |  
     |  split(self, /, sep=None, maxsplit=-1)
     |      Return a list of the words in the string, using sep as the delimiter string.
     |      
     |      sep
     |        The delimiter according which to split the string.
     |        None (the default value) means split according to any whitespace,
     |        and discard empty strings from the result.
     |      maxsplit
     |        Maximum number of splits to do.
     |        -1 (the default value) means no limit.
     |  
     |  splitlines(self, /, keepends=False)
     |      Return a list of the lines in the string, breaking at line boundaries.
     |      
     |      Line breaks are not included in the resulting list unless keepends is given and
     |      true.
     |  
     |  startswith(...)
     |      S.startswith(prefix[, start[, end]]) -> bool
     |      
     |      Return True if S starts with the specified prefix, False otherwise.
     |      With optional start, test S beginning at that position.
     |      With optional end, stop comparing S at that position.
     |      prefix can also be a tuple of strings to try.
     |  
     |  strip(self, chars=None, /)
     |      Return a copy of the string with leading and trailing whitespace removed.
     |      
     |      If chars is given and not None, remove characters in chars instead.
     |  
     |  swapcase(self, /)
     |      Convert uppercase characters to lowercase and lowercase characters to uppercase.
     |  
     |  title(self, /)
     |      Return a version of the string where each word is titlecased.
     |      
     |      More specifically, words start with uppercased characters and all remaining
     |      cased characters have lower case.
     |  
     |  translate(self, table, /)
     |      Replace each character in the string using the given translation table.
     |      
     |        table
     |          Translation table, which must be a mapping of Unicode ordinals to
     |          Unicode ordinals, strings, or None.
     |      
     |      The table must implement lookup/indexing via __getitem__, for instance a
     |      dictionary or list.  If this operation raises LookupError, the character is
     |      left untouched.  Characters mapped to None are deleted.
     |  
     |  upper(self, /)
     |      Return a copy of the string converted to uppercase.
     |  
     |  zfill(self, width, /)
     |      Pad a numeric string with zeros on the left, to fill a field of the given width.
     |      
     |      The string is never truncated.
     |  
     |  ----------------------------------------------------------------------
     |  Static methods defined here:
     |  
     |  __new__(*args, **kwargs) from builtins.type
     |      Create and return a new object.  See help(type) for accurate signature.
     |  
     |  maketrans(x, y=None, z=None, /)
     |      Return a translation table usable for str.translate().
     |      
     |      If there is only one argument, it must be a dictionary mapping Unicode
     |      ordinals (integers) or characters to Unicode ordinals, strings or None.
     |      Character keys will be then converted to ordinals.
     |      If there are two arguments, they must be strings of equal length, and
     |      in the resulting dictionary, each character in x will be mapped to the
     |      character at the same position in y. If there is a third argument, it
     |      must be a string, whose characters will be mapped to None in the result.
    
    

<b><u> Note : </b></u>  There's a difference between **str** and **string** in python. Especially if you consider <b>help("str")</b> and <b>help("string")</b>. <br><br>
**str** is a datatype (It is also a **class** but more on "class" later) it is used to work with letters and symbols while <b>string</b> is a module/library which consists of added functions to work with strings {such as <b>string.lower</b> gives as a string from a to z "abcde....xyz"}. More info on this can be found [here](https://stackoverflow.com/questions/2026038/relationship-between-string-module-and-str). )


We will try to cover as many of these built-in methods and functions which are popular and generally used. You can always check the internet for the function or method that you don't understand or which is not covered here.<Br>
Few points before we begin with string functions and methods :
* If you look at the methods and functions mentioned in help(str) you can see that in the begining some are followed by <code><pre> __ add__ </code></pre>This means that this is a method and can be applicable on other data types like list, dictionaries, etc as well. Methods can be universal but a function most probably would not.
* If you scroll down further in the help menu, you will notice now functions names like : Capitalize, center, count shown as follows :
<code><pre>capitalize(...)
 |      S.capitalize() -> str
 |      
 |      Return a capitalized version of S, i.e. make the first character
 |      have upper case and the rest lower case.</pre></code>
 These are functions and follow the syntax as :
 <code>object.function-name(parameters_if_any)</code><Br> or
 <br><code>variablename.function-name(parameters_if_any).</code>
 <Br> Since we are talking about string functions here, the variable (which infact is the object of string class as well), should be holding a string value (like in case of s="hello world") to be able to use string functions.<Br>



<a id="9C vi. String methods"></a>
<br><br><b><u>(vi.) Methods used with str</u> :</b><br>
 Now, let's get started with the methods of <code>str</code> and see how to use them.<br> 
 <br><b>NOTE : </b>Make sure the first cell below is run for all the other cells to work as they use the common variable 'z' to run, if the first cell below isn't run all will give errors.<br><br>


```python
z = "power rangers"   
print (z.__add__(" were so boring at times.")) #The __add__ method works the same way as concatenation works
```

    power rangers were so boring at times.
    


```python
#Make sure you have run the above cell to see the output without error here
print (z)   #but it isn't permanent like concatenation either
```

    power rangers
    


```python
#Make sure you have run the above 2 cells to see the output without error here
print (z + " have lost the match") 
#As you can see using + operator for concatenation method or __add__ is the same thing
```

    power rangers have lost the match
    


```python
#By now you must have realized that the basic syntax for methods is as follows :

#variable-name.__methodname__(parameters-if-any)
 
#or

#object-name.__methodname__(parameters-if-any)
#lets use contains method
print (z.__contains__("p"))
```

    True
    


```python
print (z.__contains__("i"))  #as you can see, it checks if a specific character exists in the string or not.
#Here we tried to find "p" and "i" in "power rangers" and we got True and False respectively as "p" is present while "i" isn't.
```

    False
    


```python
#__eq__ method stands for "Equal to" and it checks if the string is exactly equivalent to the string assigned to the variable.
print (z.__eq__("rangers power"))
```

    False
    


```python
print(z.__eq__("power rangers"))
```

    True
    


```python
#__ge__stands for 'greater than equal to'
print("hello".__ge__("hello"))  
#We can directly use "strings" in double-quotes as well, because in the end variables point to 
#"string_values" itself.
```

    True
    


```python
print("hello".__ge__("hell"))  #hello>=hell (True)
```

    True
    


```python
print("hello".__ge__("hello world"))  
#Don't forget the dot/period operator between the methods and the string/variables/object
#here, "hello">="hello world" (False)
```

    False
    


```python
#__gt__ stands for 'greater than'
print ("hello".__gt__("hello"))  #hello>hello (False) __gt__method
print ("hello".__ge__("hello"))  #hello>=hello (True) __ge__method
```

    False
    True
    


```python
print("hi".__gt__("h"))
```

    True
    


```python
#The hash() method or .__hash__()
print(z.__hash__())
    #or
print (hash(z))  #both will give the same output

#The hash() method returns the hash value of an object if it has one.
#Hash values are just integers which are used to compare dictionary keys during a dictionary lookup quickly.
#Internally, hash() method calls __hash__() method of an object which are set by default for any object.
```

    -1631650316125606053
    -1631650316125606053
    


```python
#The iter() method or .__iter__()
#Just like hash() some methods can also be called as special functions like iter(),hash() and len(), and str()
#you don't need to use __iter__(), you can just use iter() as well.
#Definition of iter():
        #The iter() method creates an object which can be iterated one element at a time.
        #These objects are useful when coupled with loops like for loop, while loop.
j = "hey"
v = iter(j)
n = j.__iter__()  #traditional way but both give the same output

print ("\tv variable - \n")        #\n prints to next line
print (next(v))  
print (next(v))            #next() is used to print the next iteration
print (next(v))

print ("\n\tn variable - \n")
print (next(n))   #1st iteration
print (next(n))   #2nd iteration
print (next(n))   #3rd iteration
print (next(n))   #j = "hey" has only 3 characters, so it can be iterated only 3 times, this 4th iteration will cause an error




```

    	v variable - 
    
    h
    e
    y
    
    	n variable - 
    
    h
    e
    y
    


    ---------------------------------------------------------------------------

    StopIteration                             Traceback (most recent call last)

    <ipython-input-119-e4aeb426dba6> in <module>
         18 print (next(n))   #2nd iteration
         19 print (next(n))   #3rd iteration
    ---> 20 print (next(n))   #j = "hey" has only 3 characters, so it can be iterated only 3 times, this 4th iteration will cause an error
         21 
         22 
    

    StopIteration: 


<a id="9C vi.> Len and type"></a>
<br><b>Some important functions in Python : (len & type)</b><br><br>
<li> <u> len() </u> : It tells the length of a string or container data-types like list, tuples, sets, etc.
<li> <u> type() </u> : It tells us the data-type of the value passed inside the type() function.
<br><br>    
    <b>Eg : </b>


```python
#len() or .__len__()
#len() is used to get the lenght of the string, lists, tuples, etc. It doesn't work for datatypes that aren't container datatypes
#dictionaries, etc or don't have indices like strings,lists,etc. Meaning it won't work for integers & floats as you can't
#find length of a number but you can find how many characters does a string have

print(len("This is a long sentence"))
p = "This is a longer sentence"
print (len(p))
print ( "This is a longest setence I guess".__len__() )
print (len("hello"))  #5 characters in "hello", hence the length will be 5 but indices are from 0 to 5-1=4.
#don't get confused between length and indices.
h = "meh"
print (h.__len__())

```

    23
    25
    33
    5
    3
    


```python
#Some more important methods
#type() method lets you check the dataype of any value or any variable that is holding any datatype

a = "apple"
print (type(a))
print (type(1))
b = 1.2
print (type(b))
print (type("Funny"))
```

    <class 'str'>
    <class 'int'>
    <class 'float'>
    <class 'str'>
    

---
Let's continue with <b>str</b> functions once again now that we have discussed <b>len()</b> and <b>type()</b> functions.

---
<br>


```python
#__le__ method stands for "less than equal to" and is similar to __eq__,__gt__ and __ge__ methods
print ("h".__le__("hey"))
h = "meh"
print (h.__le__("m"))   
print (h.__le__("meh"))  #meh>=meh
```

    True
    False
    True
    


```python
#__lt__ method stands for "less than" and is similar to __eq__,__ge__,__gt__ and __le__ methods
h = "meh"
print(h.__lt__(h)) #meh<meh (False)
print (h.__lt__(h[0]*5)) #meh<mmmmm (True)
```

    False
    True
    


```python
#__mul__ stands for Multiply and is used to multiply a string multiple times.
print ("hey! ".__mul__(5)) #Multiply 'hey' 5 times
#It is the same as :       #Multiply 'hey' 7 times
print ("hey! "*7)

print (len("hey"*10))  #Some improvisation examples with len() and .__len__
print (len("hey".__mul__(19)))
print ("hey".__mul__(7).__len__())  
```

    hey! hey! hey! hey! hey! 
    hey! hey! hey! hey! hey! hey! hey! 
    30
    57
    21
    


```python
#__ne__ stands for 'Not equal to' and is opposite of  __eq__ method (equal to method)
a = "apple"
print (a.__ne__(a[0]))
print (a.__ne__(a[:]))  
#here a[:],a and "apple" are the same thing which is "apple" and hence, we get false as "apple" is equal to apple
print (a.__ne__(a))
print (a.__ne__("apple"))

#but
print (a.__eq__(a[:]))  #as "apple" is equal to "apple"

#IMPORTANT :
#Kindly try not to 

```

    True
    False
    False
    False
    True
    


```python
#__repr__ method, 
#It is used to put a string in single quotes and is useful while maintaining those single quotes during print statement
print ("And he quoted:","The world is burning slowly~".__repr__(),"and left with a sad expression.")
print ("Hey".__repr__()) #with __repr__
print ("Hey")            #without __repr__
```

    And he quoted: 'The world is burning slowly~' and left with a sad expression.
    'Hey'
    Hey
    


```python
#__sizeof__ method returns the size of the string in memory, in bytes.

a = "apple"
print (a.__sizeof__())
print ("not apple".__sizeof__())

```

    54
    58
    


```python
#__str__ or str() method : Converts any datatype to a string value
a = 9
b = a.__str__()  #Converting int to str datatype
print (b)
c = str(a)       #Same thing but using str() instead
print (c)
print (b+c+" pizzas didn't fill his stomach")  #string concatenation
print (a+b)      #This will cause error as variable 'a' is still holding on to integer value of 9
                 #and concatenation of string and integers is not possible.
```

    9
    9
    99 pizzas didn't fill his stomach
    


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-128-8355d8a89d14> in <module>
          6 print (c)
          7 print (b+c+" pizzas didn't fill his stomach")  #string concatenation
    ----> 8 print (a+b)      #This will cause error as variable 'a' is still holding on to integer value of 9
          9                  #and concatenation of string and integers is not possible.
    

    TypeError: unsupported operand type(s) for +: 'int' and 'str'


<a id="9C vii.String functions"></a>
<br><br><b><u>vii.) Functions used with str</u> :</b><br>
When we run <code>help(str)</code>, after scrolling down a bit you will see methods with the double underscores on both sides, and after that comes functions which use the (.) dot operator.<br>
Something like this :<br>
<code><pre>capitalize(...)
 |      S.capitalize() -> str
 |      
 |      Return a capitalized version of S, i.e. make the first character
 |      have upper case and the rest lower case.</pre></code>
 <br>
 The basic syntax of functions is :<br>
 <pre><code>
 s = "Text"
 s.function-name(parameters-if-any) #Notice the usage of dot operator after the variable. Eg:
 s.capitalize()  #capitalize function doesn't have any parameters
 </code></pre>
 One thing that is worth noting here is that we can use functions of strings with any string value or variable that is assigned a string value (just like in case of methods. This will be clear in further examples below.
 Let's explore the most conmmonly used functions of string module/data type :


```python
#capitalize() function : Takes no parameters or arguments inside the paranthesis

a = "this is a text"
print (a.capitalize())  #Notice the "T" in "this" in "this is a text" in the output. It gets capitalized.
print (a)               #Also notice how the original string value has not changed, to change the original string we need to reassign it
a = a.capitalize()     #reassigning the value of variable a with a.capitalize() value
print (a)               #The value will be capitalized now
print ("this is a text. this is an another text".capitalize())
#Capitalize only makes the first letter capital, it doesn't care about full stops as
#in this example. Notice how I didn't use an variable to call the function just the string. This is what happens also when we use an variable.
#Python subsitutes the string value of the variable in the back-end for us.
```

    This is a text
    this is a text
    This is a text
    This is a text. this is an another text
    


```python
#center() function : Takes two parameters and one arguement (Meaning only one parameter is compulsory to be filled inside the paranthesis)
#center() has two parameters which are (width,fill). Width expects integer value and is compulsory to fill, fill is a string data type and
#isnt' compulsory to fill.

s = "hello"
#print (s.center())         This won't work as center() function atleast expects you enter one parameter. Hence I commented this statement.
print (s.center(15))        #By default, width here is set to 15, while fill is set to " "  (empty space)
print (s.center(15," "))    #This will give the same output as above statement
print (s.center(15,"$"))    #here the spaces will be set to $ (dollar) symmbol
print (len(s.center(15,"$"))) #Notice how the final lenght isn't 15+5=20 where 15 is width and 5 is lenght of "hello"
#center function just adds the character "$" on both the sides of the string "hello" until "hello" is in center

print ("Width is 4 : ",s.center(4,"$"))     #This won't work as we want to add width of 4 overall but the string "hello" itself is of length 5
print ("Width is 5 : ",s.center(5,"$"))     #won't have any change
print ("Width is 6 : ",s.center(6,"$"))     #will add a "$" at the end to make the final width as 5+1=6 (here, 5 is length of "hello")
print ("Width is 7 : ",s.center(7,"$"))     #adds dollar symbols on both sides to make overall length as 7.
print ("Width is 14 : ",s.center(14,"$"))   #adds 4 $ symbols on left and 5 $ symbols on right
```

         hello     
         hello     
    $$$$$hello$$$$$
    15
    Width is 4 :  hello
    Width is 5 :  hello
    Width is 6 :  hello$
    Width is 7 :  $hello$
    Width is 14 :  $$$$hello$$$$$
    


```python
#count() function : Takes one parameter which is a string value in the paranthesis
s = "hello"
print (s.count("l"))  #Returns the count of how many times the letter "l" appears in "hello"
print (s.count("z"))  #Returns how many times "z" appears in "hello"
print (s.count("h"))  #Returns how many times "h" appears in "hello"
print (s.count("he")) #Returns the count of how many times "he" appears in "hello"


#this is an important function for questions like : How many times is "s" repeating in "mississippi"
print ("mississippi".count("s"))  #Returns 4 as "s" appears 4 times in "mississippi"
```

    2
    0
    1
    1
    4
    


```python
#endswith() function : Accepts one string value as a parameter in the paranthesis
s = "hello"
print (s.endswith("o"))   #Accepts one string value in the paranthesis as the parameter
#Returns boolean value (True or False) whether a string ends with a specific letter or character or not.

print (s.endswith("s"))
```

    True
    False
    


```python
#find() function : Accepts one string value as a parameter in paranthesis

a = "hello"
print (s.find("l"))    #returns the index of the first instance of the string passed inside the paranthesis (here it is letter "l")
#for the given string, here "l" is first spotted at index 2, hence it will return 2 ignoring another "l" at index 3 

print (s.find("h"))    #returns 0 for index 0 as "h" is at index 0 in "hello"

print (s.find("z"))    #returns -1 as the character "z" does not exist in "hello" Not to be confused with negative indices as explained before.
print (s.find("H"))    #returns -1 as character "H" is not present in "hello" (python is case-sensitive, it treats "H" and "h" differently)
print ("abcabcabc".find("b"))  #returns 1 as letter "b" is spotted at index 1 first. It will always return the lowest index value where it finds
#the letter "b" first, that is the first instance of letter "b" in "abcabcabc"
```

    2
    0
    -1
    -1
    1
    


```python
#index() function : Accepts one string value as the parameter inside the paranthesis
#Index works the same way as find() function, that is, it returns the lowest index where it first spotted the letter which was 
#passed inside the paranthesis but the only difference is, if a letter is not found in the actual string
#it will raise "ValueError" instead of returning -1 in case of find() function
#This is useful in case of exception handling where we can ignore the error and still make the code work.
a = "hello"
print (a.index("h"))  #returns 0 as "h" is located at index 0 in "hello"
print (a.index("o"))  #returns 4 as "o" is located at index 4 in "hello"
print (a.index("l"))  #returns 2 as the first instance of "l" or the lowest index of "l" is at index 2 in "hello"
print (a.index("z"))  #returns "ValueError" as "z" is not present in "hello". Here, find() function would have returned -1 instead of an error
                      #as we can see from the example above.
```

    0
    4
    2
    


    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    <ipython-input-134-4963a527ebcf> in <module>
          8 print (a.index("o"))  #returns 4 as "o" is located at index 4 in "hello"
          9 print (a.index("l"))  #returns 2 as the first instance of "l" or the lowest index of "l" is at index 2 in "hello"
    ---> 10 print (a.index("z"))  #returns "ValueError" as "z" is not present in "hello". Here, find() function would have returned -1 instead of an error
         11                       #as we can see from the example above.
    

    ValueError: substring not found



```python
#isalnum() function : Accepts no values as parameters in the paranthesis
#alnum stands for "is alphanumeric" or "is aplphabet or numeric" 
#It checks whether each character in a given string is either an alphabet or number
#if not, then it returns False else it returns True
a = "hello"
b = "hello123"
c = "123"
d = "hello 123"  #notice the whitespace in between of "hello" and "123"

print (a.isalnum())   #Returns True as all the letters in variable a are alphabets
print (b.isalnum())   #Returns True as all the letters in variable b are alphabet or numbers
print (c.isalnum())   #Returns True as all the letters in variable c are numbers
print (d.isalnum())   #Returns False as whitspace between "hello" and "123" is neither a number nor an alphabet
```

    True
    True
    True
    False
    


```python
#isalpha() function : Accepts no values as parameters in the paranthesis
#isalpha() stands for "is alphabet" checks if each character in a given string is an alphabet or not
#if it is an alphabet it returns True or else it returns false

a = "hello"
b = "hello123"
c = "123"
d = "hello world"  #notice the whitespace in between of "hello" and "world"
e = "hello-world"

print (a.isalpha())   #Returns True as all the letters in variable a are alphabets
print (b.isalpha())   #Returns False as all the letters in variable b are alphabet or numbers. Every character isn't an alphabet.
print (c.isalpha())   #Returns False as all the letters in variable c are numbers and not alphabets. 
print (d.isalpha())   #Returns False as whitspace between "hello" and "hello" is not an alphabet.
print (e.isalpha())   #Returns False as "-" in "hello-world" is not an alphabet.
```

    True
    False
    False
    False
    False
    


```python
#isdecimal() function : Accepts no values as parameters in the paranthesis
#isdecimal() does exactly what it sounds like. It checks if a given string is a decimal or not.
#Please do not confuse decimal for float values like (1.2, 2.434, 3.14 etc). Decimal here refers to decimal in case of
#binary, oct, decimal, hexa-decimal

a = "1.5"
b = "hello-to-only-1.5-of-you-humans"
c = "hello to only 1.5 of you humans"
d = "0123"

print (a.isdecimal())   #1.5 is not a decimal no. (It's a float)
print (b.isdecimal())   #Not decimal
print (c.isdecimal())   #Not decimal
print (d.isdecimal())   #This is decimal as decimal system has numbers from 0 to 9 only.
```

    False
    False
    False
    True
    


```python
#isdigit() function : Takes no parameter in paranthesis
#Works the same way as isdecimal() function the 
a = "1.5"
b = "hello-to-only-1.5-of-you-humans"
c = "hello to only 2 of you humans"
d = "0123"

print (a.isdigit())   #1.5 is not a digit (decimal no.)
print (b.isdigit())   #Not digit
print (c.isdigit())   #Not digit
print (d.isdigit())   #This is a digit.
```

    False
    False
    False
    True
    


```python
#isnumeric() function : 
#Works in the same way as isdigit() and isdecimal() but also recognizes no.s in other languages such as chinese no.s 1,2,3
#etc in this case.
print ('一二三四五'.isnumeric())
print ("1234".isnumeric())
print ("abc21".isnumeric())
print ('一二三四五'.isdigit())
```

    True
    True
    False
    False
    


```python
#islower() function:
#Checks if every letter in a string is lowercase or not. 

a = "hello234"
b = "Hello"   #H is capital
c = "223"
d = "hiii"

print (a.islower())
print (b.islower())
print (c.islower())
print (d.islower())
```

    True
    False
    False
    True
    


```python
#isspace() function :
#Checks if the given string value is only spaces or not

a = "hello world"   #has letters too beside the space in between "hello" and "world"
b = "     "  #Only spaces
c = "\t\t"   #\t is an escape sequence which is used to give tab-space. One \t => 8 spaces hence this is also true

print (a.isspace())
print (b.isspace())
print (c.isspace())
```

    False
    True
    True
    


```python
#isupper() function :
#Just like islower() function it checks that if every character in a string is uppercase or not

a = "HENLO"
b = "Henlo"
c = "HENLO123"
d = "henlo123"
e = "1234"

print (a.isupper())
print (b.isupper())
print (c.isupper())
print (d.isupper())
print (e.isupper())
```

    True
    False
    True
    False
    False
    


```python
#join() function
#It takes a list consisting of elements as string values as the parameter or arguement and joins them together with the initial
#variable value
#Eg:

a = "hello"
b = ["a"]     #Here, b is a variable which is assigned a list having the string element "a" as it's first element
c = ["a", "b"]#Here, c is a list which is having "a" as first index and "b" as second element
d = ["a","b ","c","d"," e"]
e = [" a ", " b ", " c ", " d "] #Notice how variable b,c and d are all holding string values only (not integer, float, etc)
# I will be talking about lists in detail later 

print (a.join(b))
print (a.join(c))
print (a.join(d))   #Notice 
print (a.join(e))   #Notice the spaces and how hello is 
print (a.join(["$$ "," $$"]))  #Directly using the list as the parameter inside the paranthesis of join() function

```

    a
    ahellob
    ahellob hellochellodhello e
     a hello b hello c hello d 
    $$ hello $$
    


```python
#lower() function
#It converts uppercase strings to lowercase and if it is already lowercase it doesn't do anything. Eg :
a = "hello"
b = "HELLO"
c = "hElLO"
print (a.lower())      #all letters are already lowercase
print (b.lower())      #all letters will be made lowercase
print (c.lower())      #only letters that are uppercase will be made lowercase rest all if they are lowercase will remain the same.
```

    hello
    hello
    hello
    


```python
#partition() function
"""partition(self, sep, /)
 |      Partition the string into three parts using the given separator.
 |
 |      This will search for the separator in the string.  If the separator is found,
 |      returns a 3-tuple containing the part before the separator, the separator
 |      itself, and the part after it.
 |
 |      If the separator is not found, returns a 3-tuple containing the original string
 |      and two empty strings.
 """
 #As per the documentation definition of partition, it partitions a string in three parts always, based on the character
 #or string passed inside it. It always returns a tupple and considers the first occurance of the string value passed
 #inside the paranthesis. Eg:

a = "This is a random text"
print (a.partition("i"))  #first occurance of "i" will be seperated by 3 parts : ('Th', 'i', 's is a random text')
print (a.partition("ra"))
print (a.partition("T"))  #obviously, be careful of case-sensitivity, here the first split will be empty '', 
                          #because the occurance of "T" is in first index and there is nothing before it.
```

    ('Th', 'i', 's is a random text')
    ('This is a ', 'ra', 'ndom text')
    ('', 'T', 'his is a random text')
    


```python
#replace() function
#It replaces all the substrings inside a string with the value passed inside the replace function.
#EG:

a = "This is a random text or is it?"
print (a.replace("i","@")) #output is : Th@s @s a random text or @s @t?
                           #all the "i" has been replace with "@"
print (a.replace("i","@",2)) #Here, 2 is a parameter (more on parameters later) which is optional and let's us
                             #tell how many first occurances of "i" we want to replace. So here,
                             #out of 4 "i", we only want to replace the first two "i", that's why the output is:
                             #Th@s @s a random text or is it?  (last two i's remain the same)
            
print (a.replace("y","a"))   #Nothing is replaced as "y" isn't present in the string
```

    Th@s @s a random text or @s @t?
    Th@s @s a random text or is it?
    This is a random text or is it?
    


```python
#split() function  [IMPORTANT FUNCTION - commonly used in string and list handling problems]
#This is used to split a string just like partition function but instead it splits at every occurance the value passed
#inside it is found at. This is usually used to remove spaces between words in string handling cases. 
#It returns list instead of tuple unlike in partition function. Eg:

a = "This is a random text"
print (a.split(" "))  #passing space (not empty)
print (a.split("i"))
print (a.split("t"))

#This is usually used hand in hand with join function (mentioned above) :
b = "+91 123456789"   #consider a random phone no. string
print ("\nThis is the value of b : ",b)  #More about significance of \n later (it basically prints an empty new line)
c = b.split(" ")
print ("\nThis is the value of c : ",c)
d = "".join(c)  #"" denotes an empty string (different from " ", this is a space, notice how their is a gap in space)
                #so basically we join an empty string with the elements inside the list, c.
          
print ("\nThis is the value of d : ",d) #The output is value of b but without spaces

#You can also use split to convert string to list and then use list functions like sort, reverse, etc to arrange
#letters in ascending or reversed order and then use join function to make it a string again. Though you can
#also use string[::-1] as mentioned above for string reversal.


```

    ['This', 'is', 'a', 'random', 'text']
    ['Th', 's ', 's a random text']
    ['This is a random ', 'ex', '']
    
    This is the value of b :  +91 123456789
    
    This is the value of c :  ['+91', '123456789']
    
    This is the value of d :  +91123456789
    


```python
#startswith() function
#It is used to determine if a string starts with a particular letter or string or not.
#It returns true if the value passed in startwith() function is the starting value for the given string, or else false.
#It's opposite of endswith() function. EG:

z = "A for Apple, B for ball"
print (z.startswith("A"))
print (z.startswith("a"))  #case-sensitivity matters
print ("Hello World!".startswith("H"))  #here directly checking a string instead of using a variable holding a string val
```

    True
    False
    True
    


```python
#strip() function
#It returns the given string after removing any extra spaces before or after the given string, if present. Eg:

m = "      Monkey likes bananas     "
n = "Monkey likes bananas"
o = "Monkey likes bananas      "
print (m)
print (m.strip())
print (n.strip()) #since no extra spcaces are present it won't do anything and return it as it is.
print (o.strip()) #the right side spaces are removed but telling the difference is hard until used with other strings
                  #later on for concatenation or such methods, the white space won't be concatenated if strip() is used.
```

          Monkey likes bananas     
    Monkey likes bananas
    Monkey likes bananas
    Monkey likes bananas
    


```python
#swapcase() function
#Converts uppercase strings to lowercase and lowercase strings to uppercase. Eg :

a = "nEw dELHi iS tHE cAPItal oF inDiA"
print (a.swapcase())
```

    NeW DelhI Is The CapiTAL Of INdIa
    


```python
#title() function
#Makes the first letter of every string after a spcae as uppercase and makes the rest as lowercase.
#It is similar to capitalize() function but capitalize() only makes the first letter as capital not every word 
#after space. Eg:

a = "nEw dELHi iS tHE cAPItal oF inDiA"
print (a.title())
print (a.capitalize())
```

    New Delhi Is The Capital Of India
    New delhi is the capital of india
    


```python
#upper() function
#converts all lower case function to uppercase. It's the opposite of Lowercase function. Eg:

a = "these were all small letters, but were they?"
print (a.upper(),"\n\n")
b = "A mIX Of uPpEr AND lOWeR cASe sTRIng"
print (b.upper())  #converts all to upper case
print (b.lower())  #coverts all to lower case
print (b.swapcase()) #converts all to ALTERNATE case of their existing case
print (b.title())  #only first letter of EVERY word is made uppercase case, rest becomes lowercase
print (b.capitalize()) #only first letter of FIRST word is mader uppercase, rest becomes lowercase 

```

    THESE WERE ALL SMALL LETTERS, BUT WERE THEY? 
    
    
    A MIX OF UPPER AND LOWER CASE STRING
    a mix of upper and lower case string
    a Mix oF UpPeR and LowEr CasE StriNG
    A Mix Of Upper And Lower Case String
    A mix of upper and lower case string
    

<b><hr></b>
These are one of the most commonly used functions of str but there are a few more left which haven't been mentioned and aren't used as widely as the ones mentioned above. You can always explore the rest remaining functions using 
<code>help("str")</code><br>
In your python prompt window.
<br><br>

<hr>
<a id="9D Boolean data type"></a>
<h3> <u><b>(d.) Boolean Data type (True or False)</b></u></h3><br>
This datatype has only two values which are <code><b>True</b></code> and <code><b>False</b></code> (mind the case-sensitivity, T in True is always capital and F in False). <code>True</code> and <code>False</code> are reserved keywords as well which are used usually with conditional statements (if-else) to check whether a given condition is <b>True</b> or <b>False</b>. I guess it will be clearer with examples : <br>



```python
print (7<8)  #True
print (8<7)  #False
print (10>2) #True
```

    True
    False
    True
    

This is also the output that few functions give when they are used. We have come across some of them in str functions.
Eg:


```python
a = "hello"
print (a.islower()) #True
print (a.isupper()) #False
print (a.startswith("h")) #True
print (a.startswith("H")) #False

#We can use this output with if-else conditions to make confirmations for string handling problems and continue
#if a condition for the problem is True or False.
```

    True
    False
    True
    False
    

<hr><br>
<a id="9D i. Comparison Operators"></a>
<b><u>(i.) Comparison Operators in Python</b></u><br>
Bool or Boolean values are usually used with <b>Comparison Operators</b> which are also used in "In-equality algebra" in mathematics. These comparison operators are the same as the ones in C and C++ language. Let's go through them all of them :
<br>
<pre>
1. <code><b>==</code></b>	If the values of two operands are equal, then the condition becomes true.	
2. <code><b>!=</code></b>	If values of two operands are not equal, then condition becomes true.
3. <code><b>></code></b>	If the value of left operand is greater than the value of right operand, then condition becomes true.<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Similar to !=.</li>
4. <code><b><</code></b>	If the value of left operand is less than the value of right operand, then condition becomes true.
5. <code><b>>=</code></b>	If the value of left operand is greater than or equal to the value of right operand, then condition becomes true.
6. <code><b><=</code></b>	If the value of left operand is less than or equal to the value of right operand, then condition becomes true.
    </pre><br><b>Eg :</b>


```python
print ("1 : ",99==99) #True
print ("2 : ",90==99) #False
print ("3 : ",99!=99) #False
print ("4 : ",90!=99) #True
print ("7 : ",4.8 > 4.7)  #True
print ("8 : ",4.8 > 4.8)  #False
print ("9 : ",4.8 < 2.1)  #False
print ("10 : ",2.1 < 4.8) #True
print ("11 : ",4.8>=4.8) #True
print ("12 : ",4.8>=4.7)  #False
print ("13 : ",1.2<=1.2)  #True
print ("14 : ",1.2<= 1.1)  #False       
       
```

    1 :  True
    2 :  False
    3 :  False
    4 :  True
    7 :  True
    8 :  False
    9 :  False
    10 :  True
    11 :  True
    12 :  True
    13 :  True
    14 :  False
    

<hr>
<a id="9E Complex data type"></a>
<h3><u><b>(e.) Complex Numbers Data type (True or False)</b></u></h3><br>
In Mathematics, we use complex numbers to deal with [imaginary numbers.](https://www.mathsisfun.com/numbers/imaginary-numbers.html) Imaginary Numbers are used to denote numbers such as square root of -1 or any negative no.<br>
Imaginary no. is of the form, <code>REAL NO. + IMAGINARY No.</code>, in python, we use <code>Int Value/float value + j</code> to denote the same. Here, "j" is not a variable as it is on the right hand side of the assignment operator (=).<br>
<b>Eg : </b>



```python
a = 1 + 1j    #The 'j' on the right side denotes squareroot of -1, while 1 is the real no. 
b = 2.4 + 5j  #The 5 in front of 'j' is a real no. multiplied with sqaureroot of -1 (5j) while 2.4 is the real no.

#c = j        #This will give error, as python will look for variable 'j' and not consider this 'j' as an imaginary no.
              #Since we haven't declared any variable 'j' (we have only declared variables 'a' and 'b'), python
              #will give error. This can be rectified by putting a one(1) in front of this 'j'. Here, one (1) is
              #the real number. Now python recognizes the 'j' as an imaginary no. and doesn't give error. 

c1 = 1j       #This is the right way to do it. Here, c1 is hodling a complex number data-type

j = 10        #Let's say we declare variable 'j' now, and use it to assign it to another variable 'd'
d = j         #Printing variable 'd' won't give error now as, python now has variables 'a','b','c1' and 'j'. But,
              #variable 'd' is holding on to an integer value, not complex number data-type.

d1 = 10 + 1j  #For complex data-type, having the real-no. or integer or float data-type in addition with 'j' is important.
              #This is a complex no. data-type.
print (a)
print (b)
print (c1)
print (d)
print (d1)
print ("\nSum of variable d and d1 : ",d+d1)  #Only real no. parts are added
print ("\nSum of variable a and b : ",a+b)    #Since, imaginary no. part exists for both, real & imaginary parts
                                              #both are added.


```

    (1+1j)
    (2.4+5j)
    1j
    10
    (10+1j)
    
    Sum of variable d and d1 :  (20+1j)
    
    Sum of variable a and b :  (3.4+6j)
    

<br>
To work with complex no.s, you need to know the domain of imaginary no.s in mathematics and it's usage. But in real-life,
imaginary no.s aren't really used for practical purposes and hence aren't really considered a very important mathetmatic
topic to be aware of.

<hr>
<a id="9F None data type"></a>
<h3><u><b>(f.) None Data type (None)</b></u></h3><br>
None Data Type in python is used to denote the null value. It is declared in the following way:


```python
a = None         #Notice, "N" in None, case-sensitivity is important
print (a)
```

    None
    

The <code><b>None</b></code> Data-type is used as a place-holder for variables that you aren't sure of what value to assign yet. You can use them to assign them a null value and wait till you get a proper value from an user. Hence,
many times in user-defined functions, parameters are passed with <b>None</b>.<br>
<br>Some important facts about None Data-type:
<ul><li> None is not to be confused with True or False. They are different things. </li>
<li> None is not equal to zero (0). 0 is an integer data-type and has mathemetical importance. None is Void. </li>
<li> None is not an empty string. As mentioned before, empty string is denoted as, a="". </li>
<li> Comparing None to anything will always return False except None itself.</li></ul><br> Eg:


```python
a = None
print (a==None)  #True
print (a==False) #False
print (a==True)  #False
print (a==0)     #False
print (a=="")    #False, comparing to empty string
print (a==" ")   #False, comparing to empty space
```

    True
    False
    False
    False
    False
    False
    

<br>
<br>

---
<a id="10. Looping Statements in Python"></a>
<h3><b>10. <u>Looping Statements in Python (For & While Loop)</h3></b></u>


---
<br><b><u>(i.) Need for Looping Statements </u> : </b><br>
<a id="10. i Need for looping statements in python"></a>
Loop Statements are special features of any good programming language as they allow a programmer to execute a block of code under the looping statement multiple times until a required condition is met. This helps us by not having to repeat and type the same piece of code again and again.<br>
One thing to keep in mind is the <b>"Flow of Code"</b> meaning how the code is run by the python interpreter. Most beginners don't keep this in mind and mess up the output as they execute the wrong line of code at the wrong time causing common errors such as <b>"Index out of range"</b> (in case of arrays/list elements calling).

<a id="10. ii For loop staments"></a>
<br><br><b><u>(ii.) For loop Statements in Python (Syntax & Usage)</u> : </b><br><br>
In C language, we wrote the code in the following way for FOR loops :<br>
<code>for (i=0;i&lt;10;i++)
                    {
                       printf("%d",i);
                       printf("\n");
                    }
</code>
<br>
* Here, variable "i" is known as the looping variable which keeps count of how many times a loop needs to run (here, i value starts from 0 goes to on 9 (as i<10 or i==9)).
* <b>i++</b> us known as the increment operator, this is responsible for incrementing or increasing the value of "i" by 1 after each loop statement is executed. <b>i++</b> is equivalent of <b>i = i + 1</b>, in the first loop, <b>i = 0</b>, so <b>i = i + 1</b> becomes <b> i = 0 +1</b> so in next loop, <b>i = 1</b>, then "i" becomes <b>i = 1+1</b> or <b>i=2</b> in the next loop. This goes on until <b>i&lt;10</b>or <b>i = 9</b>.
* The Curly Braces {} are responsible for executing the statements under the FOR loop mutliple times until the loop condition is meant. It tells the C compiler that until this for loop doesn't change from i=0 to i=9, keep repeating the block of code under {} which is <br>
                    {
                       printf("%d",i);
                       printf("\n");
                    }<br>
  So these two printf() statements will be printed 10 times (i=0 to i=9 is 10 times worth of counting).

  <br>
  ---
  <br>In Python, we use the [keyword](https://www.programiz.com/python-programming/keyword-list) <b>"for"</b> just as in C or C++ language to run a for loop but we also use another keyword called as <b>"in"</b> and function called as <b>range()</b> function with it. Hence, the for loop in python is very different than in C or C++ language.
 <br>The basic syntax for <b>for loop</b> in python goes as : <br><br>
 <code>for looping_variable in range(0,10):</code><br> 
 <br>
 Example of the C code above in python language would be the following :
    


```python
for i in range(0,10):
    print (i)
    print ("\n")
```

    0
    
    
    1
    
    
    2
    
    
    3
    
    
    4
    
    
    5
    
    
    6
    
    
    7
    
    
    8
    
    
    9
    
    
    

---
So what is happening here?<br>
<ul>
<li> <b>"for"</b> is a keyword and is used by us to let python know that we are using a "for-loop". The characteristic of for loop is that, it has a beginning, an end and in some cases a skip value (more about these later). But, "for" is same as in C language, we type "for" and python interpreter knows okay a "for loop" is going to be executed here.</li>
    
<li> <b>looping_variable</b> here is "i", just how we had in C or C++ langauge. It can be any variable, it doesn't really matter. But make sure you are using the same variable and not some other variable if you want to use the changing values of "i" as in this case. Meaning, I used <b>print(i)</b> not print(k) or anything else, since only variable "i" is changing from values 0 to 9 not any other variable.</li>
    
<li> <b>"in"</b> is a keyword and is used with secondary or container data-types (list, arrays, tuples, sets, etc are such data-types) mostly to make python interpreter understand that we are talking about the values or elements insde this secondary data type. Understand it in the same way how you understand the english word "in". <Br><b>Eg:</b>The apples are "in" the basket.<br> Now this basket is the container data-type and using the keyword "in" you are going through Apple No. 1, Apple No. 2, etc until the basket gets over. This will be clearer with further examples of "for-loops" later.</li>
<li> <b>range()</b> function is the most tricky one to understand but let's try our best to understand it. <b>range()</b> is a generator function, meaning it generates a collection or group of numbers containing integers values for a specific range. But on it's own it's not really a secondary-data type but more of it's own data-type called as "range" data-type which temporary holds the range of numbers. But on it's own, it's not useful, we need to [type-cast](https://techterms.com/definition/typecasting#:~:text=Terms%20%3A%20Typecasting%20Definition-,Typecasting,an%20integer%20to%20a%20string.) to a secondary data-type or use it in "for-loops" using keywords like "in" which give access to range of numbers held by this weird unusable data-type.<br><br>The arguments or parameters that range() function accepts are as follows : <br><br><code>range(starting_int_value, ending_int_value, skip_int_value)</code><br><br></li>
    ** Here, <b>"start_int_value"</b> is the starting point of your range, i.e., where do you want to start your range from.<br>
    ** Here, <b>"ending_int_value"</b> is the value you want to end your range at, but in range() function  will always return values upto <b>n-1</b> value of the "ending_int_value".<br>
    ** Here, <b>"skip_int_value"</b> acts as the counter, i.e., the decrement or increment manager like how we had <b>i++</b> or <b>i--</b> in C or C++.<br><br>
    Now, in this only <b>"ending_integer_value"</b> is an argument or a compulisory parameter to be passed inside the range() function and range() function will always return values upto <b>n-1</b> value of the <b>"ending_int_value"</b> as mentioned before. Obviously like most functions, you cannot pass range() function without any parameters or empty.<br><br> Let's try to understand this with an example (Kindly read the comments to understand deeply) :


```python
#EXAMPLE 1 : range()

#Here, we will run range() function without passing no arguments or any parameter in it.

print (range())   #see how we will get TypeError telling as range expected "1 argument" but got 0,
                  #so we need to at least pass 1 value inside the paranthesis for it to make it work
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-160-0e629a20b09d> in <module>
          3 #Here, we will run range() function without passing no arguments or any parameter in it.
          4 
    ----> 5 print (range())   #see how we will get TypeError telling as range expected "1 argument" but got 0,
          6                   #so we need to at least pass 1 value inside the paranthesis for it to make it work
    

    TypeError: range expected 1 arguments, got 0



```python
#EXAMPLE 2 : range(ending_float_value)

#Here, we will pass the wrong data-type (float) instead of the right data type (int) inside the 
#paranthesis of range() function and see how it goes.

print (range(7.7))  #Obviously we will get a "TypeError" because, python expects you to enter an integer value
                    #inside the range() function to make it work
    
#So at least one "integer" argument is required to make the range() function work properly. 
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-161-956932f6f851> in <module>
          4 #paranthesis of range() function and see how it goes.
          5 
    ----> 6 print (range(7.7))  #Obviously we will get a "TypeError" because, python expects you to enter an integer value
          7                     #inside the range() function to make it work
          8 
    

    TypeError: 'float' object cannot be interpreted as an integer



```python
#EXAMPLE 3 : range(ending_int_value)

print (range(10))   #A range data-type will be outputted. This holds the value from 0 to 9 but we cannot access it
                    #on it's own until we type-cast it to a secondary data-type like list or tuples
                    #or use this function with for-loop and "in" keyword.


print (type(range(10)))   #To check the data-type of range() function output.
                          #The output is going to be class "range" or data-type range which is not useable on 
                          #it's own.
```


```python

#EXAMPLE 4 : range(ending_int_value) with type-casting to secondary data-type

#Here, we type-cast or change the data-type from range data-type to a list and see the expanded range values inside it.

print (list(range(10)))   #A list data-type will be outputted from 0 to 9 (where, 9 is n-1 of 10, if n = 10, 
                          #then values will be printed till 9, not 10)

#list() function is used to convert container data-types to a list data-type.

#Notice how I haven't mentioned all the 3 parameters which are : "starting_int_value", "ending_int_value" and
#"skip_int_value" and that I have only mentioned one parameter which is "ending_int_value" 
#(Not the other parameters : start_int_value or skip_int_value as they aren't compulsory and range() function will work
#without them as well but not without ending_int_value). Here, when you pass only 1 value inside the python takes it 
#for "ending_int_value" only. 

#Here, python itself adds a default value for "starting_int_value" and "skip_int_value" which are,
# start_int_value = 0   (start from i=0 by default if nothing is mentioned)
# skip_int_value = 1    (keep the increment at i++ or i=i+1 by default if nothing is mentioned)

#Hence, that's why even though we don't mention it our range starts from 0 and is incremented by 1 only.
```

    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
    

---
We can conclude one thing with the following above examples. <br>
<b>range()</b> function needs at least <u>one "integer" argument</u> and has <u>two optional arguments</u> (also known as parameters).<br>
Here, the one compulsory argument is the "ending_int_value" because python cannot decide where we want to end the range.<br>
The other optional parameters (not arguments per say, but parameters) are "starting_int_value" and "skip_int_value"
because even if you don't mention them, python by default sets, start_int_value = 0 and skip_int_value = 1.
<br><b>Eg : </b>


```python
#EXAMPLE 5 : range(starting_int_value, ending_int_value, skip_int_value)

#here, we will keep start_int_value = 0
                    #end_int_value = 10
                    #skip_int_value = 1 
        
print (list(range(0,10,1)))  #Notice how we get the same output as above example. 

#This is because as I mentioned, python defaults start_int_value & skip_int_value 0 and 1 respectively even if 
#you don't mention them.

#But we can obviously change it as per our wishes by manually mentioning them. 
#Check the next examples
```

    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
    


```python
#EXAMPLE 6(a) : range(start_int_value, end_int_value)

print (list(range(1,11)))  #Notice how I still haven't given 3 parameters but only 2.
                           #Here, start_int_value = 1 (mentioned manually by me, but not compulsary)
                           #Here, end_int_value = 11 (mentioned manually by me, but is compulsary. It will print till
                                    #10 since, n-1 of 11 is 11-1=10)
                           #Here, skip_int_value = 1 (set by python on its own to default value 1)
            
#Now since I have manually mentioned the start_int_value, python won't use the default value for start_int_value
#which is 0.

#ALso notice, how we get range from 1 to 10, not 0 to 11 or 0 to 10 as we get n-1 of 11 which is 10 and we mentioned
#and as to why it begans with 1 and not 0, I already mentioned in the line above.
```

    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    


```python
#EXAMPLE 6(b) : range(start_int_value, end_int_value)

print (list(range(11,1)))  #Notice how I still haven't given 3 parameters but only 2.
                           #Here, start_int_value = 11 (mentioned manually by me, but not compulsary)
                           #Here, end_int_value = 1 (mentioned manually by me, but is compulsary. It should print till 0
                                    #coz n-1 of 1 is 1-1=0)
                           #Here, skip_int_value = 1 (set by python on its own to default value 1)
            
#Now since I have manually mentioned the start_int_value, python won't use the default value for start_int_value
#which is 0.

#But, since the 
   #start_int_value > end_int_value
    #and the increment is by positive 1 (by default), we cannot decrease (going from 11 to 1 is descending order)
    #hence python won't print anything as our generated list will be empty. (Refer to example 7(c) for more details)
```

    []
    


```python
#EXAMPLE 7(a) : range(start_int_value, end_int_value,skip_int_value)

print (list(range(2,21,2)))  #Here, I have given 3 parameters (all of them) so no default values will be used.
                             #Here, start_int_value = 2 (begins at 2 since I manually set it)
                             #Here, end_int_value = 21 (will print till 20 (n-1 of 21), set by me)
                             #Here, skip_int_value = 2 (Here, the increment will now be by 2, i.e, i = i + 2,
                                     #so it will skip by 2 and give us an even series, set by me manually)
                
#This is the multiplication table of 2.
```

    [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]
    


```python
#EXAMPLE 7(b) : range(start_int_value, end_int_value,skip_int_value)

print (list(range(3,31,3)))  #Here, I have given 3 parameters (all of them) so no default values will be used.
                             #Here, start_int_value = 3 (begins at 3 since I manually set it)
                             #Here, end_int_value = 31 (will print till 20 (n-1 of 31), set by me)
                             #Here, skip_int_value = 3 (Here, the increment will now be by 3, i.e, i = i + 3,
                                     #so it will skip by 3 and give us an odd series, set by me manually)
                
#This is the multiplication table of 3.
```

    [3, 6, 9, 12, 15, 18, 21, 24, 27, 30]
    


```python
#EXAMPLE 7(c) : range(start_int_value, end_int_value, skip_int_value)

print (list(range(30,-31,-3))) #Here, I have given 3 parameters (all of them) so no default values will be used.
                               #Here, start_int_value = 30 (begins at 30 since I manually set it)
                               #Here, end_int_value = -31 (will print till -30 (n+1 of -31, -31+1= -30), set by me)
                                        #In case of negative "end_int_value", it prints till n+1 of n, here, n = -31
                                        #so, it will print till n+1 of it, i.e., -31 + 1 = -30.
                               #Here, skip_int_value = -3 (Here, the decrement will now be by -3, i.e, i = i - 3,
                                        #so it will skip by 3 and give us an odd negative series, set by me manually)
```

    [30, 27, 24, 21, 18, 15, 12, 9, 6, 3, 0, -3, -6, -9, -12, -15, -18, -21, -24, -27, -30]
    


```python
#EXAMPLE 8(a): Implementing range() function with for-loops

#We saw how to use range() functions with list() function but the same principle is used for "For-loop" as well.
#As mentioned earlier, the keyword "in" helps us to access the unusable range of numbers that are in the range data type.
#The "in" keyword kind of treats the range data-type as a temporary list and goes through each element or value 
#from first index to the last index and then outputs them.

#Eg:
for i in range(30,-31,-3): #The colon (:) are equivalent of curly braces {} in C or C++ language.
    print (i,end=" ")       #Notice the "indentation" of print() is inside the for-loop, the print() function isn't
                           #directly under the for keyword, I have added a gap (4 spaces or 1 tab space to be exact)
                           #to let python know that this print() function is related to the for loop and is to be
                           #repeated until the for-loop is completed and that this print() function isn't to be
                           #just printed once.
                    
                           #end=" " , refers to print in the same line and add a space.
                                     #By default, everytime one loop is completed
                                     #python will print the next integer value of "i" under the next line, but
                                     #due to end=" ", it will print it in the same line and adds " " (an empty space)
                                     #at the end of it.
                                     #try only, print(i) and print(i,end="") and print (i,end="$") to see the difference. 

    #This is wrong way to use indentation:
    
#for i in range(30,-31,-3):
#print (i,end="")          #Notice how no extra tab space or spaces follow before the print() function so python
                           #will interpret it as a statement that is independent of the for-loop statement
                           #but a for-loop statement needs to have atleast one line of code under it
                           #so we will get any error as here, python thinks that under for-loop we have no block of code
                           #only.

            
#Notice how the output isn't surrounded by [] (square brackets) as in examples 4 to 7 as the output isn't a 
#list data-type but just a range of numbers printed one after the other.
#This is because we are using for-loop and "in" keyword.
```

    30 27 24 21 18 15 12 9 6 3 0 -3 -6 -9 -12 -15 -18 -21 -24 -27 -30 


```python
#EXAMPLE 8(b): Implementing for-loops with only 2 parameters (similar to example 6(a))

for i in range(10,20):     #skip_int_value is set to "1" by default by python, since we haven't set any value manually
    print (i)              #since, end=" " isn't used, all the values will be printed in next line.
                           #and not in the same line.
    
    #Output is printed till n-1 of 20 which is 19.
```

    10
    11
    12
    13
    14
    15
    16
    17
    18
    19
    

<a id="10. iii Nested for loop"></a>
<br><b><u>(iii.) Nested For loop Statements </u> : </b><br><br>
Nested "for-loops" refers to an inner for-loop inside an outer for-loop. This is usually done to execute matrix problems (problems containing 2D dimension, meaning row and columns, etc). Here, the inner for-loop is used for transvering or for travelling through the columns (From left to right, one column after another) while the outer for-loop is used for going to next row (understand it like going to next line of a table).<br>
<br><b>Eg : </b>


```python
#Printing multiplication table from 2 to 4.

for i in range(2,5):
    #This is the outer loop
    print ("\nThe table of %d is : "%(i))   #Here, %d is acting as a place-holder for printing values of i
    for j in range(1,11):
        #This is the inner loop
        print ("\t%d x %d = %d"%(i,j,i*j))  #in first left-most %d, value of "i" will be printed
                                            #in second mid %d, value "j" will be printed
                                            #in last right-most %d, value of i*j will be printed
                
#Here, the inner-loop (looping_variable "j") will run first from 1 to 10 values while the value of "i"
#from outer-loop will remain the same.
     #First loop -> when i=2 (since, start_int_value of outer loop is "2"), j will change from 1 to 10.
     #Second loop -> when i=3 ("i" gets incremented by 1), j will once again gets initialized from 1 and get incremented
                      #till 10.
     #third loop -> when i=4 (last loop as n-1 of 5 is 4, and 5 is the end_int_value of outer loop)
                    #variable "j" will change from 1 to 10 again.
        
#Understand that only the outer loop is getting looped "thrice", hence three loops, but within each of these 3 loops,
#the inner loop is looped 10 times (from 1 to 10), so the inner loop technically 
#runs 3*10 = 30 times (outer_loop_count x inner_loop_count = total_inner_looop_count)
```

    
    The table of 2 is : 
    	2 x 1 = 2
    	2 x 2 = 4
    	2 x 3 = 6
    	2 x 4 = 8
    	2 x 5 = 10
    	2 x 6 = 12
    	2 x 7 = 14
    	2 x 8 = 16
    	2 x 9 = 18
    	2 x 10 = 20
    
    The table of 3 is : 
    	3 x 1 = 3
    	3 x 2 = 6
    	3 x 3 = 9
    	3 x 4 = 12
    	3 x 5 = 15
    	3 x 6 = 18
    	3 x 7 = 21
    	3 x 8 = 24
    	3 x 9 = 27
    	3 x 10 = 30
    
    The table of 4 is : 
    	4 x 1 = 4
    	4 x 2 = 8
    	4 x 3 = 12
    	4 x 4 = 16
    	4 x 5 = 20
    	4 x 6 = 24
    	4 x 7 = 28
    	4 x 8 = 32
    	4 x 9 = 36
    	4 x 10 = 40
    

---
Like this we can have multiple nested loops until required. As demonstrated from above example, you can see that examples 7(a) and 7(b) where implemented using one nested for-loop instead of two seperate for-loops as shown in 7(a) and 7(b).
<br><br>Nested for-loops are very important concept in <b>competitive programming</b> as most people get confused with the flow of the program when it comes to "Nested for loops"
