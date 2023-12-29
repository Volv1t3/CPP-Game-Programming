<h1 style="text-align: center; color: aliceblue; font-family: 'Segoe UI Semilight', sans-serif; font-weight: bold; font-size:  12pt ">
CMP4300 | Introduction to Game Programming in C++ 
</h1>
<h6 style="text-align: center; color: aliceblue; font-family: 'Segoe UI Semilight', sans-serif; font-weight: bold; font-size:  12pt ">
Santiago Arellano  
</h6>

***
<p>
The following file will be a representation (not accurate to the course material and not representative of the information given in any content file) of the topics covered in the C++ practice
for the class' more advanced topics. We will structure this in terms of a list of concepts which will include example code and todos for practices.
</p>

<ul style="color: aliceblue; list-style: lower-roman; font-family: Consolas, sans-serif; font-size: 12pt">
<br>
<li>
 <b style="color: coral">Arguments in Main Function: </b> the arguments that we would usually see in the main function in any program when we first open it through a C++ editor
<code> argc and char* argv[]</code> are literal representations of the reading, of the program itself, of the command line arguments passed into it through the command line exeuction.
Such that if your program requires or allows user specialization through command line arguments then you can have it run like that.
<br>
<code>argc:</code> represents the length of the string containing all the params passed in command line,
<br><code>char* argv[]:</code> represents the pointer to the string read through the console.
</li>
<br>
<li>
<b style="color: coral"> C++ Standard Template Library: </b> This is a collection of functions, classes, generics, methods, algorithms, helpers, iterators, holders, etc. 
All of these functions are defined in the standard library in the best and purest implementation to allow you to work quickly and efficiently.
<br><br>
However, the STL library does not handle anything when it comes to user interfaces, rendering, etc. This forces us to work with external libraries like ImGUI or SFML.
<br><br>Always use <code> std::</code> this is better since this is basically a a namespace that holds the standard library files, and using namespaces 
we can compartmentalize our work and variables for further use or changes. 
</li>


</ul>
