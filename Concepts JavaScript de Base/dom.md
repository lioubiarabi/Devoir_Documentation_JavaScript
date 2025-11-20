# Instructions Conditionnelles

## if/else, switch, opérateur ternaire

we can use them to decide which code block we want to execute depend on a condition if it's true or false

### if/else
it will execute the first block if one or more conditions are true, if not it will execute the code block in else

```
if(condition){
  // true
} else {
  // false
}
```

### switch
it execute the code block based on checking each key if it match the value, it's better method of using a seies of if/else

```
switch (expression) {
  case value1:
    // execute if expression === value1
    break;xecuted if expression === value2
    break;
  // ... more cases
  default:
    // execute if no case matches the expression
    break;
}
```

### ternary operator

it's a simple why of using conditions in js, it check the condition if true or false, if true it execute the first experssion and return a value, if false it will execute the second experssion and also return a value;

```
condition ? experssion1 : experssion2;
```
