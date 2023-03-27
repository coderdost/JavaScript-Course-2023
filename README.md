# JavaScript Full Course 2023

## Chapter 1 (Introduction)

### Assignments
**Question  1:** Difference Between "null" and "undefined" data type with example?
**Question 2:** What type of variable should you **initialize** at the time of declaration?
**Question 3:** Guess the **Output** and Explain Why?
```js
let languages = "java javaScript python cSharp";
let result = languages.lastIndexOf("S");
	console.log(result)
```
**Question 4:** Guess the **Output** and Explain Why?

```js
let variable = "hello programmers";
let result = Number(variable);
	console.log(result);
```
**Question 5:** Guess the **Output** and Explain Why?
```js
let num1 = 32;
let num2 = "32";
let result1 = num1 !== num2;
let result2 = num1 != num2;
	console.log(result1,result2);
```

**Question 6:** Guess the **Output** and explain Why?
```js
let str =  "Hello Programmers";
let result = str.includes("r");
console.log(result);
```
**Question 7:** Guess the **Output** and Explain Why?

```js
let num1 = 2;
let num2 = 5;
let result = num1**num2*2;
	console.log(result);
```
**Question 8:** Guess the **Output** and Explain Why?
```js
let num1 = [1,2,4,5];
let num2 = [6,5,8,0];
let result = num1.concat(num2);
	console.log(result)
```
**Question 9:** Guess the **Output** and Explain Why?
```js
let a = 5;
let b = 7;
let c = 8;
let result = a<b>c;
	console.log(result)
```
**Question 10:**  If your state split into **four** equal parts such that in each part there are **1/4**  number of people live. You have to find How many people would live in each part?

## Chapter 2 (Conditional and iteration statement)

### Assignments:
**Question 1:** Guess the **Output** And Explain Why?

```js
let  i  =  4;
for(let  j  =  0;i<10;i++){
	if(j  ===  1  ||  i  ===  6){
	continue;
}
else{
	console.log(i,j);
	if(i  ===  7){
	break;
}}}
```

**Question 2:** Guess the **Output** and Explain Why?
```js
let  i  =  0;
for(i;i<5;i++){
	console.log(i);
}
```
**Question 3:**  Write a simple **Program** in which You have to print first **10** number in **descending** order?

**Question 4:** Lets say **John** is looking a new **country** to live in.
He want to live in a country that speaks **English**, has less than 10 million people. One of the **food** option between these two must present **Spanish food** *Or* **English food**.

**Write** an if statement to help john figure out Your country is right for him?

 
**Question 5:**  Guess the **Output** And Explain Why?
```js
	for(let i = 0;i<10;i++){
	console.log(i);
}
	console.log(i)
```
**Question 6:** use **nested-if** statement to check your **age>18**
than check your height **height > 5.10**.     
If **both** true show any message(**I can sit in __ exam**)  in the console?

**Question 7:** Create two variables **grade** and **passingYear**.Check if your **grade == "A"** and **passingYear < 2020** with the help of **ternary** operator(Not allowed to use any logical operator).If both condition *true* print on console **Qualify**. Otherwise **Fail** 
   
## Chapter 3 (Function)

### Assignments

**Question 1:** Create a **function Declaration**  called **describeYourState** Which take three parameters  'Population', 'traditional food' and  'historical place'. Based on this input function should return a string with this format. 
**My state population is __. Its traditional food is __ and historical place name is __**

**Question 2:** Create a **function expression** which  does the exact same thing as defined in **Question 1**

**Question 3:** Create  function **addition** which takes two numbers as an argument. And return the result of  **sum of two numbers**

**Important Note** In the function call you are **not** allowed to pass any **parameter**.

```js 
Example
function addition(num1,num2){
return num1 + num2;
}
	console.log(addition()); //You are not allowed to modify this line any more
```

**Question 4:** Identify which **type** of value passed below into the function **greet()**

```js
let  person  = {
name:"john",
age:25
}
function  greet(person){
person.name  =  `Mr ${person.name}`
	console.log(`Welcome ${person.name}`)
}
greet(person)
```

**Question 5:**  Create **higher** order function named as **transformer** which take **string** and **firstUpperCaseWord()** as  an arguments. And return **string** with first word in **upperCase** 

**Question 6:**  create function which will display Your name after every 5 seconds 
```js
input
let yourName = "john";

output
"john" after 5 second
"john" after 5 second
"john" after 5 second
"john" after 5 second
.
.
.
and so on.
```

**Question 7:** Guess the **Output** And Explain Why?
```js
let arrowFunction = (name ="Coders") => {`Welcome ${name}`};

	console.log(arrowFunction("Programmers"));
```

**Question 8:** Create a JavaScript **Function** to find the area of a triangle where lengths of the three of its sides are 5, 6, 7

```js 
input : area_of_triangle(5,6,7)
output : 14.69
```
**Question 9:** Create a JavaScript **Function** to capitalize the first letter of each word of a given string.
```js

input : capitalize("we are the champions") 
output : "We Are The Champions"


```

## Chapter 4 (Objects)

### Assignments

**Question 1:** Guess the **Output** And Explain Why?
```js
console.log(Math.round(Math.random() * 10 ));
```
**Question 2:** Create an object called 'Country' for a country of your choice, containing properties 'country', 'capital', 'language', 'population' and 'neighbours'

1) Increase the country population by two million using **dot** notation.
2) Decrease the country population by one million using **bracket** notation.

**Question 3:** Guess the **Output** and explain Why?
```js
let car = {
color:"Blue",
model:2021,
company:"Toyota"
}
let carColor = "Blue";
	console.log(car[carColor]);
	console.log(car.carColor);
```
**Question 4:** Create a method **describeCar** inside *car* object in which you have to print like this in console using template literals

**Company of my car is __ . It color is __ And Model of my car is __**

**Question 5:** Generate random  numbers between 0 and 10 using **trunc** method of **MATH** object 

```js
Example
getRandomNumbers(){

}
Ouput value 0-10
```

**Question 6:** Guess the **Output** and Explain Why?
```js
let arr = [1,2,3,4];
arr.forEach(elem =>{
	if(elem == 1){
	continue;
	}
	console.log(elem);
})
```
**Question 7:** Guess the **Output** And explain Why?
 
**Important Note** if there is any error How we can solve that **error**? 

```js
let  airplane  = {
flightName:"fly india",
atacode:"FI",
ratings:4.9,
book(passenger,flightNum){
console.log(`${passenger} Booked flight in ${this.flightName} with flight Number ${this.atacode}${flightNum}`);
}
}
let  bookMethod  =  airplane.book;
bookMethod("john",8754);
```


**Question 8:** Guess the **Output** And Explain Why?
```js
let arr = [1,2,3,4];
for(let elem in arr){
	console.log(elem);
}
```

**Question 9:** You have to create a  **Shopping_Cart**  array with following features :

-   **addItem(itemName)**  : this function should add string itemName to cart
    
-   **removeItem(itemName)**: this function should remove any item which matches itemName.  _Hint : search for index of itemName and then remove it_
    
-   **cartSize()**  : returns size of cart in terms of number of cart Items.


## Chapter 5 (DOM)

### Assignments

**Question 1:** Explain difference between **innerText** and **innerHTML** in the following example?

**HTML**
```html
<div  id="content">
<h2> 		Hello Coders</h2>
</div>
```
**JavaScript**
```js
let  content  =  document.getElementById("content")
	console.log(content.innerHTML)
	console.log(content.innerText)
```

 
 ## Chapter 6 (Form Events)
 
### Assignments

**Question 1:** Create regex for password with the following **validations**.

1) Length of password at least  of 8 characters 
2) contain at least one special character 
3) contain at least one alphabet (a-z) character

**HTML**
```html
<form  action=""  class="testForm">
<input  type="password"  name=""  class="inputPass"  placeholder="Enter Password"  >
<input  type="submit"  value="Check Password">
</form>
```

**JavaScript**
```js
let  form  =  document.querySelector('.testForm')
let  inputPassword  =  document.querySelector('.inputPass');
let  requiredPasswordPattern  =  "create your regex here";
form.addEventListener('submit' , (e)=>{
e.preventDefault();
let  password  =  inputPassword.value;
let  result  =  requiredPasswordPattern.test(password);
if(result  ==  true){
	console.log("Your password validated successfully")
}else{
	console.log("try again with new password")
}
})
```

## Chapter 7(Array Methods)

### Assignments

**Question 1:**  You have given array of **strings**. Your task is to obtain last **two**  elements of given array using **slice** method?

```js
Input
let admins = ["john","paul","Neha","harry"];
Ouput
["Neha","harry"];
```

**Question 2:** You have given an array of **5** elements(1-5). Your task is defined as below.

1) You have to delete **2** elements starting from index  **2**.
2) You have to add **3** new elements on that position of Your choice.
3) Display the **2 deleted** elements in console.


**Question 3:** What happens if we use **negative** number inside **slice** method?
Example : arr.slice(-2); 

**Question 4:** Write **three** different methods/approaches to get **last** element of the array?

**Question 5:**  You have given an array of **nums**. Create new Array with the help of **nums** array. In new Array each element  will be a result of  **multiplication by 2**  of the original array element

```js
Example:
Input
let nums = [1,2,3,4,5];
output
updatedNums = [2,4,6,8,10]
```

**Question 6** You have given an array of **scores** in which score of each student stored. Create a new array with the help of original **scores** array in which only those scores exist  **greater** than 75%

```js
let totalScore = 150;
let scores = [55,76,35,77,88,97,120,136,140];
```
**Question 7:** You have given an array of numbers **nums**. You have to find **sum** of all array elements using **reduce** method?

```js
let nums = [2,3,5,7,8,4,9];
```
**Question 8:** You have given an array of numbers **nums**. You have to find the index of value **8** using **built-in** method of array?
```js
let nums = [2,3,5,6,8,6,4,8];
```
**Question 9:** You have given an array of **objects** of users  as below. Find the specified **user** with **name property** = "John".
Also find the **position** (index+1)   of that **user** inside the array?
```js
let  users  = [
{
name:"Paul",
age:24,
verified:true
},
{
name:"John",
age:21,
verified:false
},
{
name:"Neha",
age:19,
verify:true
},
]
```
**Question 10:** Guess the **Output** and explain Why?
```js
let  nums  = [1,2,4,5,[6,[8]],[9,0]];
let  res1  =  nums.flat(1);
let  res2  =  nums.flatMap(elem  =>  elem);
console.log(res1,res2);
```

**Question 11:** You have given an array of **nums**. Write a program to sort the elements of array in **descending** order **using built-in** method of array.
```js
Input
let nums = [5,1,4,6,8,3,9];
Output
[9,8,6,5,4,3,1]
```

**Question 12:** Guess the **Output** and Explain Why?
```js
let arr = [1,2,3,4];
let result = arr.splice(1,2).pop();
console.log(result);
```  
**Question 13:** You have `given an array of numbers **nums**. You have to check if all elements of the **array > 15** using **built-in** array method. 
```js
let nums = [16,17,18,28,22];
```

### More Practice Questions (Arrays)

**Question 1:**  Guess the **Output** And explain Why?

```js
let  strArray  = [1,2,3,4,5];
let  result  =  strArray.reverse();
console.log(result  ==  strArray);
```
**Question 2:**  You have **given** two **arrays** below as an example. Your task is to **combine** them into one By using array method
```js
input  
let arr1 = [1,2,3,4,5];
let arr2 = [6,7,8,9,10];
ouput
[6,7,8,9,10,1,2,3,4,5]
```
**Question 3:** You have given an array of **letters** below. Convert that array into string of letters **Without Space**

```js
input 
let  arr  = ['a','b','h','i','s','h','e','k'];
output
'abhishek'
```

**Question 4:**   Guess the **Output** and explain why?
```js
let  arr  = [11,62,1,27,8,5];  
let  sorted  =  arr.sort();
console.log(sorted)
```

**Question 5:**  Create a function 'calcAverageHumanAge', which accepts an arrays of dog's ages ('ages'), and does the following thing in order:
 1. Calculate the dog age in human years using the following formula: if the dog is <= 2 years old, humanAge = 2 * dogAge. If the dog is > 2 years old, humanAge = 16 + dogAge 
```js
Test data

let arr = [12,2,5,12,8,13,9];
```

**Question 6:** Guess the **Output** and Explain Why?

```js
let  arr  = [1,2,3,4,5,6,7,8]
let  elem  =  arr.at(-1);
console.log(elem);
```

**Question 7:**  Guess the **Output** and Explain why?
```js
let  arr  = [1,2,3,4,5,6,7,8]
let  result  =  arr.slice(2,5).splice(0,2,21).pop();
console.log(result,arr)
```




## Chapter 8 (Date and Time)

### Assignments

**Question 1:** How can we get current time in **millisecond**?

**Question 2:** Guess the **Output** and Explain Why?
```js
let currentDate = new Date();
let result1 = currentDate.getDay();
let result2 = currentDate.getDate();
	console.log(result1,result2)
```

 ## Chapter 9 (Local Storage)
### Assignments

**Question 1:** Create two variables **myHobby** , **age** . Now **set** their value  in local storage(according to your hobby and age). 

After setting also **get** value from local storage and display their values in **console**.


## Chapter 10 (OOP)

### Assignments

**Question 1:** Your tasks: 
1. Use a constructor function to implement a 'Bike'. A bike has a 'make' and a 'speed' property. The 'speed' property is the current speed of the bike in km/h 
2. Implement an 'accelerate' method that will increase the bike's speed by **50**, and log the new speed to the console 
3. Implement a 'brake' method that will decrease the bike's speed by **25**, and log the new speed to the console 
4. Create **2**  'Bike' objects and experiment with calling **'accelerate'** and **'brake'** multiple times on each of them 

 **Sample Data**
   
Data car 1: 'bike1' going at 120 km/h 
Data car 2: 'bike2' going at 95 km/h
 
**Question 2:** Re-create **Question 1**  But this time using **ES6**
class.

**Question 3:**  Guess the **Output** And Explain Why?
```js
function Person(name){
	this.name = name;
}
let me = new Person("John");

	console.log(me.__proto__ == Person.prototype);
	console.log(me.__proto__.__proto__ == Object.prototype);

```

**Question 4:** Create  **constructor** function inside **Car** class with three properties  **color** , **model** , **company**
```js
class Car {
	
}
```
**Question 5:**  **Identify** all **mistakes** in the following class

```js
class Car = {
	constructor(){
	
	},
	engineMethod = function(){
	console.log("This is engine method of Car class");
}
}
```
**Question 6:**  Guess the **Output** and explain Why? And **if** there is any **error** How we can remove that error?

```js
function  Person(name,age){

	this.name  =  name;
	this.age  =  age;
	this.brainMethod  =  function(){
	console.log("This is brain method of Person")
}
}
	Person.heartMethod  =  function(){
	console.log("This is heart method of Person");
}
let  me  =  new  Person("john",34);

	me.brainMethod();
	me.heartMethod();
```

**Question 7:**  Create a new class **Animal** (which will be child class) inherited from **Person** class. In Addition  in **Animal** class Add some additional properties like **breedType** and  **animalFamily**.(catFamily, dogFamily)

**Question 8:**  Guess the **Output** And Explain Why?

```js
class  Car {
	constructor(){
}
}
let  car  =  new  Car();
	console.log(Car.prototype.isPrototypeOf(Car));
	console.log(Car.prototype.isPrototypeOf(car));
```
## Chapter 11( Async & Await )

### Assignments

**Question 1:** Guess the **Output** And Explain Why?
**Html Code**


```html
<!DOCTYPE  html>
<html  lang="en">
<head>
<meta  charset="UTF-8">
<meta  http-equiv="X-UA-Compatible"  content="IE=edge">
<meta  name="viewport"  content="width=device-width, initial-scale=1.0">
<title>JavaScript-CoderDost</title>
<style>
</head>
<body>
<div  id="content">

	<h2 id = "heading" ></h2>

</div>
<script  defer  src = "./script.js"></script>
</script>
</body>
</html>
```
**JS Code**

```js
async  function greeting() {  
let myPromise = new Promise(function(resolve) {  
setTimeout(function() {resolve("I love Programming !!");}, 2000);  
});  
document.getElementById("heading").innerHTML = await myPromise;  
}  
greeting();
```

**Question 2:** Find the **Logical Error** in below code. And How can we solve them with **callback** function approach?

```js

const movies = [
        { title: `Movie 1`},
        { title: `Movie 2` }
    ]

function getMovies(){
    setTimeout(() => {
        movies.forEach((movie, index) => {
            console.log(movie.title)
        })
    }, 1000);
}

function createMovies(movie){
    setTimeout(() => {
        movies.push(movie)
    }, 2000);
}

getMovies();


createMovies({ title: `Movie 3`} )
```

**Question 3:** What are the **three** possible State of any promise?

**Question 4:** Solve **Question 2** again But this time with the help of **promise**  

**Question 5:** Now re-factor **Question 2** with the help of **async-await** keyword?

**Question 6:** Status code starting with **300** represent which type of message/error?
 

## Chapter 12 (Modern Operators)

### Assignments 

**Question 1:**  Guess the **Output** and Explain Why?

```js
let arr = [3,4,5,7,98,0];
let [a,b,,c] = arr;
	console.log(a,b,c);
```

**Question 2:** Guess the **Output** And Explain Why?
```js
let arr = [1,3,[2,55],[9,8,7]];
let [a,,[b,c],d] = arr;
console.log(a,b,c,d);
````

**Question  3:**  Guess the **Output** and explain Why?
```js
let obj = {
name:"John",
age:25,
weight:70
}

let {name:objName,age} = obj;
	console.log(name,age);
```

**Question 4:** You have given an array of **nums**.Create **shallow** copy of that array  and store them in another **variable**

```js
let nums = [5,7,4,9,2,8];

let newNums = "store Shallow copy of nums inside newNums variable")
```
**Question 5:**  You have given an array as below . Create a function which accept elements as an argument and return last **4** element of the array 

```js
Example:
let nums = [1,2,3,4,5,6,7,8];
input data: 1,2,3,4,5,6,7,8
output data: 5,6,7,8
```
**Question 6:** Guess the **Output** And Explain Why?

```js
let nums = 0;
let result = nums ?? 50;
console.log(result);
```
**Question 7:** You have given an object as below. You have to check  wheather **physics** is the subject of that student or not, if true find the **score** of **physics** subject using **optional chaining**

```js
let  student = {
Math:{
score:75,
},
physics:{
score:85,
}
}
```

**Question 8:**  Guess the **Output** And Explain Why?
```js
let nums = [2,3,4,5,6];
for(let key of nums) {
	console.log(key)
}
```

### More Practice Questions

**Question 1:** Guess the **Output** and  Explain Why?
```js
let  arr  = [1,2,3,4,5];
let  arr1  = [...arr];
arr1[2] =  10; 
console.log(arr,arr1)
```
**Question 2:** You have given a list of variable names written in underscore. You have to write a program to convert them into camel casing format

```js
					List of variable names
					
Input
user_name
last_name
date_of_birth
user_password

Output
userName
lastName
dateOfBirth
userPassword
```
**Question 3:** Guess the **Output** and Explain why?

```js
function  fun(a,b,...c){
console.log(`${a}  ${b}`);
console.log(c);
console.log(c[0]);
console.log(c.length);
console.log(c.indexOf('google'));
}
fun('apple','sumsung','amazon','google','facebook')
```
**Question 4:**  Guess the **Output** and Explain Why?
```js
const fruits = { apple: 8, orange: 7, pear: 5 };
const entries = Object.entries(fruits);
for (const [fruit, count] of entries) {
  console.log(`There are ${count} ${fruit}s`);
}
```

**Question 5:** Write a program in which you have to set **Default** value  in case of false input value using **Logical Assignment** Operator?

**Question 6:** Guess the **Output** and Explain Why?
```js
let  arr  =  new  Set([1,2,3,1,2,1,3,4,6,7,5]);
let  length  =  arr.size;
console.log(arr,length);
```

**Question 7:** You have given **Set** below. Your task is to convert that **Set** into an **array**?

```js
input
let set = new Set[1,2,3,2,1,3,4,12,2];
output
let arr = "Do something here to convert....";
```

**Question 8:**  Guess the **Output** and Explain Why?
**Note** :  **Change** values of variable to examine the result.
```js
let  number  =  40;
let  age  =  18;
let  result  =  number  >  50  ?  age  >  19  ?  'pass':'ageIssue'  :  "numberIssue" ;
console.log(result);
```

 
## Chapter 13 (Modern Tooling)
 
### Assignments

**Question 1:** You have given scenario. You are in **script.js** And in same directory there is another file **products.js**. In **products.js** there are two methods called **createProduct** and **deleteProduct**

write an **import** and **export** statement properly in order to import these two methods from **products.js** file into the **script.js**


**Question 2**  Now **export** only one method **createProduct** using **default** export statement?

**Question 3:** In **importing** statement how can we **customize**/**change** the name of **function** we are importing?

```js
Example Actuall function name = 'Addition'
We want to import as 'Add'
How can can we do this?
```
