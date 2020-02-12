# projects_lab
## Q1: Is the keyword "fixes" the only way to auto-close an issue from a PR 
## (pull request). Is there other keywords that can accomplish the same thing?
NO, keyword "fixes isn't the only way to auto-close an issue from a PR. Other keywords like close, closes, closed, fix, resolve, resolves, 
resolved can also be used.

## Q2: Do you have to create a new PR EVERYTIME you want to close an issue, or is it possible to close multiple issues within a single 
## PR? If so, how?
It is possible to close multiple issues within a single PR. Just use use auto-close keywords for each of the issues created(comma seperated)
for example - closes #1, closes #2, closes #3; commit message.

## Q3: Provide an example of using map that is different from the one I have done. Your example must use map both as a named function declaration ## and with an anonymous function.

### anonymous
let array = [0, 1, 2, 3, 4, 5, 6]
newArray = array.map(function (element) {
    element ++;
    return element;
})
console.log(newArray);

### named function
let array = [0, 1, 2, 3, 4, 5, 6]
newArray = array.map(function addition(element) {
    element ++;
    return element;
})
console.log(newArray);