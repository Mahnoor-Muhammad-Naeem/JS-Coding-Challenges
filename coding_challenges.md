# JavaScript Practice Problems

This repository contains solutions to basic JavaScript problems.  
Each problem includes a **question**, **solution code**, and the **expected output**.

---

## 1. Print Squares

**Question:**  
Write a program to output the squares (using multiplication) of numbers from 1 to 5 on separate lines.

**Code:**
```javascript
for (let i = 1; i <= 5; i++) {
    console.log(`${i} - ${i * i}`);
}
```

**Output:**  
/ 1 - 1  
/ 2 - 4  
/ 3 - 9  
/ 4 - 16  
/ 5 - 25  

---

## 2. Print all the arithmetic operations

**Question:**  
Write a JavaScript program that calculates and prints the results of arithmetic operations such as addition, subtraction, division, and multiplication between the numbers 8 and 4.

**Code:**
```javascript
let a = 8;
let b = 4;

console.log(a + b);  // Addition
console.log(a - b);  // Subtraction
console.log(a / b);  // Division
console.log(a * b);  // Multiplication
```

**Output:**  
/ 12  
/ 4  
/ 2  
/ 32  

---

## 3. Divide two variables

**Question:**  
- Create two variables of integer type and assign the value 30 to `a` and 10 to `b`.  
- Print the result of `a / b`.

**Code:**
```javascript
let a = 30;
let b = 10;

console.log(a / b);
```

**Output:**  
/ 3  

---

## 4. Convert Temperature

**Question:**  
Declare a variable `"temperature"` and initialise it with a value of 25.5 (in Celsius) and print it in Celsius and Kelvin (add 273 to temperature in Celsius).

**Code:**
```javascript
let temperature = 25.5;

console.log("Celsius - " + temperature);
console.log("Kelvin - " + (temperature + 273));
```

**Output:**  
/ Celsius - 25.5  
/ Kelvin - 298.5  

---

## 5. Print total minutes and seconds

**Question:**  
Declare a variable `hour` and initialize it with the value 5. Then, calculate and print the total number of minutes and seconds present in this hour.

**Code:**
```javascript
let hour = 5;

let minutes = hour * 60;
let seconds = hour * 60 * 60;

console.log(minutes);
console.log(seconds);
```

**Output:**  
/ 300  
/ 18000  

---

## 6. Convert speed

**Question:**  
Create a variable named `speed1` and assign it the value 36, representing speed in kilometers per hour. Then, convert and display this speed in meters per second.  
(Note: 1 km/h = 5/18 m/s)

**Code:**
```javascript
let speed1 = 36;

let speedInMetersPerSecond = speed1 * (5 / 18);

console.log(speedInMetersPerSecond);
```

**Output:**  
/ 10  

---

## 7. Area & Perimeter of Rectangle

**Question:**  
Let’s consider a rectangle of sides 11 and 13. Output the following on separate lines:  
- Area of the rectangle having sides as 11 and 13  
- Perimeter of the rectangle having sides as 11 and 13  

Formula:  
- Area = length * breadth  
- Perimeter = 2 * (length + breadth)

**Code:**
```javascript
let length = 11;
let breadth = 13;

let area = length * breadth;
let perimeter = 2 * (length + breadth);

console.log(area);
console.log(perimeter);
```

**Output:**  
/ 143  
/ 48  

---

## 8. Area of Rectangle

**Question:**  
Find out and display the area of a rectangle of sides 45 and 76 respectively.  
Declare variables `length`, `width`, and `area` and assign the relevant values to them.  
Output the value of variable `area`.  

**Code:**
```javascript
let length = 45;
let width = 76;

let area = length * width;

console.log(area);
```

**Output:**  
/ 3420  

---

## 9. Area of Circle (Float datatype)

**Question:**  
Find the area of a circle whose radius is 8.9. Take `pi = 3.14`.  
Declare variables `radius`, `pi`, and `area` and assign the relevant values to them.  
Output the variable `area`.  

Formula: `area = pi * radius * radius`

**Code:**
```javascript
let radius = 8.9;
let pi = 3.14;

let area = pi * radius * radius;

console.log(area);
```

**Output:**  
/ 248.71940000000004  

---

## 10. String Datatype

**Question:**  
- Declare two variables `a` and `b`.  
- Assign `"Learning "` to `a` and `"is fun!"` to `b`.  
- Display the sentence `"Learning is fun!"` using variables `a` and `b` in a single line.  

**Code:**
```javascript
let a = "Learning ";
let b = "is fun!";

console.log(a + b);
```

**Output:**  
/ Learning is fun!  

---
