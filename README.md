# Craig270-JavaScript-Week-4

exicution context
memory global variable envorment
call stack

Week 4

Week two questions:

1. what is the Window and Worker interfaces? Example:The setInterval() method, offered on the Window and Worker interfaces, repeatedly calls a function or executes a code snippet, with a fixed time delay between each call. It returns an interval ID which uniquely identifies the interval, so you can remove it later by calling clearInterval(). This method is defined by the WindowOrWorkerGlobalScope mixin.

2. Can a parameter be a writen function? Can you write the function right there in a parameter? as with setInterval()

Week two W.I.L. :

Notes:

    Video 1 :
        diffirence between let, const, and var

    Video 2:
        Template Literals, using ` ` with ${} to combined your code in a string. Or add new lines without the need to use /n using `` with this you can just press enter for a new line

    Video 3:
        Aarow Functions
    let createFullName = (firstName, lastName) => `${firstName} ${lastName}`

    let someFunction = (a,b) => {
        let result = " ";
        for (let i=0; i <= b; i++) {
            result = a;
        }
        return result;
    }
    console.log(createFullName('Tom', 'Sawyer'))  //Tom Sawyer
