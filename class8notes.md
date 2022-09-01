# Computer Logic

This chapter describes JavaScript's expressions and operators, including assignment, comparison, arithmetic, bitwise, logical, string, ternary and more.

## Comparison operators
* Equal (==)
* Not equal (!=)
* Strict equal (===)
* Strict not equal (!==)
* Greater than (>)
* Greater than or equal (>=)
* Less than (<)
* Less than or equal (<=)
** Note: => is not a comparison operator but rather is the notation for Arrow functions.**

## Assignment operators
*An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

[you can find examples here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)

## Loops and iteration

*Loops offer a quick and easy way to do something repeatedly. This chapter of the* [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide) *introduces the different iteration statements available to JavaScript.*

*You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another.

1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
3. The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.
4. If present, the update expression incrementExpression is executed.
5. Control returns to Step 2.

**EX**
<form name="selectForm">
  <label for="musicTypes">Choose some music types, then click the button below:</label>
  <select id="musicTypes" name="musicTypes" multiple>
    <option selected>R&B</option>
    <option>Jazz</option>
    <option>Blues</option>
    <option>New Age</option>
    <option>Classical</option>
    <option>Opera</option>
  </select>
  <button id="btn" type="button">How many are selected?</button>
</form>

## While Statement
A *while* statement executes its statements as long as a specified condition evaluates to *true*

If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.


