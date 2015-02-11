##Descriptions of Iterators

###Instructions
Below you will find a list of methods. In the space provided below each, please provide a brief description of what this method does based upon your review of the Docs. 

###Array methods:
May be helpful to look in [Enumerable](http://ruby-doc.org/core-2.2.0/Enumerable.html) as well...

####select:
Returns a new array of every element in the array that returns true within the block.

####reject:
Returns a new array of every element in the array that returns false within the block.

####map:
Invokes the the given block once for each element in the array. Then returns the new element into a new array.
####detect:
Returns whatever number matches both "arguments" in an array that is within the block.

####inject:
Executes the block for 2 parameters from an array. In order from left to right. Commonly shown with addition.

####partition:
Returns two arrays, the first that return true from the block and the second array containing everything else, all within an array.

####sort:
Sorts through an array based off of what is returned in the block. If a -1 is returned in the block, the array will be descending, if 1, array will be ascending.

####one:
Loops through everything in the array. If one condition returns true, than it the block returns true. If more than one condition returns true, the block returns false.

####none:
Block will return true if nothing in the array matches the conditions in the block. Will return false if a condition in the block matches an element in the array.

####all:
Will return true if all of the elements in the array are true to the condition inside of the block.

####empty?:
Will return true if the array is empty. Will return false otherwise. 

####eql?:
Will return true if both of the arrays are exactly the same or equal.

####include?:
Will return true if the array includes the parameter. Will return false if the parameter is not included in the array.

####nil?:
Will return true if the object is nil. False otherwise.

###Hash methods:

####key?:
Will return true if the hash has the keys that are included in the conditions of the block.

####keys:
Will return an array of the keys included in the given hash.

####delete:
Will return the value of the key that is deleted from the hash.

####delete_if:
Will return the remaining key, value pairings based off of the conditions of the block that is passed.
