# mix
The official home of Mix

Mix Docs

Hello, welcome to the offical documentation of Mix 1.0. If you are looking for the most recent documentation, then this is your doc. Please note: this is in no way a tutorial but a small guide showing all functions and keywords

~Built-in Keywords and Functions~

print{statement}; -- The Mix equivalent of the common print() or printf() function. Displays the text passed in the terminal/shell

prompt{statement}; -- The Mix equivalent of functions such as input() (python) cin (C++) etc... Displays the prompt and accepts user input. The answer is stored in the variable answer.

var name : value; -- Creates a variable called name and stores the value in it. NOTE: In future updates (most likely Mix 2.x.y), there will be support for typing

array name : no items -- Creates a one-dimensional array called name with the specified number of items

2dArray name : no rows, no columns; -- Creates a two-dimensional array called name with the specified number of rows and columns

vector name : no items; -- Creates a flexible array style list with the specified number of items

//Comment -- Creates a comment which is not compiled

function {name}{parameters}: -- Creates a function called name with the specified parameters with the block that follows it.

END; -- Tells the compiler that the current function/loop/class/block is over

if {statement}: -- Mix's if block

else, if {statement}: -- Mix's else if (elif) block

else: -- Mix's else block

for {declaration, condition, action}: -- Mix's for loop. Runs the following block until the condition given is true. After the end of each iteration, the action given is executed. Using Mix2Py, this compiles to

[START CODE]
variable = value
while (condition):
	code
	action
[END CODE]

foreach {variable name, iterate-able object}: -- Loops through each object in the given iterate-able object, assigning the adress of the index to the variable name.

while {condition} -- Loops while the condition is true

~~Compiler~~

Right now, Mix 1.0 only uses Mix2Py. This means that when Mix is compiled, it is compiled to python 3. In the future, there will be other standards such as Mix2JS, Mix2C, Mix2PHP, Mix2Java (maybe even Mix2HTML if you're lucky!)


~~Final Words~~

Although this documentation may be short in length, it will be added to with future versions and standards of Mix. Also, this documentation will eventually be formatted with pictures and everything.
