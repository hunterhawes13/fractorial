## Synopsis

####JavaScript Challenge
Using the JavaScript language, have the function FirstFactorial(num) take the num parameter being passed and return the factorial of it (e.g. if num = 4,
return (4 * 3 * 2 * 1)). For the test cases, the range will be between 1 and 18. 
1. Create a variable n to store 1 so we can loop from 1 to the index N multiplying each number by the previous one until we reach our number. 

2. loop will work by multiply each number between 1 and num 

n = 1 * 1 = 1

n = 1 * 2 = 2

n = 2 * 3 = 6

n = 6 * 4 = 24


## Code Example

```
function FirstFactorial(num) { 
var n = 1;
for (i=1; i<=num; i++) {
    n = n * i;
}
  return n; 
         
}

   

FirstFactorial();    
```

## Motivation

JavaScript Fitness

## Contributors

Hunter Hawes
github: hunterhawes13
twitter: @tikishackfun

## License

This project is licensed under the terms of the MIT license.

## Warning

This should not be used in production. It is for demonstration purposes only.
