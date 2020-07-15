
what-i-learn-week-9
#Tuesday
## const fs = require ('fs') is built-in function in Node just like console.log()
const fs = require ('fs')
## readFileSync() is a function that takes in fs file, and text format of that file and return text.
const file = fs.readFileSync('./example.csv', 'utf-8')
