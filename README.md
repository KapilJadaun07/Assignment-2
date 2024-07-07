# Assignment-2
Question 1.how to integrate css file in html file?
Options: a) using <javascript> tag
b) using <link> tag
c) using <js> tag
d) using <file> tag
Ans-B
Question 2. How do you make a new paragraph in HTML?
Options: a) using div tag
b) using p tag
c) using span tag
d) using form tag
Ans-B
Question 3. Div tag is a inline-block element?
Options: a) true
b) false
Ans-b
Question 4. Span is an inline-block element?
Options: a) true
b) false
Ans-a
Question 5. What is the output of following code?(1 mark)
function ValueOfC(){
Var y = 10;
Var c = y ** y
console.log(c);
Return c;
}
ValueOfC() // —-->
Options: a) 100
b) 10
c) 10000000000
Ans-c
Q6. Consider this array :
const people = [
{ id: 1, name: 'John', age: 30 },
{ id: 2, name: 'Jane', age: 25 },
{ id: 3, name: 'Bob', age: 40 },
]; (apply all operations on this array)
only use map and filter functions to get the output array.
A) Output array : ['John', 'Jane', 'Bob']
B) Output array :
[{ "id":1,"name":"John","age":30,"salary":50000},
{"id": 2,"name": "Jane","age": 25,"salary": 50000},
{"id": 3,"name": "Bob","age": 40,"salary": 50000}]
C)Create an array of objects for people who are above 30
years old, and you only need their names and ages (no
id property ). You can use map in combination with filter
Output array : [
{"name": "Bob","age": 40}
]
Ans-

Q7: write a function main and pass two functions as
parameter to it cb1 and cb2. main(cb1, cb2, x, y)
Define cb1 in such a way that will add two numbers
Define cb2 in such a way that will give you the
difference of two numbers.
X and y are two numbers ex- x=11, y =4.
Ans-function cb1(a, b) {
    return a + b;
}

function cb2(a, b) {
    return a - b;
}

function main(cb1, cb2, x, y) {
    const sumResult = cb1(x, y);
    const diffResult = cb2(x, y);
    
    console.log(`Sum of ${x} and ${y} is: ${sumResult}`);
    console.log(`Difference of ${x} and ${y} is: ${diffResult}`);
}


const x = 11;
const y = 4;
main(cb1, cb2, x, y);

Q8 : given an array
var users = [
{firstName : "Susan", lastName: "Steward"},
{firstName : "Daniel", lastName: "Longbottom"},
{firstName : "Jacob", lastName: "Black"}
];
outputarray = ["Susan Steward", "Daniel Longbottom", "Jacob Black"]
to get the output array from users array which array method
will give you correct result?
A)Some function
B)filter function
c)map function
d)every function
Ans-c

Q10: what will be the value of arr?
var arr = [1,2,3,4,5].filter(func)
function func(v){
return false;
}
A)[0,0,0,0, 0]
B)[false, false, false, false, flase]
C)[]
D)0
ans-c

Q11: what is the key difference between these two
properties?Choose appropriate option.
Display : none and visibility:hidden
A)visibility : hidden removes the element from the
dom while display: none just hides the element.
B)display : none removes the element from the dom
while visibility : hidden just hides the element.
C)display : none apply property to element opacity
: 0,while visibility : hidden just remove that
element from dom.
D)display : none works same as visibility hidden
Ans-b

Q12: what will be the output of following code?
var a = 1;
var b = 0;
while (a <= 3)
{
a++;
b += a * 2;
console.log(b);
}
A)4 10 18
B)4 6 8
C)1 3 5
D)none of the above
Ans : A

Q13: at the end of both operations what will be the value of arr? (2 marks)
Var arr= [1,2,3,4]
arr.unshift(100)
arr.shift()
A) [1,2,3,4]
B) [1,2,3,100]
C)[100,2,3,4]
D)[2,3,4,100]
Ans-a
