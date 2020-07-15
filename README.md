
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
