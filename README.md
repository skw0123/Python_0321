# Python_2
##### 제곱
```
x = lambda a: a * a
print(x(10))

--> 100
```
##### 짝수 고르기
```
numbers = [111, 26, 37, 48]
result = list(filter(lambda x: x % 2 == 0, numbers))
print(result)

--> [26, 48]
```
##### 짝수 고르기 2
```
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
print(list(filter(lambda x: x % 2 == 0, numbers)))

--> [2, 4, 6, 8, 10]
```
##### 짝수 고르기 3
```
print(list(filter(lambda x: x % 2 == 0, [1, 2, 3, 4, 5, 6, 7, 8, 9, 10])))

--> [2, 4, 6, 8, 10]
```
##### 짝수 고르기 4
```
print([x for x in [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] if x % 2 == 0])
```
