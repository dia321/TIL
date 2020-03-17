### 객체 생성 방법

객체는 키와 밸류로 구성된 property들의 모임

- 객체 리터럴
- Object 생성자 함수



객체 속성접근: ~~~[속성]



### 배열

JS에서 배열은 값만 존재함



#### 배열 순회

- for
- for of
- forEach
- for in : 배열의 속성까지 출력 가능

#### 배열 메소드

- sort 메소드에 비교 함수가 없으면 문자열 기준 정렬(ex. 1 100 2 3 30 4 5 등)
  - numbers.sort(function(a,b) {return a-b;}) 
- 문자열-join, string cf) 배열의 메소드임(파이썬이랑 다르게 string의 메소드가 아님)
- concat: 배열로 합치기(append, extend 느낌) (+는 문자열로 합치기)
- 원소 삽입/삭제 : push, pop, unshift(처음 인덱스에 넣음), shift(처음 인덱스에서 뺌)
- 인덱스 탐색: indexOf
- 배열 조작: splice(시작지점, 몇개를 지우기, 배열에 추가할 요소,..)
- 배열 자르기: slice



### 함수

- 함수선언: function 뭐시기(a,b)

  ​				 var 뭐시기 = function(a,b)

- 화살표 함수: `뭐시기 = (a,b) => a+b` 같이 표현함

### 함수 인자

매개변수 전달에 제한이 없음

넘겨진 것이 없으면 undefinded



##### css 응용

중앙정렬 : display:flex로 할 수 있음

​	(자식요소들이 item으로 나온다는 뜻)

​	justify-content:center;

​	align-items:center;