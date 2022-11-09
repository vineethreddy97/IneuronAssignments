## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Answer: Python is object oriented and high level language . If we talk about both these terms high-level language is easy to 
learn and its easy to understand for humans Where as object oriented means it has lot of data rather than functions.


Q2. Why is Python called a dynamically typed language?

Answer: Because type of the variable is determined only during runtime in python.

Q3. List some pros and cons of Python programming language?

Answer:
Pros: Beginner-friendly,portable,Highly Scalable
Cons:Security,High Memory Consumpion,Garbage collection leads to potential memory losses



Q4. In what all domains can we use Python?
Answer: Python is used in datascience,automation,AI & Machine learning,Audio/video applications,
console applications,Desktop GUI,Application Development

Q5. What are variable and how can we declare them?

Answer: A declaration of a variable is where a program says that it needs a variable.
For example a=3 here a is variable

Q6. How can we take an input from the user in Python?
Answer: By using Input function the user can take input 
For example:
a=int(input("Enter a number:"))

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Answer: String

Q8. What is type casting?
Answer: Type casting is when you assign a value of one primitive data type to another type.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Answer:yes By using split()

Q10. What are keywords?
Answer: Python has a set of keywords that are reserved words that cannot be used as variable names, function names, or any other identifiers.

Q11. Can we use keywords as a variable? Support your answer with reason.
Answer:No we cannot use keyword as a variable because it has defualt values.

Q12. What is indentation? What's the use of indentaion in Python?
Answer:Indentation refers to the spaces at the beginning of a code line.Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
Answer:By using print() function

Q14. What are operators in Python?
Answer:Operators are special symbols in Python that carry out arithmetic or logical computation. The value that the operator operates on is called the operand.
Arithmetic operators:These are used to perform mathematical operations like addition, subtraction, multiplication, etc.
Comparison operators:These  are used to compare values. It returns either True or False according to the condition.
Logical operators:These  are the and, or, not operators.



Q15. What is difference between / and // operators?
Answer: / operation:Divide left operand by the right one which always results into float.
    // operation:Floor division - division that results into whole number adjusted to the left in the number line

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Answer:

string="iNeuron"*4
print(string)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Answer:
number=int(input("Enter the number:"))
if number%2==0:
    print("It is a even number")
else:
    print("It is a odd number")


Q18. What are boolean operator?
Answers: The boolean type in Python has two possible values: False and True.
A boolean expression, also known as a logical expression, can only have the states true or false.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Answer:
True
True
False
True

Q20. What are conditional statements in Python?

Answer:A conditional statement is used in your program to manage conditions. These statements direct the program as it makes decisions in response to the circumstances it encounters. In python there are 3 conditional statemts if,if-else,if-elif-else

Q21. What is use of 'if', 'elif' and 'else' keywords?

Answer: 
If :The  keyword if evaluates as true, the block of code will execute
Elif:Multiple conditions can be checked by including one or more elif checks after your initial if statement. But these statements will be executed
Else:It is an optional to  add an else response that will execute if the condition is false

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Answer:
age=int(input("Enter your age:"))
if age>=18:
    print("I can vote")
else:
    print("I cannot vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Answer:
sum=0
numbers = [12, 75, 150, 180, 145, 525, 50]
for num in numbers:
    if num%2==0:
        sum=sum+num
print(sum)
    


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Answer: 
a=int(input("enter the first number: "))
b=int(input("enter the second number: "))
c=int(input("enter the third number: "))
if a>b and a>c:
    print("a is greatest number")
elif b>a and b>c:
    print("b is greatest number")
else:
    print("c is greatest number")


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Answer:
numbers = [12, 75, 150, 180, 145, 525, 50]
for num in numbers:
    if num>500:
        break
    elif num>150:
        continue
    elif num%5==0:
        print(num)