Quiz 1

Ans1= Javascript is a interpreted programming language which is mainly used for web development and allow users to make their website more dynamic and more feasible
It, is use in both front end and back end
It has easy syntax also allow users to connect their html file providing eventlisteners




ans2- let and var both are mutable keyword
When the variable are declared with the let keyword we cannot redeclared it and can change the value or reassigned whereas,
if the variables are declared with the var keyword we can also redeclared it and can change the value, their scope is global




ans3-if we declare the variable with the const keyword, they are in immutable, means cannot be changed ,they cannot be redeclared and they cannot be reassigned but,
if we declare the variable with the var keyboard they can be changed, they can be modified they can be redeclared ,
so to prevent the accidental modification we prefer cosnt over the var keyboard
const Have better optimization in the javascript whereas bar has less optimization




and4- Javascript is uses web browser to make the content very dynamic and flexible, as it uses the event handling the animations, the buttons with different tags
It uses DOM which represent interface or structure of HTML So by using it we can modify content we can change the content and make our html page is very interactive and dynamic




ans5 - Objects in javascript are the collection of heterogeneous data
which store data into the key value pair and every key should be unique same as we do in hashmaps




ans6 - Array is one of the user defined data type which stores the homogeneous data into it and we can access the data by indexing and in array the index is starts from zero but in object what data is heterogeneous in the key value pair of data and every key should be unique




ans7 -Functions at a block code or a piece of code which is used to perform a specific task by the user
function function name(parameters){
task
}




and8 - call by value == it do not check the datatype and only check the value
eg i == 'i' output = true
call by referaence === it check the datatype reference ang value
eg i === 'i' output = false




ans9 -Primitive data types are the types Which are already defined in the javascript and they're immutable means there can be change such as
number , string , Boolean , undefined , null




ans 10- document object model which represent the structure of HTML page
It is a tree like a structure will store node , element and tags in the tree like structure form
help us to connect our html page with the javascript so we can make our page very interactive and dynamic by modifying the content by changing the content and also adding the different types of eventhandlers and text




ans11 - The DOM allows JavaScript to interact with and modify the structure, content, and style of web pages dynamically. This enables to make dynamic and interactive web applications
to create, modify, and delete HTML elements and attributes, as well as update the text content of elements.





<!-- codes -->

ans1--
var arr=[1,2,3,4,5];
var sum =0
for(var i =0;i<arr.length;i++){
sum=sum+arr[i];
var length = arr.length;
}
console.log(sum/length);





ans2--
// by array
function func (arr){
var temp = arr[0];
arr[0]=arr[1];
arr[1]=temp;
console.log(arr);
}
var numbers=[5 , 6]
func(numbers);

// simple 2 numbers

function funcc(num1,num2){
var temp = num1;
num1=num2;
num2=temp;
console.log(num1,num2);
}
console.log(funcc(2,3));






ans3--
function fiboo(n) {
var a = 0;
var b = 1;
var c;
for (var i = 1; i <= n; i++) {
c = a + b;
a = b;
b = c;
console.log(a);
}
}
fiboo(5)





ans4--
function print(arry){
for(var i=0;i<arr.length;i++){
console.log(arry[i]);
}
}

var arr=[5,4,2,6,7,14,12,1];
for(var i=0;i<arr.length-1;i++){
for(var j=0;j<arr.length-1;j++){
if(arr[j]<arr[j+1]){
var temp =arr[j];
arr[j]=arr[j+1];
arr[j+1]=temp;
}
}

}
print(arr)

function print(arry){
for(var i=0;i<arr.length;i++){
console.log(arry[i]);
}
}



var arr=[5,4,2,6,7,14,12,1];
for(var i=0;i<arr.length-1;i++){
for(var j=0;j<arr.length-1;j++){
if(arr[j]>arr[j+1]){
var temp =arr[j];
arr[j]=arr[j+1];
arr[j+1]=temp;
}
}

}
print(arr)





ans 5--

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
  </head>
  <body>
    <div id="variableValue"></div>
  </body>
  <script 
var placeholder = document.getElementByID("variableValue");
placeholder.innerText = "hello Ujjwal"
</script>
</html>














quiz 2

Ans1 - Firstly functions at a block of code which is used to perform a specific task
we need function to make a code very dynamic
like if we have to perform the same task again and again so by writing the same code again and again we can simply make function that perform in the same task and we can call that function every time we need so this is why we make functions.\



ans2 - Function invocation meansfunction is invoked and that means when we execute the function or we call the function it means the function is invoked .

ans 3 -
Yes functions are treated as a object in the

<!-- defining -->

function func(name) {
return "Hello, " + name + "!";
}

 <!-- Add a property to the function -->

func.language = "English";

<!-- Add a method to the function  -->

func.sayHello = function(name1) {
return "Hello! + name1";
};

 <!-- Calling the function -->

console.log(func("John"));  
 Output: "Hello, John!"

<!-- calling the property -->

console.log(func.language);
Output: "English"

<!-- Call the method of the function  -->

console.log(func.sayHello("Ujjwal"));
Output: "Hello!"





ans4 - events in javascript means or are used to perform a specific task
example there are different types of event like onclick onmouseover onmouseleft onmousedown hover onsubmit
so when we do this these things the events perform the specific task



ans5-Strings in Java script are the data types which is used to store the letters alphabets or the collections of letters, basically they are text based




ans6- In JavaScript, an array is a special type of object used to store a collection of elements,Each element is assigned an index starting from 0  
 JavaScript arrays can contain elements of different data types,
JavaScript arrays are dynamic in nature, meaning they can change in size dynamically. Elements can be added to or removed from an array at any time




ans7 -A Map is a collection of key-value pairs where each key is unique within the Map
keys in a Map can be of any data type,

A Set is a collection of unique values where each value can occur only once. Sets do not have keys




ans8 - Array is one of the user defined data type which stores the homogeneous data into it and we can access the data by indexing and in array the index is starts from zero but in object what data is heterogeneous in the key value pair of data and every key should be unique

Maps in JavaScript are collections of key-value pairs where each key is unique within the Map, and each key maps to a corresponding value.
Keys in a Map can be of any data type



ans9- Array methods are built-in functions for for manipulating arrays and performing various operations on array
These methods allow you to add, remove, modify, iterate and search for elements
push()
pop()
shift()
unshift()
concat()
slice()
splice()  
find():



ans10- there are several ways to traverse or iterate over an array

for loop
for in loop
for of loop
for rach method
map method
while loop
do while lop






<!-- codes -->

ans1--
var arr= [1, 2, 3, 4, 5, 6]
var res = arr.reverse();
console.log(res);




ans2--
var arr1 = [1,2,3,4]
var arr2=[5,6,7,8]
var joined= arr1.concat(arr2)
console.log(joined);



ans3--

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
  </head>
  <body>
    <div id="variableValue"></div>
  </body>
  <script>

    var place = document.querySelector("#variableValue");

var arr1=[1,2,3,4,5]

arr1.forEach((value)=>{
place.innerHTML=arr1
})
</script>

</html>





ans4--
var set1 = new Set([1, 2, 3]);
var set2 = new Set([3, 4, 5]);

var mergedSet = new Set([...set1,...set2]);

console.log( mergedSet);

Quiz 3

ans1 - objects are complex data types that stores
the key value pair where each key is a unique identifier
we can call the Properties that are the keys of an object,
objects are made with curly braces {}
Objects in JavaScript are mutable, meaning their properties can be added, modified, or removed
after the object is created.
we can use prototype to inherit the object
__proto__

eg
let person = {
name: "ujjwal",
age: 21,
isStudent: false,
}
console.log(person.name);





ans2 -
function Vector(x, y) {
this.x = 0;
this.y = 0;
}

Vector.prototype.setX,setY = function(x,y) {
this.x = x;
this.y = y;
};

Vector.create = function(x, y) {
return new Vector(x, y);
};

let aa = Vector.create(3, 4);
console.log(aa.x,aa.y);



ans3 - As we all know that javascript is a programming language that is mainly attached to the web development for the front end and the back end development
but in present in the era of ai artificial intelligence , coming time the javascript will be used less and the all the work done or performed by the ai in future and we don't have to write the code from the scrap in the javascript



<!-- codes -->

ans1--

arr=[1,2,3,4,5]
arr.forEach((value)=>{
console.log(value);
})


var arr=[1,2,3,4,5];
arr.map((value)=>{
console.log(value\*2);
})



var arr=[1,2,3,4,5,18,20,50];
var filt =arr.filter((value)=>{
return value>=18
})
console.log(filt);



var arr=[1,2,3,4,5,18,20,50];
var filt =arr.reduce((val1,val2)=>{
return val1-val2
})
console.log(filt);



var arr=[1,2,3,4,5,18,20,50];
console.log(arr.includes(20));



var arr=[1,2,3,4,5,18,20,50];
var somee=arr.some((value,arrv)=>{
return value===10
})
console.log(somee);


 let arr = [56, 92, 18, 88, 12,11];
    function func() {
        let value = arr.every((value)=>{
            return value%2==0
        });
        console.log(value);
    }
    func();




ans3--

<!-- I learned from different sources (Google , Chatgpt , MDN) -->


class tmanager {
constructor() {
this.todo = [];
this.completed = [];
}

add(title) {
if (title == null) {
return -1;
}
const id =
this.todo.length > 0 ? this.todo[this.todo.length - 1].id + 1 : 1;
this.todo.push({ id, title });
return id;
}

remove(id) {
const index = this.todo.findIndex((task) => task.id === id);
if (index != -1) {
this.todo.splice(index, 1);
return true;
}
return false;
}

update(id, title) {
const task = this.todo.find((task) => task.id === id);
if (task) {
task.title === title;
return true;
}
return false;
}

markascompleted(id) {
const index = this.todo.findIndex((task) => task.id === id);
if (index != -1) {
const comtask = this.todo.splice(index, 1)[0];
this.completed.push(comtask);
return true;
}
return false;
}
}

const task = new tmanager();
console.log(task.add("ujjwal"));
console.log(task.add("drummer"));
console.log(task.todo);
console.log(task.remove(2));
console.log(task.markascompleted(1));
console.log(task.completed);
console.log(task.todo);



<!-- quiz 4 -->

ans1--
Anonymous functions in JavaScript are functions that are defined without a name. 
const add = function(x, y) {
    return x + y;
};



ans2--
strict comparison means ===
It check both the value and the type of the data while comparing
eg  i==='i' False
Abstract comparison means ==They only check the value and do not check the type of data while comparing
eg   i==='i' True



ans3--
Arrow functions consist of arrow "=>"
new keyboard cannot be used
used for small task

let add = ((a,b)=>{
  console.log(a+b;)
})

Regular functions consist of function keyword
new keyboard can be used
used for big task

function add(a,b){
  console.log(a+b)
}


ans4--

Hoisting in JavaScript is a method where variables and function declarations are moved to the top of their containing scope
hoisting Means calling the behave function or a variable before its declaretion



ans5--
yes, JavaScript is a garbage collected programming language
When an object is no longer needed, the garbage collector will automatically free the memory that it was using
we can also free up the memory by declaring it null

ans6--
   Shallow copying creates a new object with references to the same memory locations as the original object, while deep copying creates a new object with new memory locations
   That means in shallow copy the original array will affected and deep copy the original array will not affected even after modifying the content

ans7--
Object.freeze() is a method in JavaScript that freezes an object, making it immutable
It means one the object is freezed it cannot be modified


<!-- code -->




function getRandomNumber(min1, max1, min2, max2) {
    
    const randomNumber1 = Math.random() * (max1 - min1 + 1) + min1;
    const randomNumber2 =Math.random() * (max2 - min2 + 1) + min2;


    return Math.random() < 0.5 ? randomNumber1 : randomNumber2;
}


const randomNumber = getRandomNumber(-100, 0, 800, 900);
console.log(randomNumber);
