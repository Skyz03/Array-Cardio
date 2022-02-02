# JS--Array-Cardio1
The Array Cardio challenge for different methods available in the array
This project is the fourth challange in JS-30 challenge where I learned about ARRAY ```.filter()```, ```.map()```, ```.reduce()```  ```.sort()``` thing.


## Demo

This one works in the console. So, there isn't a demo for online version.

## Features

- All the power of the Arrays to .reduce(), .sort(), .map(), .filter()

## Lessons Learned

Here, I leared about the power of the Array where different array functions are used.


```
const fifteen = inventors.filter(function (inventor) {
  if (inventor.year >= 1500 && inventor.year <= 1599) {
 return true;
 }

const fullName = inventors.map(inventor => {
   console.log((inventor.first) + " " + (inventor.last))
 })

const ordered = inventors.sort(function (a, b) {
  if (a.year > b.year) {
    return 1;
  } else {
    return -1;
  }
});

const lived = inventors.reduce((total, inventor) => {
  return total + (inventor.passed - inventor.year)
}, 0);

const oldest = inventors.sort(function (a, b) {
  const lastGuy = a.passed - a.year;
  const nextGuy = b.passed - b.year;
  return lastGuy > nextGuy ? -1 : 1;

});
console.table(oldest);

const alpha = people.sort((lastOne, nextOne) => {
  const [aLast, aFirst] = lastOne.split(', ');
  const [bLast, bFirst] = nextOne.split(', ');
  return aLast > bLast ? 1 : -1;
});
console.log(alpha);

```

These, are the examples used to implement in the array with these functions.

1000 milliseconds = 1 second.

## Optimizations

Can Implement different functions to find more about these arrays. 

## Screenshots

![image](https://user-images.githubusercontent.com/42742924/152195724-a2eb91f1-a028-4f88-b0c0-f98e39029ad6.png)

## Tech Stack

**Client:** HTML & JS

## Documentation

Lots of MDN documentation to understand about these parameters.
