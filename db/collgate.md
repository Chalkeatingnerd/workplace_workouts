# collgate

> a collation is a set of rules that defines how to compare and sort character strings. Each collation in MySQL belongs to a single character set. Every character set has at least one collation, and most have two or more collations. A collation orders characters based on weights. Each character in a characters with unequal weights compare according to the relative magnitude of their weights.

* 문자열을 어떻게 비교하고 정렬할지 정의한 규칙의 집합
* 각 collation(정렬)은 하나의 character set에 속해있다.
* 모든 character set은 적어도 1개 이상의 collation을 가지고 있다.
* character set에 포함된 각 문자는 가중치에 맵핑된다.
* 동일한 가중치를 가지는 문자들을 비교하면 같다고 판단한다.
* 서로 다른 가중치를 가지는 문자들을 비교하면, 각 문자가 가지는 가중치의 크고 작음에 따라 동일한 문자인지 아닌지 판단한다.

[adding a collation to characterset](https://dev.mysql.com/doc/refman/8.0/en/adding-collation.html#:~:text=A%20collation%20is%20a%20set,orders%20characters%20based%20on%20weights.)

## 사용

DB를 구축하다보면 텍스트 데이터(text data)를 취급해야 할 때가 있다. 이때 반드시 고민해야 하는 것이 문자셋(character set)을 선택하는 것이다.



