# Array.every


- �迭 ���� ��� ��Ұ� �ش� �Լ��� �� test �Ǵ��� pass ���θ� �� �� �ִ�.




#### ����

```javascript

 
arr.every(callback[, thisArg])
 
- callback -
Function to test for each element, taking three arguments
 
currentValue (required) :
The current element being processed in the array.
 
index (optional) :
The index of the current element being processed in the array.
 
array (optional) :
The array every was called upon.
 

- thisArg -
Optional. Value to use as this when executing callback.
```




#### ��

```javascript
 
function isBigEnough(element, index, array) {
return element >= 10;
}

[12, 5, 8, 130, 44].every(isBigEnough); // false
[12, 54, 18, 130, 44].every(isBigEnough); // true

```
