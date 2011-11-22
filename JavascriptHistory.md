JavaScript 와 ECMAScript 의 역사
===============================

#1995년 4월#
BrendanEich 가 Netscape Communications Corporation에 "10일안에 브라우저 안에서 Scheme이 동작하도록" 해주기로 약속하고 입사.
(Scheme을 선택한 것은 이전 직장이었던 SGI에서 Nick Thompson의 영향으로 SICP에 흥미를 가졌던 적이 있었기 때문)
그러나 '자바같이 보이도록' 만드는 쪽으로 결정이 내려져서 Scheme을 사용하려던 계획은 버려짐.

#1995년 9월#
넷스케이프 네비게이터 2.0 베타 릴리즈. 이 때 *LiveScript* 라는 이름으로 탑재됨.

#1995년 12월 4일#
넷스케이프 네이게이터 2.0B3을 릴리즈하면서 이름을 LiveScript 에서 *JavaScript* 로 변경함.
(Netscape and Sun did a license agreement.)

#1996년 8월#
마이크로소프트 Internet Explorer 3.0 릴리즈. *JScript*가 탑재됨.
JScript는 JavaScript와 거의 같지만, trademark issue를 피하기 위해 이름을 바꾼 것임.
(Y2K 문제를 피하기 위해 새로운 date 메소드가 들어갔다는 것 정도가 다름)

#1996년 가을#
Eich가 집에서 2주간 Mocha 를 재작성.
이 Mocha가 나중에 SpiderMonkey 가 된다.

#1996년 11월#
Netscape는 JavaScript를 산업표준화를 위해 EcmaInternational 에 제출했음을 published.
그리하여 *ECMAScript* 탄생. JavaScript 와 JScript 는 ECMAScript + 추가기능.

#1997년#
Java로 재작성된 Netscape Navigator가 계획됨.
여기에 탑재될 자바스크립트 엔진을 만들기 위해 Rhino 프로젝트 시작.

#1997년 6월#
*ECMA-262 first edition* published.

#1998년 6월#
*ECMA-262 second edition* published.
Editorial changes to keep the specification fully aligned with ISO/IEC 16262 international standard

#1999년 12월#
*ECMA-262 third edition* published.

* Added regular expressions
* better string handling
* new control statements
* try/catch exception handling
* tighter definition of errors
* formatting for numeric output and other enhancements

*JavaScript 1.5*. 현제 대세. 익스플로러 5.5도 지원함.

#2004년 6월#
ECMA-357(E4X, ECMAScript for XML) published.

#2005년 8월#
BrendanEich, Mozilla Corporation의 CTO 취임.

#2005년 11월#
*JavaScript 1.6* (Firefox 1.5)

* E4X
* Array extras (e.g. Array.prototype.forEach)
* Array and String generics (New in JavaScript 1.6)

#2006년 10월#
*JavaScript 1.7* (Firefox 2.0)

* Pythonic generators and array comprehensions 
* block scope with let
* destructuring assignment

#2008년 6월#
*JavaScript 1.8* (Firefox 3.0, Opera 11.50)

* expression closures (function(x) x * x)
* generator expressions
* and more (New in JavaScript 1.8)

#2008년 8월 13일#
*ECMAScript 4th edtion* to *ECMAScript Harmony*
(나중에 JavaScript 2.0이 될 예정)

#2009년 1월#
CommonJS 프로젝트 시작. JavaScript 의 standard library를 만드는 것이 목표.

#2009년 12월#
*ECMAScript 5th edition* published.

* Adds "strict mode"
    * a subset intended to provide more thorough error checking and avoid error-prone constructs. Clarifies many ambiguities in the 3rd edition specification
    * and accommodates behaviour of real-world implementations that differed consistently from that specification.
* Adds some new features
    * such as getters and setters
    * library support for JSON
    * and more complete reflection on object properties.

SpiderMonkey, Rhino, V8이 지원함.

*JavaScript 1.8.5* (Firefox 4, Internet Explorer 9)

#2011년 6월#
*ECMAScript Language Specification 5.1 edition* published.
This edition 5.1 of the ECMAScript Standard is fully aligned with third edition of the international standard ISO/IEC 16262:2011

#2011년#
SpiderMonkey 코드 소유권을 Dave Mandelin에게 이전

References
----------
* http://en.wikipedia.org/wiki/Javascript
* http://en.wikipedia.org/wiki/Ecmascript
* http://en.wikipedia.org/wiki/Rhino_(JavaScript_engine)
* http://brendaneich.com/2008/04/popularity/
* http://brendaneich.com/2011/06/new-javascript-engine-module-owner/
* http://www.infoworld.com/d/developer-world/javascript-creator-ponders-past-future-704
* http://www.computerworld.com.au/article/255293/a-z_programming_languages_javascript#closeme
