## 1. Write short notes on string methods with code examples

## toLowerCase() -

To convert a string to lowercase, we can use the toLowerCase() method in JavaScript. let myString = "HeLLo WoRLD!"; let lowerCaseString = myString. toLowerCase(); console. log(lowerCaseString); // output: "hello world!".

```js

let name="NANDHU"
console.log(name.toLowerCase())

```

## toUpperCase() -

JavaScript String toUpperCase() method converts the entire string to Upper case. This method does not affect any of the special characters, digits, and the alphabets that are already in the upper case. 

```js

let name="nandhu"
console.log(name.toUpperCase())

```


## substring() -

The substring() method extracts characters, between two indices (positions), from a string, and returns the substring. The substring() method extracts characters from start to end (exclusive). The substring() method does not change the original string.

```js

let comment="NandhuRamesh"
console.log(comment.substring(1,5))

```

## replace() -

The replace() method of String values returns a new string with one, some, or all matches of a pattern replaced by a replacement . The pattern can be a string or a RegExp , and the replacement can be a string or a function called for each match. If pattern is a string, only the first occurrence will be replaced.

```js

let string="My name is Nandhu"
let newString=string.replace("Nandhu","yadhu")
console.log(newString)

```



## trim() -

The trim() method removes whitespace from both sides of a string. The trim() method does not change the original string.

```js

let string="     JavaScript     "
console.log(string.trim())

```


## split() -

In JavaScript, the split method allows you to split the string into an array of substrings based on a given pattern. The split() function takes one or two optional parameters, the first one being the separator, and the second the maximum number of elements to be included in the resulting array.

```js


let name="Nandhu"
console.log(name.split())

let name1="Nandhu"
console.log(name1.split(""))


```


## slice() -

JavaScript String slice() Method. The slice() method in JavaScript is used to extract a portion of a string and create a new string without modifying the original string.

```js


let name="Nandhu"
console.log(name.slice(1,3))

```



## 2. create a simple app that takes the user’s name and greets him/her after capitalizing the first letter of the user’s name and changing the rest of the letters into lowercase (toUpperCase(), toLowerCase(), slice(), length property, string concatenation)


Ans : 

```js

let user=prompt("Enter your name")
let firstLetter = user.slice(0,1).toUpperCase()
let restOfTheLetter = user.slice(1,user.length).toLowerCase()
alert(`Hi ${firstLetter}${restOfTheLetter}`)

```
