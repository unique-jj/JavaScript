# Boolean.prototype

�ο��� ������Ÿ�Կ� ���� ������ ��ȯ�մϴ�.


#### ����

```javascript
boolean.prototype
```



### ����

`boolean` �μ��� ��ü �̸��Դϴ�.

prototype �Ӽ��� ��ü Ŭ������ �⺻ ��� ������ �����մϴ�.
�ν��Ͻ��� �� ��ü�� �ش� ��ü�� �Ҵ�� ������Ÿ���� ������ ����մϴ�. 
������Ÿ���� �Ӽ��� �޼��带 �߰��� ���� ������ �⺻ ���� ��ü�� �ٸ� ������Ÿ���� �Ҵ��� ���� �����ϴ�.

������� �迭�� �ִ��� ���� ��ȯ�ϴ� `boolean` ��ü�� �ż��带 �߰��Ϸ��� �Լ��� �����ϰ� `boolean.prototype`�� �߰��� ���� ����մϴ�.


```javascript
// �Լ�����
function isFalse(){
	if(this.toString() == 'false')
		return true;
	else
		return false;
}

// boolean.prototype �� �߰�
Boolean.prototype.isFalse = isFalse;

// ���
var bool = new Boolean(1);
document.write(boolisFalse());
```
