
##indexOf(i)
indexOf(searchElement, fromIndex)
Given an item, i, this method returns either the position, if the item is found, or -1, if the item is not found. Optional: can also note the start index in the second argument.

###Examples:
var testArray = ["Hello", "Sun", "World", "Sun", "Mars"]
console.log(testArray.indexOf("World"))  // returns 1
console.log(testArray.indexOf("Earth"))  // returns -1
console.log(testArray.indexOf("Sun", 2)) // returns 3

##Case (string)
.toUpperCase() - returns the calling string value converted to uppercase
.toLowerCase() - returns the calling string value converted to lowercase

###Examples:
console.log("hello".toUpperCase()); // returns "HELLO"
console.log("BYE".toLowerCase()); // returns "bye"
