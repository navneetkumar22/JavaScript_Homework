# **JavaScript Homework**

## Q2. Declare variables to store your first name, last name, marital status, country and age and display them using interploation method.
```js
let firstName = "Navneet";
let lastName = "Panwar";
let maritalStatus = "Single";
let myCountry = "India";
let myAge = 32;
console.log(`My name is ${firstName} ${lastName} and I'm a ${myAge} year old ${maritalStatus} man, currently living in ${myCountry}.`);
```

## Q3. Decalre a varibale and assign value to it and change all the string characters to capital letters using toUpperCase() method.
```js
let name = "navneet kumar";
console.log(name.toUpperCase());
```

## Q4.Check if the string contains a word Script using includes() method.
```js
let text = "Hello world, I'm learning Java Script";
let result = text.includes("Script");
console.log(result);
```

## 5. Split the string into an array using split() method
```js
let text = `Hello world, I am learning Java Script`;
let myArray = text.split(" ");
let words = myArray[5] + myArray[6];
console.log(words);
```


## Q6. 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon' split the string at the comma and change it to an array.
```js
let mnC = `Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon`;
let myCountry = mnC.split(" ");
console.log(myCountry);
```

## 7. Use lastIndexOf to determine the position of the last occurrence of a script.
```js
let text = `Hello world, I am learning Java Script`;
let word = text.lastIndexOf("world");
console.log(word);
```

## 8. Use search to find the position of the first occurrence of the word because in the following sentence:'You cannot end a sentence with because because because is a conjunction'.
```js
let text = `You cannot end a sentence with because because because is a conjunction`;
let word = text.search("because");
console.log(word);
```

## 9. Use trim() to remove any trailing whitespace at the beginning and the end of a string.
```js
let textt = "  Navneet Panwar!  ";
let word = textt.trimEnd().trimStart();
console.log(word);
```

## 10. Boolean value is either true or false.
    - Write three JavaScript statement which provide truthy value.
    - Write three JavaScript statement which provide falsy value.

## 11. Figure out the result of the following comparison expression first without using console.log(). After you decide the result confirm it using console.log()
    console.log(4 > 3);
    console.log(4 >= 3);
    console.log(4 < 3
    console.log(4 <= 3
    console.log(4 == 4
    console.log(4 === 4);
    console.log(4 != 4
    console.log(4 !== 4
    console.log(4 != '4'
    console.log(4 == '4');
    console.log(4 == '4');
    console.log(Find the length of python and jargon and make a falsy comparison statement.

## 12. Use the Date object to do the following activities
    - What is the year today?
    - What is the month today as a number?
    - What is the date today?
    - What is the day today as a number?
    - What is the hours now?
    - What is the minutes now?
    - Find out the numbers of seconds elapsed from January 1, 1970 to now.

```js
let now = new Date();
console.log(now.getFullYear());
console.log(now.getMonth()+1);
console.log(now.getDate());
let bDay = new Date(1990, 04, 14);
let timeWent = now - bDay;
console.log(now);
```

## 13. Write a script that prompt the user to enter base and height of the triangle and calculate an area of a triangle (area = 0.5 x b x h).
```js
let b = prompt("Enter the base of the triangle:");
let h = prompt("Enter the height:");
let areaTriangle = 0.5 * b * h;
console.log(areaTriangle);
alert(`Area of the triangle is : ${areaTriangle}`);
```

## 14. Slope is m = (y2-y1)/(x2-x1). Find the slope between point (2, 2) and point(6,10)
```js
let x1= 2;
let y1=2;
let x2=6;
let y2=10;
let m = (y2-y1)/(x2-x1);
console.log(`The slope between given points is : ${m}`);
```

## 15. Calculate the slope, x-intercept and y-intercept of y = 2x -2

## 16. Get radius using prompt and calculate the area of a circle (area = pi x r x r) and circumference of a circle(c = 2 x pi x r) where pi = 3.14.
```js
let r = prompt("Enter radius of the circle:");
alert(`Area of the circle is : ${3.14 * r * r}`);
alert(`Circumference of the circle is: ${2 * 3.14 * r}`);
```

## 17. Create a human readable time format using the Date time object
    - YYYY-MM-DD HH:mm
    - DD-MM-YYYY HH:mm
    - DD/MM/YYYY HH:mm

## 18. Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback:'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18.
```js
let age = prompt("Enter your age:");
if (age >= 18) {
    alert("You are old enough to drive!");
}
else {
    alert(`You should wait for atleast ${18 - age} years to drive!`);
}
```

## 19. Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?
```js
let a = prompt("Enter the number");

if (a %= 2) {
    alert("Given number is even!");
}
else{
    alert("Given number is a odd number!");
}
```

## 20. Write a code which can give grades to students according to theirs scores:
    - 80-100, A
    - 70-89, B
    - 60-69, C
    - 50-59, D
    - 0-49, F

## 21. Check if the season is Autumn, Winter, Spring or Summer. If the user input is :
    - September, October or November, the season is Autumn.
    - December, January or February, the season is Winter.
    - March, April or May, the season is Spring
    - June, July or August, the season is Summer

```js
let givenMonth = prompt("Please enter name of the month");
// let mth = givenMonth.toString();
if (givenMonth = "September" || "October" || "November"){
    alert("The season is Automn");
}else if (givenMonth = "December" || "January" || "February"){
    alert("The season is winter");
}
```

## 22. Write a program which tells the number of days in a month.

## 23. Write a program which tells the number of days in a month, now consider leap year.

## 24. Create a separate countries.js file and store the countries array in to this file, create a separate file web_techs.js and store the webTechs array in to this file. Access both file in main.js file

## 25. In the following shopping cart add, remove, edit items
    => const shoppingCart = ['Milk', 'Coffee', 'Tea', 'Honey']
    - add 'Meat' in the beginning of your shopping cart if it has not been already added
    - add Sugar at the end of you shopping cart if it has not been already added
    - remove 'Honey' if you are allergic to honey
    - modify Tea to 'Green Tea'

```js
let shoppingCart = ['Milk', 'Coffee', 'Tea', 'Honey'];
let newItem = "Meat";

shoppingCart.indexOf(newItem) === -1 ? shoppingCart.unshift(newItem) : console.log("This item already exist.");
console.log(shoppingCart);
console.log(shoppingCart);

const index = shoppingCart.indexOf("Green TEa");
if (index > -1){
    shoppingCart.splice(index, 1);
}
else{
    console.log("Given item doesnt exist.")
}

console.log(shoppingCart);

function removeItemAll(arr, value) {
    var i = 0;
    while (i < arr.length) {
      if (arr[i] === value) {
        arr.splice(i, 1);
      } else {
        ++i;
      }
    }
    return arr;
  }
  // Usage
  let myArray = [2,5,5,1,5,8,5];
  console.log(myArray);
  console.log(removeItemAll(myArray, 5))
```


## 26. In countries array check if 'Ethiopia' exists in the array if it exists print 'ETHIOPIA'. If it does not exist add to the countries list.
```js
let myCountry = ["India", "Ethiopia", "China", "Spain", "Russia"];
myCountry.includes("Ethiopia") ? console.log("ETHIOPIA") : myCountry.push("Ethiopia");
console.log(myCountry);
```

## 27. The following is an array of 10 students ages:
    => const ages = [19, 22, 19, 24, 20, 25, 26, 24, 25, 24]
    - Sort the array and find the min and max age
    - Find the median age(one middle item or two middle items divided by two)
    - Find the average age(all items divided by number of items)
    - Find the range of the ages(max minus min)
    - Compare the value of (min - average) and (max - average), use abs() method

```js
const ages = [19, 22, 19, 24, 20, 25, 26, 24, 25, 24];
ages.sort();
console.log(ages);
console.log(`Min item of the array is : ${Math.min(...ages)}`);
console.log(`Max item of the array is : ${Math.max(...ages)}`);

let sum = 0;
for (let i = 0; i < ages.length; i++) {
    sum += parseInt(ages[i]);
}
console.log(`The sum of all ages is ${sum} and average is ${sum / ages.length}`);
```

## 28. Use for loop to iterate from 0 to 100 and print only prime numbers
```js
for (let i = 0; i <= 100; i++) {
    if ((i % 2 == 0) || (i % 3 == 0) || (i % 5 == 0) || (i % 7 == 0)) {
        continue;
    }
    console.log(i);
}
```

## 29. Use for loop to iterate from 0 to 100 and print the sum of all evens and the sum of all odds.
```js
let sum = 0;
for (let i = 0; i <= 100; i++) {
    if (i % 2 == 0) {
        continue;
    }
    sum += i;
    // return sum;
}
console.log(`The sum of odd numbers is : ${sum}`);
```

## 30. Write a script which generates a random hexadecimal number.

## 31. Sort the webTechs array and mernStack array
// countries Array : https://gist.github.com/incredimike/1469814

## 32. Array Questions
    - Extract all the countries contain the word 'land' from the countries array and print it as array
    - Find the country containing the hightest number of characters in the countries array
    - Extract all the countries contain the word 'land' from the countries array and print it as array
    - Extract all the countries containing only four characters from the countries array and print it as array
    - Extract all the countries containing two or more words from the countries array and print it as array
    - Reverse the countries array and capitalize each country and stored it as an array

## 33. Body mass index(BMI) is calculated as follows: bmi = weight in Kg / (height x height) in m2. Write a function which calculates bmi. BMI is used to broadly define different weight groups in adults 20 years old or older.Check if a person is underweight, normal, overweight or obese based the information given below.
    - The same groups apply to both men and women.
    - Underweight: BMI is less than 18.5
    - Normal weight: BMI is 18.5 to 24.9
    - Overweight: BMI is 25 to 29.9
    - Obese: BMI is 30 or more

## 34. Linear equation is calculated as follows: ax + by + c = 0. Write a function which calculates value of a linear equation, solveLinEquation.

## 35. Write a functions which checks if all items are unique in the array.
