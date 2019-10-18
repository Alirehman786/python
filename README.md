# python
I will tell you how to use idle to make a password with loops in python
For Loop
The for loop that is used to iterate over elements of a sequence, it is often 
used when you have a piece of code which you want to repeat "n" number of time. 

It works like this: " for all elements in a list, do this "

Let's say that you have a list
computer_brands = ["Apple", "Asus", "Dell", "Samsung"]
for brands in computer_brands:
    print brands
That reads, for every element that we assign the variable brands, 
in the list computer_brands, print out the variable brands
numbers = [1,10,20,30,40,50]
sum = 0
for number in numbers:
    sum = sum + numbers
print sum
for i in range(1,10):
    print i
Break

 
To break out from a loop, you can use the keyword "break". 
for i in range(1,10):
    if i == 3:
	break
    print i
Continue
The continue statement is used to tell Python to skip the rest of the statements 
in the current loop block and to continue to the next iteration of the loop.
for i in range(1,10):
    if i == 3:
	continue
    print i
While Loop
The while loop tells the computer to do something as long as the condition is met
it's construct consists of a block of code and a condition. 

It works like this: " while this is true, do this "
computer_brands = ["Apple", "Asus", "Dell", "Samsung"]
i = 0
while i < len(computer_brands):
    print computer_brands(i)
    i = i + 1
That reads, as long as the value of the variable i is less than the length of the 
list (computer_brands), print out the variable name.
while True:
    answer = raw_input("Start typing...")
    if answer == "quit":
        break
    print "Your answer was", answer
Let's show another example.

Here we set the variable counter to 0. 

For every time the while loop runs, the value of the counter is increased by 2. 

The while loop will run as long as the variable counter is less or equal with 100.
counter = 0
while counter <= 100:
    print counter
    counter + 2
Nested Loops
In some script you may want to use nested loops. 

A nested loop is a loop inside a loop. 
for x in range(1, 11):
    for y in range(1, 11):
        print '%d * %d = %d' % (x, y, x*y)
