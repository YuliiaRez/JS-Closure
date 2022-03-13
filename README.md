# JS-Closure
Write a function addNum(n) that will return another function. The returned function must add the resulting argument to the return function's argument n.
Explanations:
- external function addNum(n) has parameter n
- the function returned from addNum has a parameter m
- usage example:
const add = addNum(5);
const result = add(10); // => 15
