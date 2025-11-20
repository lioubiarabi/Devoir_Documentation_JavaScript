# Fonctions

## Déclarations de fonction vs expressions de fonction

delarations functions are hoisted so we can call them before assigning them in the code, to create them we use `function` keyword and the name of the function after it then we open the block scope with `{}`

experssions functions are not hoisted, we stock them in a varibale so we have to call them after assigning them

for example:

```
const name = function() {
  // code here
}
```
## Fonctions fléchées

same as experssions functions it's not hoisted, it's simple to write, it's solve big problem in js because it heritat This from the block parent

for example:
```
() => {
  // code here
}
```
