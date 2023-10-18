# Lecture 4
>>>>![](./%D0%91%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20(2).png)
# Table of content.
>>>>>>># 1.String
>>>>>>># 2.Number
# What is Methods in Js ?
>>>>>![](./%D0%91%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.png)
>## Methodho in funksiahoi taiore meboshad ki mo onhoro istifoda mebarem va onho kori moro oson mekunand A method is a block of code which only runs when it is called.You can pass data, known as parameters, into a method.Methods are used to perform certain actions, and they arealso known as functions.

# What is String in Js?
>## String dar Js in iak namud typeOf ast va ba guruhi primitive dokhil meshavad va hamchunin methodhoi sting niz hast
# Creating String in Js?
>## 1."Doube Quotes"
```
"hello"
```
>## 2."single Qoutes"
```
'hello
```
>## 3."Backticks"
```
`Hello ${hi}`
```
>>>>>![](./images%20(1).jpg)
# Methods in Js?
>## 1.charAt() : - The charAt() method returns the character at a specified index (position) in a string.
```
/// js
let str = "Hello"
console.log(str.charAt(1))

/// output : ---> o
```
>## 2. at() : - This method allows for positive and negative integers. Negative integers count back from the last string character.
```
/// js
let str = "Hello"
console.log(str.at(-1))

/// output : ---> o
```
>## 3. concat() : - The concat() method joins two or more strings, does not change the existing strings.
```
/// js
let str = "Hello"
let str2 = "Bilol
console.log(str.concat(" ",str2)))

/// output : ---> Hello Bilol
```
>## 4.replace() : - The replace() method searches a string for a value or a regular expression.
```
/// js
let str = "Hello Ahmad"
let str2 = "Bilol"
console.log(str.raplace("Ahmad",str2)))

/// output : ---> Hello Bilol
```
>## 5.replaceAll() : - The replaceAll() method returns a new string with all matches of a pattern replaced by a replacement.
```
// js
let str = "Hello Ahmad and Ahmad and Ahmad"
let str2 = "Bilol"
console.log(str.raplace("Ahmad",str2)))

/// output : ---> Hello Bilol and Bilol and Bilol
```
>## 6.split() : - The split() method splits a string into an array of substrings. stringro megirad aray mekunad
```
// js
let str = "Hello Ahmad"
console.log(str.split()))
console.log(str.split("")))
console.log(str.split(" ")))

/// output : --->
[ "Hello Ahmad" ]
[ "H","e","l","l","o"," ","A","h","m","a","d",]
["Hello","Ahmad"]
```
>## 7.substring() : - The substring() method extracts characters, between two indices (positions), from a string, and returns the substring
```
/// js
let str = "Hello Bilol"
console.log(str.substring(1,-1))

// output : --> ello Bilo
```
>## 7.slice() : - slice misli substring kor mekunad ammo minusa kabul mekunad
```
/// js
let str = "Hello Bilol"
console.log(str.slice(-5))

// output : --> Bilol
```
>## toLowerCase() : - harfhor ba khurd tabdil medihad
```
/// js
let str = "hello
console.log(str.toLowerCase())
// output  : -- > HELLO 
```
>## toUpperCase() : - harfhor ba kalon tabdil medihad
```
/// js
let str = "HELLO"
console.log(str.toUpperCase())
// output  : -- > hello 
```
>## trim() : - mathode hast ki az du taraf probelhoi ziodatira megirad
```
/// js
let str = "    hello    "
console.log(str.totrim())
// output  : -- > hello 
```
>## includes() : - mesangad ki hast io nest
```
/// js
let str = "hello Bilol"
console.log(str.includes("Bilol"))
console.log(str.includes("Ahmad"))
// output  : -- > 
 true
 false 
```
>## toString() : - Raqamro ba string tabdil meihad
```
/// js
let str = 25
let res = str.toString()
console.log(typeOf(res))
// output  : -- > string 
```
>## indexOf() : - elementa indexsha nishon meta
```
/// js
let str = "hello
console.log(str.indexOf("l"))
// output  : -- > 2
```
>## repeat() : - takror nishon medihad
```
/// js
let str = "hello
console.log(str.repeat(3," "))
// output  : -- > hello hello hello 
```
>>>>>![](./%D0%91%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.jpg)
>## Math.round() : - Az nim nigoh mekunad
```
/// js
let num1 = 6.6
let num2 = 6.3
console.log(Math.round(num1))
console.log(Math.round(num2))

/// output : --> 
7
6
```
>## Math.ceil() : - baland mekunad
```
/// js
let num1 = 6.6
let num2 = 6.3
console.log(Math.ceil(num1))
console.log(Math.ceil(num2))

/// output : --> 
7
7
```
>## Math.floor() : - past mekunad
```
/// js
let num1 = 6.6
let num2 = 6.3
console.log(Math.floor(num1))
console.log(Math.floor(num2))

/// output : --> 
6
6
```
>## Math.max() : - kalontarin raqamro meiobad
```
/// js
let num1 = (1,2,3,4,5,6)
console.log(Math.max(num1))

/// output : --> 
6
```
>## Math.min() : - khurdtarinro raqamro meiobad
```
/// js
let num1 = (1,2,3,4,5,6)
console.log(Math.min(num1))

/// output : --> 
1
```
>## Math.pow() : - ba daraja mebardorad
```
/// js
let num1 = 2
console.log(Math.pow(num1,5))

/// output : --> 
32
```
>## Math.sqrt() : - resharo neiobad
```
/// js
let num1 = 64
console.log(Math.sqrt(num1))

/// output : --> 
8
```
>## Math.abc() : - minusaro ba pilusa tabdil medihhad ammo pilusaro ba minusa tabdil namedihad
```
/// js
let num1 = -12
console.log(Math.abc(num1))

/// output : --> 
12
```
>## Math.random() : - kalontarin raqamro meiobad
```
/// js
let num1 = 10
console.log(Math.floor(Math.random(num1)*10))

/// output : --> 
6 , 10 , 4 , 7
```
>## isNaN() : - mesanjad ki raqam hast io ne
```
/// js
let num1 = 2+"2a"
let num2 = 10
console.log(isNaN(num1))
console.log(isNaN(num2))

/// output : --> 
true
false
```