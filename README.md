# Markdown 문법정리

## Markdown 이란

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## 강조
* __기울여 쓰기(italic)__
    ```
    *기울여 쓰기(italic)*
    _기울여 쓰기(italic)_
    ```
    *기울여 쓰기(italic)*
    _기울여 쓰기(italic)_

* __굵게 쓰기(bold)__
    ```
    *굵게 쓰기(bold)**
    __굵게 쓰기(bold)__
    ```
    *굵게 쓰기(bold)**
    __굵게 쓰기(bold)__


## 제목
* __큰제목__
    ```
    큰 제목 H1
    ========
    ```
    큰 제목 H1
    ========

* __작은제목__
    ```
    작은 제목 H2
    ----------
    ```
    작은 제목 H2
    ----------

## 리스트
* 인용문
    ```
    > 인용문
    > > 연속 인용문 
    ```
> 인용문
> > 연속 인용문

* __순서가 있는 리스트__
    ```
    1. 첫번째
	3. 두번째
	2. 세번째
    ```

1. 첫번째
2. 두번째
3. 세번째 

* __순서가 없는 리스트__
    ```
    * 첫번째
	+ 두번째
	- 세번째
    ```

* 첫번째
+ 두번째
- 세번째 

* __혼합 리스트__
    ```
    1. 첫번째
		+ 두번째
	2. 세번째
    ```

1. 첫번째
	+ 두번째
2. 세번째 

##블럭
* __블럭__
    ```
     ```{.python}
	 def sum(a, b):
     return a+b
	 ```
    ```
```{.python}
def sum(a, b):
    return a+b
```

* __코드 블럭__
    ```
     `code`
    ```
`code`

##링크
* __인라인 링크__
	```
	[링크](http://example.com "링크제목").
	```
	[링크](http://example.com "링크제목").

* __참조 링크__
	```
	[링크1][1] 과 [링크2][2].

	[1]: http://example.com/ "링크제목1"
	[2]: http://example.org/ "링크제목2"
	```
[링크1][1] 과 [링크2][2].
[1]: http://example.com/ "링크제목1"
[2]: http://example.org/ "링크제목2"

##수평선
* __수평선__
	```
	---------
	_________
	*********
	```

---------
_________
*********