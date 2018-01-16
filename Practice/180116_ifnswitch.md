# Swift 문법
> 2018.01.16 업데이트   

## 이론 강의
### 조건문
> 함수 내에서 실행되는 선택문   
> 특정 조건에 따라 선택적으로 코드를 실행시킨다.   
> 대표적인 조건문으로 if-else문과 swhich-case문이 있다.   
> 비교 연산자를 통해 나오는 Bool값이 나와야 된다.   
> 논리 연산자를 사용하여 조건 조합이 가능하다.   

#### if-else문
> 조건이 참일 경우 if문의 대괄호 안의 코드가 실행된다.   
> 만약 조건이 거짓일 경우 else문 대괄호 안의 코드가 실행된다.   

```swift
if 조건 {
    // 조건이 만족되면 실행
}else{
    // 조건이 만족되지 않을 때 실핼
}
// * 조건 값은 참 or 거짓으로 표현되는 Bool을 사용한다.
```

#### else if문
> if문 안에 else if를 추가하여 조건을 반복해서 추가할 수 있다.   

```swift
if 조건 {
    // 조건이 만족되면 실행
}else if{
    // 추가 조건문을 반복적으로 추가할 수 있다.
}else{
    // 조건이 만족되지 않을 때 실핼
}
// * 조건 값은 참 or 거짓으로 표현되는 Bool을 사용한다.
```

#### 산술 연산자
| 기호 |    예제    |  설명  |
|:----:|:----------:|:------:|
|   +  |  1 + 2 = 3 | 더하기 |
|   -  |  2 - 1 = 1 |  빼기  |
|   *  |  2 * 1 = 2 | 곱하기 |
|   /  | 10 / 3 = 3 | 나누기 |
|   %  | 10 % 3 = 1 | 나머지 |

#### 비교 연산자
| 기호 |  예제  |          설명         |
|:----:|:------:|:---------------------:|
|  ==  | A == B | A와 B가 같다          |
|  >=  | A >= B | A가 B보다 크거나 같다 |
|  <=  | A <= B | A가 B보다 작거나 같다 |
|   >  |  A > B | A가 B보다 크다        |
|   <  |  A < B | A가 B보다 작다        |

#### 논리 연산자
| 기호 |    예제   |                      설명                     |
|:----:|:---------:|:---------------------------------------------:|
|  ==  |   A && B  | A조건이 참이고, B조건이 참이면,참이다.        |
|  ||  |   A || B  | A조건이나, B조건 둘중에 하나가 참이면,참이다. |
|   !  | !(A || B) | A || B조건의 반대                             |

#### 추가 연산자
복합연산자
| 기호 |  예제  |         설명        |
|:----:|:------:|:-------------------:|
|  +=  | a += 1 | a에 1의 값을 더하기 |
|  -=  | a -= 1 | a에 1의 값을 빼기   |

범위 연산자
|  기호 |  예제  |                 설명                |
|:-----:|:------:|:-----------------------------------:|
| a...b | 3...10 | a부터 b까지의 숫자 예) 3,4,5....10  |
| a..<b | 3..<10 | a부터 b앞까지의 숫자 예) 3,4,5....9 |   

identity 연산자
| 기호 |       예제      |                      설명                      |
|:----:|:---------------:|:----------------------------------------------:|
|  === | name1 === name2 | name1과 name2는 같은 인스턴스를 참조하고 있다. |
|  !== | name1 !== name2 | name1과 name2는 다른 인스턴스를 참조하고 있다. |

