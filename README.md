https://github.com/indongyoo/functional-javascript-01

제대로 배워봅시다.

1. 자바스크립트는 함수를 값으로 다룰 수 있다. = 자바스크립트의 함수는 일급 함수이다. => 조합성과 추상화의 도구
2. 고차함수는 함수를 값으로 다루는 함수로 말한다.
3. "ARRAY/SET/MAP"은 이터러블/이터레이터 프로토콜을 가진다.
4. 이터러블은 순회가능한 자료구조를 말한다.
5. 이터레이터는 순회가능한 next(val, done) 메소드를 가지는 객체를 말한다.
6. 이터러블/이터레이터는 for ... of, 전개연산자 활용 가능하다.
7. "ARRAY"는 이터러블이지, 이터레이터는 아니다.
8. "ARRAY"에서 [Symbol.iterator] 메소드를 선언하면 이터레이터가 된다.
9. 전개연산자 '...'도 이터러블/이터레이터 프로포토콜이 구현되어 있다.
10. 제너레이터를 활용하면 어떠한 값도 순회할 수 있는 형태로 만들 수 있다.
11. 일반 객체는 이터러블이 아니며, dom 객체도 그러하다.
12. 제너레이터는 순회할때 평가가 되는 이터레이터 객체다.
13. 평가 순서를 미루는 지연 평가 기법을 활옹하면 좀 더 성능 우위 있는 코딩이 가능하다.
14. 지연 평가 "map, filter"는 결합순서가 바뀌어도 결과는 같다.