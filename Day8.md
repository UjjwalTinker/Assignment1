<!-- assignment 1 -->

ans1--
There are different data types in typescript such as
number
string
Boolean
any
void
never
null
undefined
array
tuple

ans2--
Generic data type and typescript allow you to enter the different data type
<T>
When we don't know the data type of an array ,object ,we can use generic

function identity<T>(namee: T): T {
return namee;
}
console.log(identity<number>(42));
console.log(identity<string>("Hello"));

ans3--
Type inference just type script ability to assign the data type to the variable function expression
if we made a function that returns a number so typescript return the number, if you return any other data typer it will show the error

ans4--
1 simple function with parameters and their data type
2 interfaces
3 generic function

ans5--

class gen<T>[
constructor(name:T){
this.name=name;
}
getname():T{
console.log(this.name)
return this.name
}
]

var gg = new gen(T);
gg.getname<string>("drummer");

<!-- code -->

interface Todo {
name: string;
description: string;
done: boolean;
}

function add(name:string, description:string):number {
let newtodo:todo{
name: name,
description: description,
done: false
}
return todo.push(newTodo);
}

function remove(index:number):number{
return todo splice(index,1)
}

function list():void{
todos.forEach(function(todo, index) {
console.log(index + " - " + todo.name);
});
}

function update(index:number,name:string,description:string):number{
todos[index].name = name;
todos[index].description = description;
return todos[index]
}
