
what-i-learn-week-9
# Monday
To check the test parameter in codewar. Console.log(that parameter)

# Tuesday
## const fs = require ('fs') is built-in function in Node just like console.log()
const fs = require ('fs')
## readFileSync() is a function that takes in fs file, and text format of that file and return text.
const file = fs.readFileSync('./example.csv', 'utf-8')
## print a string in console.log
 make new line: \n
 ab: \t
## split() => convert a string to an array. Each element will be separated by element we put in () 

~~~ 
split(',') -> split at any ','
split(' ') -> split at any space
split('/n') -> split at any newline
~~~
# Wednesday
## Two dimensional Array: An array that contain other arrays
~~~
const arr =[['a'], ['b'], ['c']]
~~~
# Thursday
## Callback function: Function that is only called at a specific time or with a specific action
Type of call back functions
## Delay function: setTimeout(function, time) => let function happen after certain amount of time 
~~~
const print = function() {
    console.log('hello')
}

let delay = setTimeout(print,2000)
delay;
~~~
## Quit the delay function: clearTimeOut.
~~~
clearTimeout(delay)
~~~
## Interval function: make a function run all over again after a given time.
~~~
let run4ever = setInterval(print, 1000);
run4ever;
~~~
## clear interval function
~~~
clearInterval (run4ever)
~~~
