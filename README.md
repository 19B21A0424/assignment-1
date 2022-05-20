# assignment-1:--1. What are the differences between operators and values in the following?
2. What is the difference between string and variable?
spam
'spam'

Ans.: We can say that variable is a container which can store different data types like string, integer, float, etc.

  whereas string is a data type which can be stored in a variable.
print(type('spam'))
<class 'str'>
3. Describe three different data forms.
Ans.: There are various data types some of them are:

1. string
2. int
3. float
4. list
5. tuple
6. set
7. dictionary (dict)
8. complex

String (str): this is a data type used for text, placed in between " " or ' '.

         for example: x = 'Hello World' where hello world is of type str.
Integer(int): this is a numerical data type which is used for numbers without decimal points.

         for example: y = 10
Float : this is also a numerical data type but with decimal point.

         for example: z = 10.11
x = 'Hello World'
print('x data type is:', type(x))
y = 10
print('y data type is:', type(y))
z = 10.11
print('z data type is:', type(z))
x data type is: <class 'str'>
y data type is: <class 'int'>
z data type is: <class 'float'>
4. What makes up an expression? What are the functions of all expressions?
5. In this chapter, assignment statements such as spam = 10 were added. What's the difference between a declaration and an expression?
Decleration of variable means binding it to a data type 
like in our case spam is used for binding 10 to it as an integer value.
Whereas as an expression is the combination of operators and operands for example: 10+20 
6. After running the following code, what does the variable bacon contain?
bacon = 22

bacon + 1

bacon = 22
bacon +1 # this does not adds to our variable bacon
print('Bacon contains:', bacon)
Bacon contains: 22
7. What should the values of the following two terms be?
'spam' + 'spamspam'

'spam' * 3

a = 'spam' + 'spamspam'
a
'spamspamspam'
b = 'spam'*3
b
'spamspamspam'
in a it concatinate both strings and in b it multiplies.

8. Why is it that eggs is a true variable name but 100 is not?
100 is a literal number, not a variable. 100 is always 100 , you cannot set it to something else. 
A variable is like a box in which you can store a value. 100 is a value that can be stored in the variable.
9. Which of the following three functions may be used to convert a value to an integer, a floating-point number, or a string?
#To convert an integer or floating point number to a string we simply can place it between " " or ' '
a = 10
b = 10.12
print("Data type of a is {}, and data type of b is {}".format(type(a),type(b)))
c = "10"
d = "10.12"
print("Data type of c is {}, and data type of d is {}".format(type(c),type(d)))

# For Float ----> Int

num = 10.11
print("data type of num is: ", type(num))

num = int(num)
print("now its type is: ", type(num))
Data type of a is <class 'int'>, and data type of b is <class 'float'>
Data type of c is <class 'str'>, and data type of d is <class 'str'>
data type of num is:  <class 'float'>
now its type is:  <class 'int'>
10. What is the error caused by this expression? What would you do about it?
'I have eaten ' + 99 + ' burritos.'

Correct_form = 'I have eaten ' + '99' + ' burritos.'
Correct_form
'I have eaten 99 burritos.
