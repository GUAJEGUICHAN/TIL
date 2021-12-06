# RORO 패턴

RORO는 "객체를 받고 객체를 반환한다(Receive an object, return an object)"의 줄임말이다.

객체의 형태는 {a:a}와 같다. 키값과 밸류값으로 이뤄져있다. 이 형태로 값을 전달하는 것이다.

함수의 params가 많다면 순서를 잘 지켜주기 힘들어진다. 그래서 각 params의 이름에 맞춰서 값을 전댈해주면 직관적이다.

물론 길이가 길어지겠지만 이해하기 쉬운 코딩이 우선이다.



## 사용법 예시

먼저 다음처럼 선언해보자

```javascript
  function plus {operand1, operand2}{
    retrn operand1+operand2
  }
```

다음처럼 사용해보자
```javascript
  console.log(plus({operand : 1,operand2 : 1)})
```


그럼 다음 값이 나온다.

```javascriptÎ
2
```