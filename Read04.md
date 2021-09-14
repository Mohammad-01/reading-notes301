## What is a ‘Controlled Component’?

* A controlled component is a component that renders form elements and controls them by keeping the form data in the component's state. In a controlled component, the form element's data is handled by the React component (not DOM) and kept in the component's state.

## Why would we use a ternary operator?

* The conditional (ternary) operator is the only JavaScript operator that takes three operands: a condition followed by a question mark (?), then an expression to execute if the condition is truthy followed by a colon (:), and finally the expression to execute if the condition is falsy. This operator is frequently used as a shortcut for the if statement.

## Conditional (ternary) operator Parameters:

**Condition**

An expression whose value is used as a condition.

**ExprIfTrue**

An expression which is evaluated if the condition evaluates to a truthy value (one which equals or can be converted to true).

**ExprIfFalse**

An expression which is executed if the condition is falsy (that is, has a value which can be converted to false).

### Description:

Besides false, possible falsy expressions are: null, NaN, 0, the empty string (""), and undefined. If condition is any of these, the result of the conditional expression will be the result of executing the expression exprIfFalse.

# Simple example:

var age = 26;

var beverage = (age >= 21) ? "Beer" : "Juice";

console.log(beverage); // "Beer"

## Things I want to know more about 