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
