//Strings

let str1 = "hello , world!";
console.log(str1);  //hello , world!

// string indices
console.log(str1[10]);  //r

 //string length
console.log(str1.length);   //14

//Template Literals
let str2 = `this is a template literal`;
console.log(typeof str2);   //string

let object = {
    item : "ball",
    price : 10,
};
console.log(`the cost of ${object.item} is ${object.price} rupees`); //the cost of ball is 10 rupees

//Escape character
console.log("hello\nworld!") /*hello
                               world!*/

console.log("hello\tworld!") //  hello	world!

//String methods in js
let str3 = "helLo , woRld!";

//toUpperCase()
console.log(str3.toUpperCase());   //HELLO , WORLD!

//toLowerCase()
console.log(str3.toLowerCase());   //hello , world!

//trim()
let str4 = "   hello , world!    ";
console.log(str4.trim());     //hello , world!

//slice()
let str5 = "0123456";
console.log(str5.slice(2 , 5));  //234

//concat()
let str6 = "654";
let str7 = "9";
console.log(str7.concat(str6));  //9654

//replace()
let str8 = "hello";
console.log(str8.replace("lo" , "p"));  //help

//chatAt()
let str9 = "hello";
console.log(str9.charAt(1)); //e




