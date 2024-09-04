# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    var foo = mystery(a.slice(1, a.length))
    if(foo > a[0]) return foo;
    else return a[0];
}
```

The 'mystery()' function starts off by checking if the length of the array is one, if yes it returns the only value within the array. If no, then it continues to disregard the first value in the array(due to the slice and selected bounds) and creates a new variable "foo" that should be for the maximum value in the smaller array. The final two lines compare the found value to the first value to see which on is larger and it will return the larger value.



I used W3 schools and programmiz to get a better understanding of what the slice() method does and how it works inside this function, I used 
the links: https://www.w3schools.com/jsref/jsref_slice_array.asp and https://www.programiz.com/javascript/library/array/slice to help me.

I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.
