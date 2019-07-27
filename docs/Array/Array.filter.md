# Array.filter

-�迭 ���� ��� ��� �� �ش� �Լ��� test�Ͽ� pass�� ��Ҹ����� ������ ���ο� �迭�� �����Ѵ�.



#### ����

```javascript
arr.filter(callback[, thisArg])
```


#### ��

```javascript

function isBigEnough(value) {
return value >= 10;
}
var filtered = [12, 5, 8, 130, 44].filter(isBigEnough);
// filtered is [12, 130, 44]

```



