# TIL_02# JAVASCRIPT_02 변수

### 01. 변수란?

</br>

````javascript
var result = 10+20;
````

자바스크립트를 해석하고 실행하는 자바스크립트 엔진도 사람과 유사하게 자바스크립트 위 코드를 실행한다. 자바스크립트 엔진이 위 자바스크립트 코드를 계산(평가<sup>evaluation</sup>)하려면 먼저 10,20 +라는 기호 (리터럴<sup>ilteral</sup>과 연산자<sup>operator</sup>)의 의미를 알고 있어야한다. <br>자바스크립트 엔진이 10 + 20이라는 식의 의미를 해석하면 + 연산을 수행하기 위해 먼저 + 연산자의 좌변과 우변의 숫자 값, 즉 <br>피연산자<sup>operand</sup>를 기억한다.
<br><br>메모리는 데이터를 저장할 수 있는 메모리 셀<sup>memory cell</sup>의 집합체이다. 메모리 셀 하나의 크기는 1바이트(8비트)이며, 컴퓨터는 <br>메모리 셀의 크기, 즉 1바이트 단위로 데이터를 저장하거나 읽어들인다.

<br><br><span style ="color:violet;">var</span><sup>클래스</sup>  <span style="color: mediumpurple;">result</span><sup>변수(식별자)</sup> = 10+20;
<br><br>여기서 변수는 메모리에 10+20의 값인 30에 접근하기 위해, 메모리 주소에 접근을한다.<br>
즉, <strong>변수<sup>variable</sup>는 하나의 값을 저장하기 위해 확보한 메모리 공간 자체 또는 그 메모리 공간을 식별하기 위해 붙인 이름을 말한다.</strong><br>간단히 말하자면 변수는 프로그래밍 언어에서 값을 저장하고 참조하는 매커니즘으로, <strong>값의 위치를 가리키는 상징적인 이름</strong>이다.
<br>
<br>
<img src = "https://user-images.githubusercontent.com/89179590/132936814-b00f0b5f-08b6-4b68-ac49-40e2e7198dfd.jpg">

