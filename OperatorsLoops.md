# Operators and Loops

## Operators

All complex expressions are joined by operators, such as = and +. An expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.  

x = 2 is an example of an expression that assigns values
var x = 2 + 3 is an example of an expression that evaluates

JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator: 2 + 3.

A unary operator requires a single operand, either before or after the operator: x++ or ++x.

There are different kinds of operators.

1. Assignment operators - An assignment operator assigns a value to its left operand based on the value of its right operand. x = f()
2. Comparison operators - A comparison operator compares its operands and returns a logical value based on whether the comparison is true. 2 == 2 True
3. Arithmetic operators - An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. ++ adds 1 to operand  
4. Bitwise operators - A bitwise operator treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers. a & b	Returns a one in each bit position for which the corresponding bits of both operands are ones.
5. Logical operators - Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. !expr	Returns false if its single operand that can be converted to true; otherwise, returns true.
6. BigInt operators - Most operators that can be used between numbers can be used between BigInt values as well. BigInt addition  const a = 1n + 2n; // 3n
7. String operators - In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings. console.log('my ' + 'string'); // console logs the string "my string"
8. Conditional operator - The conditional operator is the only JavaScript operator that takes three operands. The operator can have one of two values based on a condition. const status = age >= 18 ? 'adult' : 'minor';
9. Comma operator - The comma operator (,) evaluates both of its operands and returns the value of the last operand.  
10. Unary operators - A unary operation is an operation with only one operand.  
11. Relational operators - A relational operator compares its operands and returns a Boolean value based on whether the comparison is true.

## Loops

Loops offer a quick and easy way to do something repeatedly. There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)  

1. For Statements - A *for* loop repeats until a specified condition evaluates to false.
2. Do...While Statement - The *do...while* statement repeats until a specified condition evaluates to false.
3. While Statement - A *while* statement executes its statements as long as a specified condition evaluates to true.
4. Labeled Statement - A *label* provides a statement with an identifier that lets you refer to it elsewhere in your program.
5. Break Statement - Use the *break* statement to terminate a loop, switch, or in conjunction with a labeled statement.
6. Continue Statement - The *continue* statement can be used to restart a **while**, **do-while**, **for**, or **label** statement.
7. For...In Statement - The *for...in* statement iterates a specified variable over all the enumerable properties of an object.
8. For...Of Statement - The *for...of* statement creates a loop Iterating over iterable objects (including Array, Map, Set, arguments object and so on), invoking a custom iteration hook with statements to be executed for the value of each distinct property.

[Back to Home page](/README.md)

### Additional resources

- [Letter to a Friend](/SummeryForAFriend.md)
- [Notes on Text Editor](/TextEditorCommand.md)
- [Notes on Git](/GitNotes.md)
- [Note on Wireframs and HTML](/WireframeHTML.md)
- [Notes on CSS](/CSSnotes.md)
- [Notes on Java Script](/js1.md)
- [Notes on Functions](/NotesOnFunctions.md)
- [Notes on Operators and Loops](/OperatorsLoops.md)
