# Array practice

Identify the time complexity of each of these functions with a 1 sentence
justification for your answer. Assume `arr` is an array of length _n_.

## `arr.push()`

Time complexity: O(1)
Space complexity: O(1)
Justification: One variable is pushed onto the end of an array so both time and space are linnearly effected

[push on MDN][push]


## `arr.pop()`

Time complexity: O(1)
Space complexity: O(1)
Justification: One variable is poped so constant space and time is needed to remove one thing

[pop on MDN][pop]

## `arr.shift()`

Time complexity: O(n)
Space complexity: O(1)
Justification: we are moving each object in the arry over so this will take linnear time. Likewise we are removing ONLY one element so this is linnear space complexity

[shift on MDN][shift]

## `arr.unshift()`

Time complexity: O(n)
Space complexity: O(1)
Justification: For the same reasons as shift we are moving all the elements of the array over so this takes linnear time. Also we are only changin the memmmory of one variable so once more this is linnear

[unshift on MDN][unshift]

## `arr.splice()`

Time complexity: O(n)
Space complexity: O(n)
Justification: We are doing an opperation chanign the positions of all the elements in the array so this is linnear time constraints. Also we are making a shallow copy of the array so this must be linnear complexity as well

[splice on MDN][splice]

## `arr.slice()`

Time complexity: O(n)
Space complexity: O(n)
Justification: Just like splice you are putting all your element in a new array this as a result takes linnear time. Also you are making a copy of the array and putting it into a new memmory slot so this means you are copying a linnear amout of memmory hence linnear space cokplexity

[slice on MDN][slice]

## `arr.indexOf()`

Time complexity: O(n)
Space complexity: O(1))
Justification: You will potentially need to search the entire array to find the lement you wish so this will take in  the worst case linnear time. However you are not using any memmory other than the value of the item you are searching for hence contant memmory contraints

[indexOf on MDN][indexOf]

## `arr.map()`

Time complexity: O(n)
Space complexity: O(n)
Justification: You will peruse over each element in your array ONLY once so this must be linnear time contraints. Also you will be potentially adding a new value into a NEW array for each elemnt in your original array you are searching for hence likewise linnear time complexity.

[map on MDN][map]

## `arr.filter()`

Time complexity: O(n)
Space complexity: O(n)
Justification: The reasons for this are exactly the same as the reasons for arr.map

[filter on MDN][filter]

## `arr.reduce()`

Time complexity: O(n)
Space complexity: O(1)
Justification: So again you will peruse each item in your initial array ONLY once so this must be linnear time complexity. However you only input and keep trak of ONE variable the entire time hence this will be contant space complexity

[reduce on MDN][reduce]

## `arr.reverse()`

Time complexity: O(n)
Space complexity: O(1)
Justification: You will peruse throug each element in your array only once so linnear time contraints there. You will be relocating and NOT creating new memmory quantites for the items you are re-arraning so this takes no additional memmory or constanc space complexity

[reverse on MDN][reverse]

## `[...arr]`

Time complexity: O(n)
Space complexity: O(n)
Justification: You will have to peruse all the element in your input ONCE so this is linnear time. Also you are making a shallow copy of these elements into an array so each element must be copied once which implies linnear space complexity.

[spread on MDN][spread]

[push]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push
[pop]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop
[shift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift
[unshift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift
[splice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice
[slice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice
[indexOf]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf
[map]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
[filter]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
[reduce]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce
[reverse]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse
[spread]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax
