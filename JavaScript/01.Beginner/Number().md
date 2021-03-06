#Number()

- 자바스크립트에서 모든 숫자는 실수로 표현된다. 정수와 실수를 구분하지 않는다.

## 1. Number() 객체의 사용
- Number() 생성자 함수는 숫자 객체와 숫자 원시값을 만들 때 사용한다.
```javascript
var numberObject1 = new Number(1); //new 키워드를 사용해 숫자 객체를 만든다.
console.log(numberObject1, typeof numberObject1); //'[Number: 1]' 'object'가 기록된다.

var numberObject2 = Number(1); //new 키워드 없이 숫자 원시값을 만든다.
console.log(numberObject2, typeof numberObject2); //'1' 'number'가 기록된다.

var numberLiteral = 1; //리터럴 표기법을 사용해 숫자 원시값을 만든다. 생성자가 암묵적으로 사용된다.
console.log(numberLiteral, typeof numberLiteral); //'1' 'number'가 기록된다.
```


## 2. Number() 속성과 메소드
- **속성**
  - MAX_VALUE
  - MIN_VALUE
  - NaN
  - NEGATIVE_INFINITY
  - POSITIVE_INFINITY
  - prototype


## 3. Number 객체 인스턴스의 속성과 메소드
- **인스턴스 속성**
  - constructor
- **인스턴스 메소드**
  - toExponential()
  - toFixed()
  - toLocaleString()
  - toPrecision()
  - toString() 문자열로 변환한다. 괄호 안에 넣는 숫자에 따라 진법을 달리할 수 있다. (예: `number.toString(2)`는 2진수로 number를 표현한다.)
  - valueOf()
