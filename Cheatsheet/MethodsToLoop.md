# Methods to loop in JavaScript 

## FOR
>  Loops through a block of code a number of times.

```javascript
const numbers = [10,20,30,40]
for (let i = 0; i<numbers.length; i++){
  console.log(numbers[i]);
}
// Result: 10 20 30 40
```

<br>

## FOR OF
>  Loops through the values of an iterable object without a specifying the last limit.

```javascript
const numbers = [10,20,30,40]
for (const i of numbers){
  console.log(numbers[i]);
}

// Result: 10 20 30 40
```
<br>

## FOR IN
>  Loops through the properties of an object 

```javascript
const numbers = {
  1: 10,
  2: 20,
  3: 40
}
for (const i in numbers){
  console.log(numbers[i]);
}

// Result: 10 20 30 40
```
<br>

## FOR EACH
>  Iterates over an array without making any changes or returning any values. 

```javascript
const numbers = [10,20,30,40]

numbers.forEach(num => {
  console.log(num);
})

// Result: 10 20 30 40
```
<br>

## WHILE
>  Loops through a block of a code while a specified condition is true

```javascript
const numbers = [10,20,30,40]
let i =0;
while (i<numbers.length){
  console.log(numbers[i]);
  i++;
}

// Result: 10 20 30 40
```

<br>

## DO WHILE
>  The code is executed one time before checking the condition and  end until a block o code while  is true.

```javascript
const numbers = [10,20,30,40]
let i =0;
do{
    console.log(numbers[i]*1);
    i++;
}while (i<numbers.length)

// Result: 10 20 30 40
```
<br>

## MAP 
>  Iterate over an array and store the result in a new variable 

```javascript
const numbers = [10,20,30,40]

const result = numbers.map ( num => {
    return num;
})

// Result: 10 20 30 40
```