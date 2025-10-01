#intro to python
#day 1

I learnt about connecting anaconda and creating a virtual environment (venv):

C:\Users\laptop\anaconda3\Scripts\activate.bat
cd C:\Users\Laptop\Desktop\sigh\DA\Krish naik bootcamp
code .
conda create -p venv python==3.12

i also learnt that in order to open an ipynb file in vscode i need to connect the kernel to ipykernel, i do this by clicking on "detecting kernel" on the top of the ipynb and then clicking on the venv just created. this would prompt you to install ipykernel, and in order to do that we run:
"pip install ipykernel"
it is also considered a good practice to add in all these requirements in a file "requirements.txt"
now it is ready for typing and running code.

I brushed up on basic concepts that i had learnt in the very initial classes of python.

i recapped variables, case sensitivity, how indents replace curly braces in python, how single line comments use a hash (#) and milti line comments use 3 quotes ('''), how to print the type of the variable (print(type())), and the concept of "type inference" which compliments the dynamic typing of python(variable type is determined at runtime). I also recapped "name errors"  which arise upon the usage of incorrect variables (uninitialized, or wrong case). I learnt about how to type a long line of code in python in multiple lines to support readability, and also its contradiction, that is how we can type multiple lines of code in one single line.


#day 2

we went in depth into the concept of variables, including naming conventions and type casting. we recapped the data types and which datatypes can be converted to which other ones, and which cant be converted, and their consequences. ex, a=5 which is an int can be converted to float and string, but it would print 5.0 if casted to float and while a='25' which is a string can be casted to int, but a='anjana' cant be casted to int or float. this would give us a "value error". furthermore, we proceeded to recap the "input" function and typecasting within the input function, since the default input taken is in the form of a string. we also looked back at the classic "simple calculator" example.

we also looked into each data type specificlly along with thier functions. we looked into string, int, float and bool and executed a few examples of each. we also looked into concatenation and learnt that only strings can be concatenated along with other strings, as opposed to other types.

We looked into operators and their types as well. First we looked into some of the basic mathematical (arithmetic) operators like +,-,*,/,//,%,**. then, we saw comparison operators like >,=,<,>=,<=,!=. then we went into logical operators like and, or and not. 

list(map(int, input().split()))

input() → waits for you to type something (like: 1 2 3)
.split() → splits your input by spaces → gives: ['1', '2', '3']
map(int, ...) → converts each '1', '2', '3' to integers → 1, 2, 3
list(...) → makes that into a list → [1, 2, 3]

matrix = [list(map(int, input("Enter (columns) numbers: ").split())) for _ in range(3)]

#new day

today i learned about positional and keyword arguements.
while defining a function, if there are multiple paramters to be passed within, we can use *args or **kwargs depending on the type of parameter to be passed.

*args, called positional arguements is used to pass multiple parameters, example (n1,n2,n3,n4,n5,"hello","hope youre well") can simply be replaced by (*args)

**kwargs, called keyword positional arguements, is used to pass multiple key-value pairs specifically into the function. ex, (name:"anjana", age:21, country:"India", college:"dayananda sagar") can simply be replaced by (* *kwargs)

i also learnt how one fucntion can return multiple parameters in its return statement. 
