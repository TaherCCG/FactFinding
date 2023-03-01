#### FactFinding
<p>AWSre/StartProjects - Fact Finding Exercise: Allow learners to work on the self-paced exercise for the allotted time.</p>


<h1 align="center">Python fact finding exercise</h1>

## Questions

<ol>
<li><h3>Define a list and tuple in Python. Provide some examples.</h3></li>
<ul>
<li>List:</li>
<ul>
<li>A list is a data structure in Python that is a mutable, or changeable, ordered sequence of elements and can be defined using any variable name. Each element or value that is inside of a list is called an item. Lists are defined by having values between square brackets [ ]
Lists can have/store different data types.
</br>
<li>List items are ordered, changeable, and allow duplicate values.</li>
<li><em>Below are some examples of how to define a list and what data types they can contain.</em></li>
<ul>
<li><code>myList=[]  <em>This defines an empty list.</em></code></li>
<li><code>myList=[name, 35, 5.11, 5J, True, data, including, duplicates]
</code></li>
<li><code>friends = ['John','Michael','Terry','Eric','Graham']
print(friends[0],friends[4])
print(friends[3])
print(friends[2:])
print(friends[2:4])</code></li>
<ul>
<li><code><em>output:</em>
John Graham</br>
Eric</br>
['Terry', 'Eric', 'Graham']</br>
['Terry', 'Eric']</code></li>
</ul>
</ul>
<li>List items are indexed, the first item has index [0], the second item has index [1] etc.</li>
<li>Lists contain items and it can be of any data types. Integers, Complex, Strings, Float, Boolean and can have multiple duplicates with unlimited amount of items</li>
</ul>
</br>
<li>Tuple:
<ul>
<li>Tuples are used to store multiple items in a single variable, can be defined using any variable name and assigning different values 
to the tuple inside the round brackets (). The tuple is ordered, unchangeable, and allows duplicate values.</li>
<li>Ordered means that the items have a defined order, and that order will not change.</li>
<li>Unchangeable means that we cannot change, add or remove items after the tuple has been created.</li>
<li>Indexed means that they can have items with the same value.</li>
<ul>
<li>example of same value:</br>
<code>thistuple = ("apple", "banana", "cherry", "apple", "cherry")</code></li>
<li>A tuple with strings, integers and boolean values:</br>
<code>tuple1 = ("abc", 34, True, 40, "male")</code></li>
<li>To create a tuple with only one item, you have to add a comma after the item, otherwise Python will not recognize it as a tuple.</br>
<code>thistuple = ("apple",)</br>
print(type(thistuple))</br>
</br>
#NOT a tuple</br>
thistuple = ("apple")</br>
print(type(thistuple))</code></li>
</ul>
<li>Tuples make the code safe from any accidental modification. If a data is needed in a program which is not supposed to be changed, then it is better to put it in ‘tuples’ than in ‘list’. They are also faster then lists and Tuples can be used as dictionary keys if it contains immutable values like strings, numbers or another tuple.</li>
</ul>
</ul>
</br>
<li><h3>What is a namespace in Python?</h3></li>
<ul>
<li>A namespace is a collection of names and the details of the objects referenced by the names. </li>
<li>In python, there are four types of namespaces, namely built-in namespaces,global namespaces, local namespaces and enclosing namespaces.</li>
<li>A built-in namespace contains the names of built-in functions and objects. It is created while starting the python interpreter, exists as long as the interpreter runs, and is destroyed when we close the interpreter. It contains the names of built-in data types,exceptions and functions like print() and input().</li>
<li>Global namespaces are defined at the program or module level. It contains the names of objects defined in a module or the main program. A global namespace is created when the program starts and exists until the program is terminated by the python interpreter.</li>
<li>A local namespace is defined for a class, a function, a loop, or any block of code. The names defined in a block of code or a function are local to it. The variable names cannot be accessed outside the block of code or the function in which they are defined. The local namespace is created when the block of code or the function starts executing and terminates when the function or the block of code terminates.</li>
<li>A function or a block of code defined inside any function can access the namespace of the outer function or block of code. Hence the outer namespace is termed as enclosing namespace for the namespace of the inner function or block of code.</li>
</ul>
</br>
<li><h3>What is the difference between a local variable and a global variable?</h3></li>
<ul>
<li>Local Variables are created when a function starts its execution and are lost when the function ends.  Also local variables do not offer data sharing.</li>
<li>Global variables are declared outside functions and are accessible by all functions in the program. Global variables are not very reliable because any function in the program can alter its value. They are useful when many functions are using the same set of data.</li>
</ul>
</br>
<li><h3>What is an IDE? Mention some common IDEs that could be used with Python.</h3></li>
<ul>
<li>An Integrated Development Environment (IDE) is software that developers/programers use to write code.  It increases developer productivity by combining capabilities such as software editing, building, testing and packaging in a easy to use application.</li>
<li>Here are few IDE's:</li>
<ul>
<li>Visual Studio Code - using it while I am typing this Markdown file</li>
<li>PyCharm - is a dedicated python IDE.</li>
<li>Spyder - is an open-source cross-platform integrated development environment for scientific programming in the Python language</li>
<li>Thonny - is an integrated development environment for Python that is designed for beginners.</li>
<li>Atom - it was a free and open-source text and source code editor for macOS, Linux, and Microsoft Windows with support for plug-ins written in JavaScript, and embedded Git Control. Developed by GitHub, Atom was a desktop application built using web technologies.</li>
</ul>
</ul>
</br>
<li><h3>What are modules in Python?  Provide some examples.</h3></li>
<ul>
<li>Module is a file that contains code to preform a specific task. A module may contain variables, functions and classes etc.  We use modules when our code gets bigger so we call them in to our program and reuse the code in the module instead of putting everything in our program. This makes our code organised and easier to maintain </li>
<ul>
<li>Example 1:</br>
 <em>import standard math module</em></br> 
<code>import math</br></code>

 <em>use math.pi to get value of pi</em></br>
<code>print("The value of pi is", math.pi)</code>
</li>
<li>Example 2:</br>
<em>importing os module</em></br> 
<code>import os</code></br>
<em>Get the current working</br> 
directory (CWD)</em></br>
<code>cwd = os.getcwd()</code></br>
<em>Print the current working</br> 
directory (CWD)</em></br> 
<code>print("Current working directory:", cwd)</code> 
</li>
</ul>
<li>As shown above using OS Module.  OS module in python provides functions for interacting with the operating system. </li>
</ul>

</br>
<li><h3>What is the difference between an array and a list?</h3></li>
<ul>
<li>The main difference between a list and array is that list can't manage arithmetic operations and Array can manage arithmetic operations. </li>
<li>When it comes to flexibility, the list is perfect as it allows easy modification of data. Whereas the array is not suitable as it does not allow easy modification of data.</li>
<li>Arrays consume less memory, and it favours longer sequence of data than a list.</li>
</ul>
</br>
<li><h3>What are operators?  Provide some examples.</h3></li>
<ul>
<li>An operator is a character that represents a specific mathematical or logical action or process.</li>
<li>In Python there are 7 different operators. Python divides the operators in the following groups: </li>
<ul>
<li>Arithmetic operators examples:</li>
<ul>
<li>"*"  multiplication</li>
<li>"+"	 Addition</li>
<li>"//" Floor division</li>
</ul>
<li>Logical Operators example:</li>
<ul>
<li>"and" 	Returns True if both statements are true	</li>
<li>"or"	Returns True if one of the statements is true</li>
<li>"not"	Reverse the result, returns False if the result is true</li>
</ul>
<li>Assignment Operators examples:</li>
<ul>
<li>"="     x = 5 <em>is same as</em> x = 5</li>
<li>"-="	x -= 3 <em>is same as</em>	x = x - 3</li>
<li>"^="	x ^= 3 <em>is same as</em>	x = x ^ 3</li>
</ul>
<li>Comparison Operators examples:</li>
<ul>
<li>"=="	Equal</li>
<li>">"     Greater than</li>
<li>"<="	Less than or equal to</li>
<li></li>
</ul>
<li>Membership Operators examples:</li>
<ul>
<li>"in" 	Returns True if a sequence with the specified value is present in the object. <em>example :</em> x in y</li>
<li>not in	Returns True if a sequence with the specified value is not present in the object. <em>example :</em> x not in y </li>
</ul>
<li>Bitwise Operators examples:</li>
<ul>
<li>"&" <em>is named "AND" </em>	Sets each bit to 1 if both bits are 1</li>
<li>"|"	<em>is named "OR"</em>	Sets each bit to 1 if one of two bits is 1</li>
<li>"^"	<em>is named "XOR"</em>	Sets each bit to 1 if only one of two bits is 1</li>
</ul>
</ul>
</Ul>
<Ul>
<li><em>To learn more about operators and precedence order refer to [Python Documentation](https://www.w3schools.com/python/python_operators.asp"w3schools.com")</em></li>
</Ul>
</br>
</br>

    If you would like a copy of this information, please use the [fork](https://github.com/TaherCCG/FactFinding/fork"click here to get a copy") feature on GitHub to get a copy.
