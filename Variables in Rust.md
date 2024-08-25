Variables in rust are declared using `let`&`cost`. Let's go over each of them.

#### let keyword

let is used to declare a variable. Variables declared by 'let' are by default
immutable meaning they are not changeable. Variables declared by let are
computed during runtime, remember that.

`let x =5;`.

Now you can make them mutable by using `mut` keyboard. Here's an example:

`let mut x = 5;`  and now it's value is changeable & we can do something like
` x=5`.

#### const keyword

const is used to declare a variable just as let. And it's also immutable & we
can't use `mut`  keyword to make it mutable. Like a constant value it stays
immutable. Also unlike `let` , `const`  can be used as a global variable
outside a function scope. And it's value is computed during compile time unlike
`let` variables whose value is computed in runtime.

Once you declare a const you cannot re-declare it, `const x=5`, `const x=6`
this is called shadowing and we'd learn more about it down below

#### shadowing

`let  x= " "`

`let x = x.len()`

What we did above was re-declare a variable and change it's type with it, this is
called shadowing. And this can only be done by using `let` keyword.

