# java-script-revision
_read about javascript and revise about it_
## variables 
- Variables in JavaScript are declared using one of three keywords: let, const, or var. let allows you to declare block-level … HashMaps in Java. Associative arrays in PHP. JavaScript objects are hashes. … An important detail of nested functions in JavaScript is that they can access variables in their parent function's scope:
- Variables in JavaScript are not directly associated with any particular value type, and any variable can be assigned (and … In JavaScript, objects are the only mutable values. … JavaScript Data Structures and Algorithms by Oleksii Trekhleb Computer Science in JavaScript by Nicholas C. Zakas
## Data Type
- This article attempts to list the built-in data structures available in JavaScript and what properties they have. … The BigInt type is a numeric primitive in JavaScript that can represent integers with arbitrary magnitude. … JavaScript Data Structures and Algorithms by Oleksii Trekhleb Computer Science in JavaScript by Nicholas C. Zakas
- JavaScript has eight primary data types, which are categorized into two main groups:
**primitive and non-primitive** (reference) types. JavaScript is a dynamically typed language, meaning variables can hold any data type, and you don't need to explicitly declare the type. 
**Primitive Data Types**
Primitive types represent** single, simple, and immutable values.** There are seven primitive data types: 

    - **string**: Represents textual data and is enclosed in single quotes ('...'), double quotes ("..."), or backticks (`...`).
   ** - number**: Represents both integer and floating-point numbers. It also includes special numeric values like Infinity, -Infinity, and NaN (Not-a-Number).
    **- bigint**: Represents integers with arbitrary precision, used for numbers that exceed the safe integer limits of the regular number type. A BigInt value                    is created by appending n to the end of an integer literal.
   ** boolean:** Represents a logical entity with only two possible values: true or false.
   ** undefined:** Represents a variable that has been declared but not assigned a value.
   ** null**: A special value that represents the intentional absence of any object value. It is a standalone type that has a single value null.
    **symbol**: Introduced in ES6, it represents a unique and immutable identifier, often used as an object property key to avoid naming conflicts. 

**Non-Primitive Data Type**
Non-primitive types, also known as reference types, are used to store collections of data and more complex entities. They are mutable and stored by reference in memory. 
    ** object:** The only non-primitive data type. Everything else in JavaScript (arrays, functions, dates, etc.) is a type of object.
       ** Arrays ([])**: A special type of object for storing ordered collections of data, accessible by index.
       ** Functions:** Objects with the additional capability of being callable to perform tasks.
        Dates, Regular Expressions, Maps, Sets, etc., are also built-in objects. 
**2. Objects (Reference Types)**
Objects are complex data types that can store collections of data or more complex entities. Unlike primitives, objects are mutable.
   ** Object**: A collection of key-value pairs.
 **   Array: **A special type of object used to store ordered lists.
 **   Function: **Even functions are technically objects in JavaScript!
**3. The typeof Operator**

If you ever aren't sure what type of data you're working with, you can use the typeof operator to check.

  **  A Quirky Note**: In JavaScript, typeof null actually returns "object". This is a famous, long-standing bug in the language that was never fixed to avoid breaking old websites!
**4. Dynamic Typing in Action**
Because JS is dynamic, a single variable can change its "type" based on what you put inside it:
Would you like to see how JavaScript handles "Type Coercion" (what happens when you try to add a string and a number together)?
## Operations
In JavaScript,** operators** are the symbols used to perform calculations, compare values, or manipulate data. If variables are the "nouns" of your code, operators are the "verbs."
JavaScript operators are grouped into several categories based on what they do.
**1. Arithmetic Operators**
These are used to perform mathematical calculations.
**2. Assignment Operators**
These are used to assign values to variables. You’ve already seen the basic =, but there are "shorthand" versions too.
    Basic: let x = 10;
    Add & Assign (+=): x += 5; (Same as x = x + 5)
    Subtract & Assign (-=): x -= 2; (Same as x = x - 2)
**3. Comparison Operators**
These compare two values and return a Boolean (true or false). These are the backbone of logic in programming.
    Strict Equality (===): Returns true if both the value and type are the same. (Always use this!)
    Strict Inequality (!==): Returns true if they are not equal.
    Greater/Less Than: >, <, >=, <=
    Watch out: In JS, there is also == (loose equality). It tries to "guess" if things are equal even if they are different types (e.g., 5 == "5" is true). It’s generally safer to stick to ===.
**4. Logical Operators**
Used to combine multiple conditions together.
**5. String Operators**
In JavaScript, the + operator has a double life. If you use it on strings, it joins them together (this is called concatenation).
**6. The "Order of Operations"**
Just like in school math, JavaScript follows Operator Precedence. Multiplication happens before addition unless you use parentheses.
total=(5+10)∗2
In the example above, the result is 30, not 25.
## Functions
In JavaScript, a function is a reusable block of code designed to perform a particular task. Think of it like a "recipe": you define the steps once, and then you can "cook" (execute) that recipe whenever you need it without rewriting the instructions.
Functions are the building blocks of any JS application because they help you keep your code DRY (Don't Repeat Yourself).
**1. Function Anatomy**
To create a function, you use the function keyword, followed by a name, a set of parentheses (), and curly braces {}.
    Parameters: These are placeholders (like variables) that represent the data the function needs to do its job.
    Arguments: These are the actual values you "pass" into the function when you call it.
    Return Statement: This is how the function "spits out" a result so you can use it elsewhere.
**2. Basic Example**
Here is a function that calculates the area of a rectangle:
**3. Different Ways to Write Functions**
JavaScript has evolved over the years, giving us multiple ways to write functions:
**A. Function Declaration (The Standard Way)
B. Function Expression**
Here, a function is stored inside a variable.
**C. Arrow Functions (The Modern Way)**
Introduced in ES6 (2015), these are shorter and very common in modern React or Node.js development.
**4. Why Use Functions?**
    Organization: Break large problems into small, manageable pieces.
    Reusability: Write code once, use it a thousand times.
**    Maintenance: If you need to change how a calculation works, you only have to change it in one place (inside the function).
5. Scope: The "Invisibility" Rule**
Variables defined inside a function are locally scoped. This means they only exist inside that function and cannot be accessed from the outside.
## Control Flow
In JavaScript, Control Flow is the **order in which the computer executes statements **in a script. By default, code runs from top to bottom, but control flow structures allow you to skip sections, repeat actions, or choose between different paths based on conditions.
Think of it like a Choose Your Own Adventure book for your code.
**1. Conditional Statements (Decision Making)**
These allow your code to perform different actions based on whether a condition is true or false.
The if...else Statement
The most common way to branch your code.
The switch Statement
Best used when you have many discrete values to check against a single variable. It's often cleaner than a long chain of else if statements.
**2. Loops (Repetitive Tasks)**
Loops allow you to run the same block of code multiple times.
The for Loop
Used when you know exactly how many times you want to repeat an action.
The while Loop
Used when you want to repeat an action as long as a condition remains true, but you might not know how many times that will be.
**3. Logical Operators in Control Flow**
You can combine multiple conditions using the operators we discussed earlier (&&, ||, !).
**4. Break and Continue**
These keywords give you even finer control inside loops:
    break: Exits the loop entirely.
    continue: Skips the rest of the current iteration and jumps to the next one.
