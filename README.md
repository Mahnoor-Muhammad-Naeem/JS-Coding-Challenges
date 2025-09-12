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
