# Python Programming: Lecture 4 and Lecture 5 Tasks

## Overview

This repository contains the completed practical work for Lecture 4 and Lecture 5 of the Python programming coursework. The work focuses on conditional statements, loops, control statements, comprehensions, functions, input validation, and type hinting.

The purpose of this repository is to document the completed programming work in a clear and professional format. The notebooks contain practical exercises and assignments that apply the concepts introduced in the lectures. The README explains the topics covered, the purpose of each task, the expected results, the problem-solving approach, and the process for running and submitting the work.

Lecture 4 focuses on conditional statements, loops, nested loops, and control statements. These concepts are important because they allow a program to make decisions and repeat instructions according to specific conditions. The practical work includes number processing, password checking, countdown logic, dictionary creation, character frequency, prime number checking, and student grade processing.

Lecture 5 builds on these foundations by introducing list comprehension, dictionary comprehension, set comprehension, functions, input validation, arguments, type hinting, and type validation. These features help make Python programs more concise, reusable, readable, and structured.

The completed notebooks demonstrate these concepts through practical examples. The work includes a Student Grade System, List Categorizer, FizzBuzz Dictionary, prime number generation, number summarization, and an Email Filtering System.

## Repository Contents

The repository contains the following main files:

- `lecture4.ipynb`
- `lecture5.ipynb`
- `README.md`

The `lecture4.ipynb` notebook contains the practical exercises and assignments related to conditional statements, loops, nested loops, and control statements.

The `lecture5.ipynb` notebook contains the practical exercises and assignments related to comprehensions, functions, validation, and type hinting.

The `README.md` file documents the work and explains how the notebooks can be executed.

## Learning Objectives

The main objectives of this practical work are:

1. Understand conditional statements in Python.
2. Use `if`, `elif`, and `else` to make decisions.
3. Understand nested conditional statements.
4. Use `for` loops to repeat operations.
5. Use `while` loops for condition-based repetition.
6. Understand nested loops.
7. Apply `break`, `continue`, and `pass`.
8. Process lists, strings, and dictionaries.
9. Calculate character and word information.
10. Identify prime and non-prime numbers.
11. Use list, dictionary, and set comprehensions.
12. Create reusable functions.
13. Understand default, positional, and keyword arguments.
14. Understand `*args` and `**kwargs`.
15. Validate function inputs.
16. Use type hints.
17. Apply Python concepts to practical programming problems.

## Lecture 4: Conditional Statements, Loops, and Control Statements

Lecture 4 introduces the mechanisms used to control the execution of a Python program. Programs often need to make decisions instead of executing every instruction in exactly the same way. Conditional statements allow a program to choose between alternatives. Loops allow instructions to be repeated.

The lecture also introduces control statements that change the normal behavior of loops. These statements include `break`, `continue`, and `pass`.

### Conditional Statements

Conditional statements are used when a program needs to make a decision based on a condition.

The main conditional structures are:

- `if`
- `elif`
- `else`

The `if` statement checks whether a condition is true. If it is true, the related block is executed. The `elif` statement provides another condition, while `else` provides a default block when the previous conditions are not satisfied.

Conditional statements are used in many of the Lecture 4 tasks. They are required when checking divisibility, validating scores, identifying prime numbers, and applying FizzBuzz rules.

### Walrus Operator

The lecture also introduces the walrus operator, written as `:=`.

The walrus operator allows a value to be assigned as part of an expression. It can be useful when a value needs to be calculated and checked within the same expression.

This topic provides an introduction to another form of Python syntax for working with values and conditions.

### Nested If Statements

A nested `if` statement is a conditional statement placed inside another conditional statement.

Nested conditions are useful when one decision depends on the result of another decision. They allow a program to represent multiple levels of logic.

The main purpose of learning nested conditions is to understand how more detailed decision-making can be represented in Python.

## For Loops

A `for` loop repeats a block of code for each value in a sequence or range.

For example, a range can be used to process numbers from one value to another. A loop can then apply the same condition or calculation to every value.

Several Lecture 4 exercises use `for` loops to process ranges of numbers.

### Practice Task 1: Numbers Divisible by 7

The first practice task requires printing the numbers from 1 to 100 that are divisible by 7.

The solution uses a `for` loop and a divisibility condition. A number is divisible by 7 when the remainder after division by 7 is zero.

The output is:

7, 14, 21, 28, 35, 42, 49, 56, 63, 70, 77, 84, 91, 98.

This task demonstrates how a loop and a condition can be combined to filter values from a range.

### Practice Task 2: Sum of Even Numbers

The second task requires calculating the sum of all even numbers from 1 to 50.

The program checks the values in the specified range and adds the values that satisfy the even-number condition.

The final result is 650.

This task demonstrates repeated processing, conditional checking, and accumulation of a result.

### Practice Task 3: Password System

The password system task provides three attempts for entering the correct password.

A loop is used to control the number of attempts. If the correct password is entered, the program prints `Access granted`. If all three attempts are unsuccessful, the program prints `Blocked`.

The task also demonstrates loop control because the program can stop processing further attempts once the correct password is entered.

This example shows how loops and conditions can represent a simple real-world interaction between a user and a program.

### Practice Task 4: Countdown

The fourth task requires a countdown from 10 to 1 using a `while` loop.

When the countdown reaches 5, the program uses `break` and prints `Midpoint reached`.

This demonstrates that a `while` loop can continue according to a condition and that `break` can terminate the loop before its normal completion.

### Practice Task 5: First Number Divisible by 13 and 7

The fifth task searches through the numbers from 1 to 500 and finds the first number divisible by both 13 and 7.

The program checks the values one by one. When the first matching number is found, `break` stops the loop.

The result is 91.

This task demonstrates why `break` is useful when only the first matching value is required. Once the required result has been found, additional iterations are unnecessary.

### Practice Task 6: Word Length Dictionary

The sixth task works with a list of words and creates a dictionary containing each word and its length.

Only words longer than four characters are included.

For the example list:

`["apple", "cat", "banana", "book", "python", "fiza", "computer"]`

the resulting dictionary is:

`{'apple': 5, 'banana': 6, 'python': 6, 'computer': 8}`

This task combines list processing, string properties, conditions, and dictionary creation.

### Practice Task 7: Character Frequency

The seventh task creates a dictionary containing the frequency of each character in a string.

The example uses the string `programming`.

The program examines each character and keeps track of the number of times it occurs. The dictionary therefore provides a simple frequency summary of the string.

This task demonstrates how dictionaries can be used for counting and basic data processing.

### Practice Task 8: Prime and Non-Prime Transformation

The eighth practice task processes the numbers from 100 to 150.

Prime numbers remain as their numeric values, while non-prime numbers are replaced with the text `Not Prime`.

The solution uses prime-checking logic to determine the category of each number.

This task combines loops, conditions, mathematical logic, and list construction.

## Lecture 4 Assignments

### Assignment A: Student Grade System

The Student Grade System is a larger practical assignment that combines several concepts from Lecture 4.

The program collects student names and five subject scores through a loop. Entering `done` ends the input process using `break`.

Invalid scores are handled using `continue`, allowing the program to skip invalid input and continue processing.

For each student, the program calculates:

- Total marks
- Average marks
- Highest score
- Lowest score
- Student count

The sample student in the notebook is `fiza`. The five scores are:

90, 98, 97, 89, 92

The total is 466 and the average is 93.20.

This assignment combines loops, conditions, input handling, `break`, `continue`, calculations, and collection processing.

The main learning point is that several basic programming concepts can work together to solve one practical problem.

### Assignment B: List Categorizer

The List Categorizer assignment starts with:

`l = list(range(1, 21))`

The values are separated into three categories:

- Even numbers
- Odd numbers
- Multiples of 5

The even numbers are:

`[2, 4, 6, 8, 10, 12, 14, 16, 18, 20]`

The odd numbers are:

`[1, 3, 5, 7, 9, 11, 13, 15, 17, 19]`

The multiples of 5 are:

`[5, 10, 15, 20]`

This assignment demonstrates how one list can be processed using multiple conditions.

### Assignment C: FizzBuzz Dictionary

The FizzBuzz Dictionary assignment creates a dictionary for numbers from 1 to 30.

The required rules are:

- `Fizz` for values divisible by 3.
- `Buzz` for values divisible by 5.
- `FizzBuzz` for values divisible by both 3 and 5.
- `None` for values that satisfy neither condition.

The important part of this task is applying the conditions correctly. The combined condition must be handled so that values such as 15 and 30 receive `FizzBuzz`.

This assignment provides practice with conditional logic and dictionary creation.

## Lecture 4 Control Statements

Three important control statements covered in the lecture are `break`, `continue`, and `pass`.

### Break

`break` immediately terminates the current loop.

It is useful when the required result has already been found or when a specific condition requires the loop to stop.

In the completed work, `break` is used in the password system, countdown task, and search for the first number divisible by both 13 and 7.

### Continue

`continue` skips the remaining statements in the current iteration and moves to the next iteration.

It is useful when one value should be ignored without stopping the complete loop.

The Student Grade System uses this idea for invalid scores.

### Pass

`pass` performs no operation. It can be used as a placeholder when a statement is required syntactically but no action is needed at that point.

Understanding these three statements helps control loop behavior more precisely.

## Lecture 5: Comprehensions and Type Hinting

Lecture 5 extends the programming skills developed in Lecture 4.

The major topics include:

- List comprehension
- Dictionary comprehension
- Set comprehension
- Functions
- Input validation
- Default arguments
- Positional arguments
- Keyword arguments
- `*args`
- `**kwargs`
- Type hinting
- Type validation
- Type hints for lists, tuples, dictionaries, and sets
- Optional values
- `mypy`

## List Comprehension

A list comprehension is a concise way to create a list from an iterable.

It can be used when a list needs to be generated, filtered, or transformed.

For simple operations, a comprehension can express the logic in fewer lines than a traditional loop while keeping the main operation visible.

The prime and non-prime transformation is one example where comprehension can be used to represent the required transformation.

## Dictionary Comprehension

Dictionary comprehension provides a concise way to construct dictionaries.

It is useful when keys and values can be generated from an existing collection or from a clear relationship between two values.

The Lecture 5 work applies dictionary-based processing to tasks involving data transformation and frequency counting.

## Set Comprehension

Set comprehension creates a set using comprehension syntax.

A set stores unique values, so it is useful when duplicate results are not required.

The Email Filtering System uses set comprehension to extract unique usernames from company email addresses.

## Functions

Functions organize reusable pieces of code.

A function can receive input through parameters, perform operations, and return a result.

Functions reduce repeated code and make individual pieces of logic easier to understand and test.

Lecture 5 introduces basic functions and several ways of providing arguments.

### Default Arguments

A default argument has a predefined value. If the caller does not provide that argument, the default value is used.

This is useful when a function has a common behavior that should apply unless the caller specifies another value.

### Positional Arguments

Positional arguments are supplied according to the order of parameters in a function.

The first supplied value corresponds to the first parameter, the second value corresponds to the second parameter, and so on.

### Keyword Arguments

Keyword arguments are supplied using the parameter name.

This can make a function call clearer because the relationship between a value and its parameter is directly visible.

### `*args`

`*args` allows a function to receive a variable number of positional arguments.

It is useful when the number of positional values is not fixed.

### `**kwargs`

`**kwargs` allows a function to receive a variable number of keyword arguments.

It is useful when different named values may be supplied to a function.

## Input Validation

Input validation checks whether the provided data is suitable for the operation being performed.

The Lecture 5 work demonstrates validation for function inputs. A function can check the expected type of an input and also check whether a numeric value meets the required conditions.

Validation makes programs more reliable because inappropriate values can be handled before they cause unexpected behavior.

## Type Hinting

Type hints communicate the expected data types of variables, function parameters, and return values.

For example, a function can indicate that it expects an integer and returns a list of integers.

Type hints improve readability and make the intended structure of the code easier to understand.

Lecture 5 also covers type hints for:

- Lists
- Tuples
- Dictionaries
- Sets
- Optional values

The lecture introduces `mypy` as a tool that can help check type-related issues.

## Lecture 5 Practical Work

### Finding the First Number Divisible by 13 and 7

The Lecture 5 work revisits the problem of finding the first number divisible by both 13 and 7.

The result is 91.

Using a familiar problem in a later lecture helps connect earlier programming logic with newer Python techniques.

### Character Frequency for `hello`

The character frequency example uses the string `hello`.

The program counts each character and stores the results in a dictionary.

The character `l` occurs twice, while the other characters occur once.

This reinforces the use of dictionaries for frequency counting.

### Prime Number Transformation

The notebook also demonstrates prime and non-prime transformation for numbers from 100 to 150.

In this work, list comprehension and the `all` function are used as part of the prime-checking logic.

Prime numbers remain numeric values, while non-prime values are represented as `Not Prime`.

This demonstrates how comprehension can combine transformation and conditional logic in a compact form.

## Prime Number Function

The `prime_upto(n)` function generates prime numbers up to a specified value.

The function includes type and value validation.

For example:

`prime_upto(50)`

returns:

`[2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47]`

This function combines several Lecture 5 concepts. It uses reusable function structure, validation, type expectations, and mathematical processing.

The function also demonstrates the importance of validating input. A reusable function should handle unsuitable input in a controlled manner.

## Number Summary Function

The `number_summary(numbers)` function summarizes a list of numbers.

The returned dictionary contains:

- Total
- Average
- Maximum
- Minimum
- Even numbers

For the example list:

`[10, 15, 20, 25, 30, 35, 40]`

the results are:

- Total: 175
- Average: 25.0
- Maximum: 40
- Minimum: 10
- Even numbers: `[10, 20, 30, 40]`

This function demonstrates how several calculations can be grouped into one reusable operation.

Instead of writing separate code each time these statistics are needed, the function can be called with different lists.

## Email Filtering System

The Email Filtering System is the main practical assignment in Lecture 5.

The example data contains:

- `fiza@company.com`
- `ayesha@gmail.com`
- `almira@company.com`
- `zara@company.com`

The target domain is:

`@company.com`

The first step is to filter email addresses belonging to the company domain.

List comprehension is used for this filtering operation.

The company email addresses are:

- `fiza@company.com`
- `almira@company.com`
- `zara@company.com`

The second step extracts the usernames from the company addresses.

Set comprehension is used so that the usernames are represented as unique values.

This assignment demonstrates a practical use of list comprehension and set comprehension. It also shows how simple text-processing rules can be used to classify data.

## Concepts Demonstrated Across Both Lectures

The completed work connects the concepts from Lecture 4 and Lecture 5.

### Decision Making

Conditional statements allow the program to choose an action based on a condition.

Examples include divisibility checks, score validation, prime-number checking, and FizzBuzz rules.

### Repetition

Loops allow the same logic to be applied to many values.

Both `for` and `while` loops are used in the practical work.

### Loop Control

`break` and `continue` provide additional control over repetition.

These statements are useful when processing user input or searching for a required value.

### Collection Processing

Lists, dictionaries, and sets are used to store, organize, count, filter, and transform information.

### Data Transformation

Several tasks transform one form of data into another.

Examples include:

- Words to word-length dictionaries
- Strings to character-frequency dictionaries
- Numbers to prime or non-prime representations
- Emails to filtered company-email lists
- Emails to unique username sets

### Reusable Functions

Functions package logic into reusable units.

The prime number and number summary examples show how larger operations can be placed inside functions.

### Validation

Validation helps ensure that functions receive appropriate input.

The `prime_upto` work demonstrates validation of both type and value.

### Type Communication

Type hints make expected input and output types clearer.

This is especially useful for reusable functions and larger programs.

## Problem-Solving Approach

The tasks were solved by breaking each problem into smaller steps.

First, the required input and expected output were identified. Next, the Python concept needed for the problem was selected. A repeated operation generally required a loop, while a filtering or transformation problem could use a comprehension.

Conditions were then added where necessary. The program was tested using the examples and expected results from the lecture work.

For calculations, the operations were organized so that the final result could be checked.

For dictionary tasks, the key and value relationship was identified before constructing the dictionary.

For prime-number tasks, the program needed a clear way to determine whether a number is prime.

For the Student Grade System, the problem was divided into input collection, validation, calculations, and results.

For the Email Filtering System, the problem was divided into filtering the email addresses and extracting unique usernames.

This approach makes programming problems easier to understand and reduces the chance of mixing unrelated logic.

## Testing and Verification

The completed examples were checked against the expected results from the lecture work.

Important verified results include:

- Numbers divisible by 7 from 1 to 100 are printed correctly.
- The sum of even numbers from 1 to 50 is 650.
- The first number divisible by both 13 and 7 is 91.
- The word-length dictionary includes only words longer than four characters.
- Character frequency is calculated using a dictionary.
- Prime and non-prime transformation is applied to the range 100 to 150.
- The Student Grade System calculates the sample student's total as 466 and average as 93.20.
- The List Categorizer separates even, odd, and multiple-of-5 values correctly.
- The FizzBuzz Dictionary assigns the required labels to numbers from 1 to 30.
- `prime_upto(50)` returns the expected prime numbers.
- `number_summary` calculates the expected summary values.
- The Email Filtering System identifies the three company email addresses.

Testing is important because a program can execute without an error and still produce an incorrect result. Comparing outputs with the expected results helps verify that the logic is working correctly.

## How to Run the Notebooks

The notebooks can be opened using Jupyter Notebook, JupyterLab, or Google Colab.

### Using Google Colab

1. Open Google Colab.
2. Choose the option to open an existing notebook.
3. Upload or open `lecture4.ipynb`.
4. Run the notebook cells in order.
5. Repeat the process for `lecture5.ipynb`.
6. Review the outputs displayed below the code cells.

The work uses standard Python features, so no special external library installation is required for these lecture tasks.

### Using Jupyter Notebook

1. Install Python and Jupyter if they are not already installed.
2. Place the notebook files in a working directory.
3. Start Jupyter Notebook.
4. Open `lecture4.ipynb`.
5. Run the cells in order.
6. Open and run `lecture5.ipynb`.

## Recommended Repository Structure

A simple repository structure is recommended:

```text
python-lecture-4-5-tasks/
|
|-- lecture4.ipynb
|-- lecture5.ipynb
|-- README.md
```

Keeping the notebooks and README together makes the repository easy to understand.

Clear filenames allow another person to identify the notebook associated with each lecture immediately.

## GitHub Submission Workflow

After completing and checking the notebooks, the work can be uploaded to GitHub.

### Step 1: Create a Repository

Create a new GitHub repository with a clear name such as:

`python-lecture-4-5-tasks`

The repository can be public if the assignment requires a shareable GitHub link.

### Step 2: Upload the Notebooks

Upload:

- `lecture4.ipynb`
- `lecture5.ipynb`

Make sure the notebooks contain the completed solutions and the relevant outputs.

### Step 3: Upload the README

Upload `README.md` to the root of the repository.

GitHub automatically displays a root-level README on the repository home page.

### Step 4: Check the Repository

Open the repository and verify that:

- Both notebooks are present.
- The README is displayed correctly.
- Code formatting is readable.
- Notebook outputs are visible where required.
- There are no unnecessary files.
- File names are correct.

### Step 5: Copy the Repository Link

After checking the repository, copy its GitHub URL.

This link will be needed for the LinkedIn post.

## LinkedIn Submission

The assignment requires a summary of the completed work to be shared on LinkedIn together with the GitHub repository link.

The LinkedIn post should briefly explain what was completed and what concepts were practiced.

A professional summary can mention conditional statements, loops, loop control, comprehensions, functions, input validation, type hinting, practical Python assignments, and GitHub documentation.

The GitHub repository link should be included in the LinkedIn post.

After publishing the post, copy the URL of the published LinkedIn post. That LinkedIn post URL should then be submitted as the final task submission if that is the required submission format.

## Submission Checklist

Before submitting the assignment, verify the following:

- [ ] Lecture 4 tasks are completed.
- [ ] Lecture 5 tasks are completed.
- [ ] `lecture4.ipynb` is included.
- [ ] `lecture5.ipynb` is included.
- [ ] `README.md` is included.
- [ ] The README opens correctly on GitHub.
- [ ] Notebook code runs without unexpected errors.
- [ ] Important outputs have been checked.
- [ ] The GitHub repository link is copied.
- [ ] A LinkedIn summary post has been prepared.
- [ ] The GitHub repository link is included in the LinkedIn post.
- [ ] The LinkedIn post is published.
- [ ] The LinkedIn post URL is copied.
- [ ] The LinkedIn post URL is submitted as required.

## Skills Developed

The completed work develops several practical Python programming skills.

The first major skill is control-flow management. Conditional statements and loops are fundamental because they allow software to respond to different situations and process repeated information.

The second skill is problem decomposition. Larger tasks such as the Student Grade System become easier when input, validation, calculations, and output are considered separately.

The third skill is collection processing. Lists, dictionaries, and sets are used to represent and transform data.

The fourth skill is writing reusable functions. Functions reduce repetition and make programs easier to maintain.

The fifth skill is input validation. Validation helps protect a program from inappropriate values.

The sixth skill is concise Python syntax. Comprehensions provide a compact way to build collections while keeping the main logic visible.

The seventh skill is code readability through type hints. Type hints communicate intended data types and can support static checking.

## Practical Importance

The concepts in these lectures are not limited to classroom exercises.

Conditional statements are used whenever software needs to make decisions. Loops are used whenever repeated processing is required. Dictionaries and sets are useful for organizing and analyzing information. Functions are essential for building maintainable programs.

Comprehensions are useful for filtering and transforming collections. Input validation is important in applications that receive data from users or other systems. Type hints can improve communication between developers and support type checking.

The practical assignments provide a small introduction to these programming patterns.

For example, the Student Grade System represents a simple information-processing application. The Email Filtering System represents a basic data-filtering problem. The Number Summary Function demonstrates how a reusable function can produce several related statistics from one input collection.

## Code Quality Considerations

Good Python code should be readable, logically organized, and easy to test.

Meaningful variable and function names make the purpose of code easier to understand.

Conditions should be written clearly rather than unnecessarily complicated.

Functions should have a focused purpose whenever possible.

Validation should happen before values are used in operations that require a particular type or range.

Comprehensions should be used when they make the code clearer and more concise. If a comprehension becomes difficult to read, a normal loop may be easier to understand.

Type hints can be added to communicate expected data types, especially for reusable functions.

These practices help transform code from a basic solution into code that can be understood and maintained by others.

## Connection Between Lecture 4 and Lecture 5

Lecture 4 provides the foundation for controlling program execution. Lecture 5 builds on that foundation by showing how the same logic can be organized and expressed more efficiently.

Lecture 4 demonstrates loops for processing ranges and collections. Lecture 5 introduces comprehensions, which can provide a shorter way to construct lists, dictionaries, and sets.

Lecture 4 uses conditions to solve filtering and classification problems. Lecture 5 continues the same idea while placing some of the logic inside reusable functions.

Lecture 4 introduces practical control through `break` and `continue`. Lecture 5 adds validation and type information, making reusable code more controlled and understandable.

Together, the two lectures demonstrate an important progression in programming: first learning how program flow works, and then learning how to write that logic in a more reusable, concise, and structured form.

## Future Improvements

The current work focuses on the concepts and tasks provided in the lectures. These programs could be expanded in future projects.

The Student Grade System could be extended to store student records in a file or database and generate reports.

The List Categorizer could accept user-defined ranges or lists rather than using a fixed range.

The FizzBuzz Dictionary could be converted into a reusable function that accepts a maximum number as an argument.

The prime number function could be extended with additional validation and more efficient prime checking.

The number summary function could be expanded with additional statistics.

The Email Filtering System could support multiple domains and more detailed email processing.

These improvements are not required for the current assignment, but they show how the lecture concepts can serve as foundations for larger programs.

## Conclusion

The Lecture 4 and Lecture 5 practical work provides a strong foundation in Python programming.

Lecture 4 focuses on conditional statements, loops, nested logic, and control statements. Through the exercises and assignments, the work demonstrates how Python can make decisions, repeat operations, search for values, validate input, and process collections.

Lecture 5 extends these skills through list, dictionary, and set comprehensions, functions, input validation, arguments, type hints, and type checking. The practical examples demonstrate how these features can be applied to prime number generation, numerical summaries, character frequency, and email filtering.

The Student Grade System, List Categorizer, FizzBuzz Dictionary, `prime_upto` function, `number_summary` function, and Email Filtering System provide practical applications of the concepts.

Overall, the completed notebooks demonstrate practical understanding of Python control flow, collection processing, reusable functions, validation, and concise programming techniques. The work also provides a foundation for more advanced Python programming and data-processing tasks.

This repository documents the completed work in a structured format so that the solutions, concepts, results, and execution process can be reviewed clearly.

## Final Repository Summary

The repository contains the completed Python work for two lectures.

Lecture 4 covers:

- Conditional statements
- Walrus operator
- Nested `if`
- `for` loops
- Nested loops
- `while` loops
- `break`
- `continue`
- `pass`
- List and dictionary processing
- Character frequency
- Prime number checking
- Student Grade System
- List Categorizer
- FizzBuzz Dictionary

Lecture 5 covers:

- List comprehension
- Dictionary comprehension
- Set comprehension
- Functions
- Input validation
- Default arguments
- Positional arguments
- Keyword arguments
- `*args`
- `**kwargs`
- Type hinting
- Type validation
- Collection type hints
- Optional values
- `mypy`
- Prime number function
- Number summary function
- Email Filtering System

The completed repository demonstrates practical understanding of these concepts through executable Jupyter notebooks and structured documentation.
