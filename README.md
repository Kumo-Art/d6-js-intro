...c#
for(int i = 1; i < 6; i++)
{
   Console.WriteLine(i);
}
...



# JavaScript

## What is JavaScript
- HTML is structure. CSS is styles. JavaScript is behavior (functionality).
- It runs in the browser, after the page is loaded.
- It is not Java. that is a different language.


## Connecting JavaScript to a page
- JS goes in it's own file, like script.js
- The page needs <script></script> at BOTTOM of body.




## Variables
- No type keyword. const or let, then name.
- const = the value does not get reassigned. let = it does.


## Errors
- An error stops the file. Lines below never run.





## Functions
- function name(parameter) { } No access modifier, no return type, no parameter types.
- Nothing checks what a function returns, or whether it returns at all.




## Objects
- { name: value, name: value }  Curly braces, name, colon, value, comma.
- Like a C# Object, except no class was ever written.



## The DOM
- DOM = Document Object Model
- index.html is the instructions. The DOM is what the browser BUILT from those instructions.
- Every element is an Object.



## getElementById and textContent
- document is the whole page as an object.
- document.getElementById("some-id) gets one Element, by it's Id attribute.
- .textContent read the text inside. Assigning to it changes the text on the page.



## classList
- element.classList.add("closed") puts a class on element.
- element.classList.remove("closed") takes it off.


## createElement and appendChild
- document.createElement("li") makes an element. It is not on the page yet.
- parent.appendChild(child) puts it on the page, as the last child.