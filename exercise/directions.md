

# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```
 for(var i=0; i<=10; i++){
    console.log(i)
}
```

<br>

## Print every number from 10 to 0

```
for(var i =10; i>=0 ; i--){
    console.log(i)
}
```

<br>

## Print every number from 4 to -16

```
for(var i = 4; i>=-16; i--){
    console.log(i)
}

```

<br>

## Print every fifth number from 8 to 41

```
for(var i = 8; i<=41; i = i+5){
    console.log(i)
}
```

<br>

# Exercises: JavaScript loops with array:

Paste your answers into this file.



1. Change all **odd** numbers to be those numbers multiplied by two:
```js
const numbers = [4, 9, 7, 2, 1, 8];

  const numbers =[4, 9, 7, 2, 1, 8];
const numLength = numbers.length -1;
for(var i=0; i<=numLength;i++){
    if(numbers[i]%2===1){
        numbers[i]= numbers[i] * 2;
    }
}

numbers; // => [4, 18, 14, 2, 2, 8]
```

2.  Create an array to hold your favorite colors.  For each choice, log to the screen a string like: `My #1 choice is blue.`

const favoriteColors =['blue', 'green', 'orange']'
const colorsLength = favoriteColors.length - 1;
for(var i= 0; i <=colorsLength; i++){
  console.log('My #'+i+'choice is ' +favoriteColors[i]);
}

3.  Create an array of ages.  Loop through and log only the ages that are over 21.

const age = [19, 20, 22, 24, 26, 30];
const ageLength = age.length -1;
for(var i = 0; i<=ageLength; i++){
    if(age[i]>21){
      console.log(age[i]);
    }
}

1. Create an array to hold your top five choices of something (music, books, movies, whatever).

const topMovies =['Joker', 'fast and furios', 'movie3', 'movie4', 'movie5'];
const moviesLength = topMovies.length - 1;
for(var i= 0; i <=moviesLength; i++){
  console.log('My #'+i+'choice is ' +topMovies[i]);
}
    - For each choice, log to the screen a string like: "My #1 choice is blue."
    - **Bonus:** Change it to log "My 1st choice, "My 2nd choice", "My 3rd choice", picking the right suffix for the number based on what it is.


## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


```
####################################

for (let num = 0; num <=100; num++){
  for(let j = num; j>= 0 ; j-- ){

  for(let i=1; i <=  num; i++){
      if(i * j=== num){
        if(i==3){
          console.log("Fizz")
        }
        else if(i==5){
          console.log("Buzz")
        }
        else if(i==3 && i==5){
          console.log("Fizzbuzz")

        }
    }
  }
}
}

```
############################
for (let num = 0; num <=100; num++){
  if(num % 3 ===0 && num % 5 ===0){
    console.log("Fizzbuzz")
  }
  else if(num % 3 === 0){
    console.log("Fizz")
  }
  else if(num % 5 ===){
    console.log("Buzz")
  }
}
################### ANOTHER solution
for (let num = 0; num <=100; num++){
  if(num % 3 ===0 && num % 5 ===0){
    console.log("Fizzbuzz");
  }
  else if(num % 3 === 0){
    console.log("Fizz");
  }
    else if(num % 5 === 0){
    console.log("Buzz");
  }
}

<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```
for(let num = 0; num <=20; num++){
  if(num%2===0){
    console.log(num +' is even')
  }
  if(num%2===1){
    console.log(num +' is odd')
  }
}
```

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
ANSWER HERE
```
for(var i=0; i<=10; i++){
    result=i*9;
    console.log(i +'*'+9+'='+result);
}

<br>

## The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

```
for(var i=60; i<=100; i++){
   if(i >= 80 && i <=89){
     console.log(i + 'B');
   }
   else if(i >= 90 && i <=94){
     console.log(i + 'A');
   }
   else if(i >= 95 && i <=100){
     console.log(i + 'A+');
   }
   
   }

```
