1)The keyword "fixes" is not the only way to auto-close a pull request. You can do it
with the keywords: close, closses, closed, fix, fixes, fixed, resolve, resolves and resolved

2)You dont have to create a pull request each time. You can close multiple issues within
the same PR by seperating keywords and #X with commas.

3) 
function arrPlus2(num){
    return num + 2;
}

// Using map as a named function declaration
let arr1 = [1, 2, 3, 4, 5];
let listRev = arr1.map(arrPlus2);
console.log(listRev);

// Using map as a anonymous function
let arr2 = [1, 2, 3, 4, 5];
let listRev2 = arr2.map(function arrPlus2(num){
    return num + 2;
});
console.log(listRev2);

// The map function executes the function is the map parenthesis on each element in an array.
// Im not exactly sure about the "transformation function" being refered to as a callback function
//but from what I've read, we are able to do something after the function is executed for each
//array element. 
//
