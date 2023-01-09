# Setup

### Make sure these tools are installed
- npm
- nvm
- node (v16)
- vscode
- python (v3)

# Data Types
All data is JS has a type even though we don't see it.

### Most common data types:
- number
- string
- boolean
- undefined
- array (technically this is an object)
- object

The `typeof` keyword can be used to lookup the type data.

# Functions

## Different ways of creating functions
- `function myFunc() {}`
- `const myFunc = function() {}`
- `() => {}`

# Scope

- Scope determines where variables can be references from
- Scope is determined when the variable is *declared*
- Stuff in global scope can be accessed anywhere
- Stuff in function scope can only be accessed in the function
- Stuff in block scope (curly braces) can only be accessed in the block

_Gotcha_: Declaring a variable without `const` or `let` will be globally scoped

## Scope Chain
- The closest scope is checked first. If the var isn't found there, JS moves up the scope chain one by one. Error is thrown if it doesn't exist in any scope.

