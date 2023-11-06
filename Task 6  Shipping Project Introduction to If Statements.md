Using "if statements" allows programs to make decisions. They let a program chose a decision based on a condition. Below is an example of how an if statement can be used to determine the section of code (which print statement) to use.
~~~
if age < 17:
    print('You are NOT old enough to drive')
else:
    print('You are old enough to drive')
~~~
In the example, if you are younger than 17, the program will output the text "You are NOT old enough to drive"; however, if you are over the age of 17, the program will output "You are old enough to drive". Depending on a condition (in this example, it's the age variable), the program will run different code sections.

There are some key components we note from our code example above:

- The if keyword indicates the beginning of the if statement, followed by a set of conditions.
- The if statement is only run if the condition (or sets of conditions) is true. In our example, it's age < 17; if that condition is true (age is below 17), the code within the if statement runs. Per the example, if certain conditions are not met, the program can default to running code shown in the else part of the if statement. 
- A colon : marks the end of the if statement.
- Note the indentation. Anything after the colon that is indented, is considered part of the if statement, which the program will execute.

![](https://github.com/A3lpha/Learning-Python-on-TryHackMe/blob/main/source%20code/5.png)


If statements are essential in programming and will be something you use a lot.

Answer the questions below
In this exercise, we will code a small application that calculates and outputs the shipping cost for a customer based on how much they've spent.

In the code editor, click on the "shipping.py" tab and follow the instructions to complete this task.

No answer needed
Once you've written the application in the code editor's shipping.py tab, a flag will appear, which is the answer to this question.
```THM{IF_STATEMENT_SHOPPING}```

In shipping.py, on line 12 (when using the Code Editor's Hint), change the customer_basket_cost variable to 101 and re-run your code. You will get a flag (if the total cost is correct based on your code); the flag is the answer to this question.

```THM{MY_FIRST_APP}```

