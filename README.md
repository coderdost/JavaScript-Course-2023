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
**Question 1:** Explain practical  use case of **break** and **continue** statement. When to use which **statement**?

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

**Question 3:** What are **default values** of function. And How we can use them?

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
**Question 5:** Explain use of **return** statement inside the function?

**Question 6:** What are **higher** order functions in JavaScript?

**Question 7:**  Create **higher** order function named as **transformer** which take **string** and **firstUpperCaseWord()** as  an arguments. And return **string** with first word in **upperCase** 

**Question 8:** Difference between **setTimeOut** and **setInterval** function. Also write **syntax** of both methods with specifying what are **required** and **optional** arguments in both function 

**Question 9:** Guess the **Output** And Explain Why?
```js
let arrowFunction = (name ="Coders") => {`Welcome ${name}`};

console.log(arrowFunction("Programmers"));
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

**Question 3:** Explain difference between **function** and **method** with the help of example?

**Question 4:** Guess the **Output** and explain Why?
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
**Question 5:** Explain **this** keyword with one real world example?

**Question 6:** Create a method **describeCar** inside *car* object in which you have to print like this in console using template literals

**Company of my car is __ . It color is __ And Model of my car is __**

**Question 7:** Generate random  numbers between 0 and 10 using **trunc** method of **MATH** object 

**Question 8:** Guess the **Output** and Explain Why?
```js
let arr = [1,2,3,4];
arr.forEach(elem =>{
	if(elem == 1){
	continue;
	}
	console.log(elem);
})
```
**Question 9:** Difference between **call** and **apply** method in term of implementation?

**Question 10:** Guess the **Output** And Explain Why?
```js
let arr = [1,2,3,4];
for(let elem in arr){
console.log(elem);
}
```


## Chapter 5 (DOM)

### Assignments

**Question 1:** Explain difference between **innerText** and **innerHTML** with the help of example?

 
 ## Chapter 6 (Form Events)
 
### Assignments

**Question 1:** Create regex for password with the following **validations**.

1) Length of password at least  of 8 characters 
2) contain at least one special character 
3) contain at least one alphabet (a-z) character

## Chapter 7(Array Methods)

### Assignments

**Question 1:** Difference between **slice** and **splice** method of array?

**Question 2:** You have given an array of **5** elements(1-5). Your task is defined as below.

1) You have to delete **2** elements starting from index  **2**.
2) You have to add **3** new elements on that position of Your choice.
3) Display the **2 deleted** elements in console.


**Question 3:** What happens if we use **negative** number inside **slice** method?
Example : arr.slice(-2); 

**Question 4:** Write **three** different methods/approaches to get **last** element of the array?

**Question 5:** One **key** difference between **map** and **filter** method of array?

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
**Question 9:** Explain working difference between **find** and **findIndex** method?

**Question 10:** Difference between **flat** and **flatMap** with details. Also Explain when to use which method?

**Question 11:** By default how **sort** method sort the array.

**Question 12:** Guess the **Output** and Explain Why?
```js
let arr = [1,2,3,4];
let result = arr.splice(1,2).pop();
console.log(result);
```  
**Question 13:** You have given an array of numbers **nums**. You have to check if all elements of the **array > 15** using **built-in** array method. 
```js
let nums = [16,17,18,28,22];
```

## Chapter 8 (Date and Time)

### Assignments

**Question 1:** How can we get current time in **millisecond**?

**Question 2:** Explain difference between **getDate()** and **getDay()** method of current Date?

 
 




 



