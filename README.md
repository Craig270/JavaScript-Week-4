# Craig270-JavaScript-Week-4

exicution context
memory global variable envorment
call stack

Week 4

Week two questions:

1. what is the Window and Worker interfaces? Example:The setInterval() method, offered on the Window and Worker interfaces, repeatedly calls a function or executes a code snippet, with a fixed time delay between each call. It returns an interval ID which uniquely identifies the interval, so you can remove it later by calling clearInterval(). This method is defined by the WindowOrWorkerGlobalScope mixin.

2. Can a parameter be a writen function? Can you write the function right there in a parameter? as with setInterval()

3. Can you really use console.log as a parameter in a function call? Because I cant get it to work.

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

The product owner on your development team believes they've seen a pattern as to which customers purchase the most socks. To verify, you've been asked to write a function that processes an array of customer objects and return a new array that contains only customers that match any of the following criteria:

name starts with a 'C' (upper or lowercase)
address contains no undefined fields
the city is Peoria and the state is AZ
membership level is GOLD or PLATINUM unless the customer is younger than 29, then SILVER is okay too
the customer's age is evenly divisible by the number of characters in his/her name
The array of customer objects will have the following schema:

const customers = [
{
name: 'Sam',
address: {
street: '1234 W Bell Rd',
city: 'Phoenix',
zip: '85308',
state: 'AZ'
},
membershipLevel: 'GOLD',
age: 32
},
//more customers with the same schema
];

Dumb shit I came up with:

function questionTwo(array) {
let passed = [];
for (var i = 0; i < array.length; i++) {
if (
array[i].name[0] == "C" &&
array[i].address != " " &&
array[i].address.city == Peoria &&
array[i].address.state == "AZ" &&
array[i].age.length == array[i].name.length &&
(array[i].membershipLevel === "GOLD" ||
array[i].membershipLevel === "PLATINUM")
) {
passed += array[i];
}
}
}
