<h2>RxJS</h2>

<details>
<summary>RxJS</summary>

- Reactive Extensions for JavaScript
- A library for reactive programming
- Reactive Programming - 
- uses observales, subject, subscription 
- helps in async programming

</details>

<details>
<summary>Reactive Programming</summary>

- One change might trigger many other changes. 
- Changes are propogated
- Observable - subscribe flow
- An LOC might not run just once but will run depending on the fulfilment of some task/condition. (react to change)

</details>

<details>
<summary>Reactive Programming in Detail</summary>

- In computing, reactive programming is a declarative programming paradigm concerned with data streams and the propagation of change. With this paradigm, it's possible to express static (e.g., arrays) or dynamic (e.g., event emitters) data streams with ease, and also communicate that an inferred dependency within the associated execution model exists, which facilitates the automatic propagation of the changed data flow.[citation needed]

- For example, in an imperative programming setting, a := b + c would mean that a is being assigned the result of b + c in the instant the expression is evaluated, and later, the values of b and c can be changed with no effect on the value of a. On the other hand, in reactive programming, the value of a is automatically updated whenever the values of b or c change, without the program having to explicit re-execute the statement a := b + c to determine the presently assigned value of a.

var b = 1
var c = 2
var a = b + c
b = 10
console.log(a) // 3 (not 12 because "=" is not a reactive assignment operator)

// now imagine you have a special operator "$=" that changes the value of a variable (executes code on the right side of the operator and assigns result to left side variable) not only when explicitly initialized, but also when referenced variables (on the right side of the operator) are changed
var b = 1
var c = 2
var a $= b + c
b = 10
console.log(a) // 12

</details>