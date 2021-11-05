<H1>TIL_#02-Javascript_03 </H1>

<H3>01. 변수 호이스팅</H3>

<br>

```javascript
console.log(score);  //undefined

var score;  //변수 선언문
```

변수 선언문보다 변수를 참조하는 코드가 앞에 있다. <br>자바스크립트 코드는 **인터프리터**에 의해 한 줄씩 순차적으로 실행되므로, console.log(score);가 먼저 실행된다. 따라서 console.log(score);가 실행되는 시점에는 아직 score 변수의 선언이 실행되 장ㄶ았으므로, 참조에러가 발생한것처럼 보이게 된다.
<br><br>하지만 참조 에러가 발생하지 않고, **undefined**가 출력이된다.<br>**그 이유는 변수 선언이 소스코드가 한 줄씩 순차적으로 실행되는 시점, 즉 런타임<sup>runtime</sup>이 아니라 그 이전 단계에서 먼저 실행되기 때문이다.** 
<br><br>**자바스크립트는 변수 선언을 포함한 모든 선언문을 제외하고 소스코드를 한 줄 씩 순차적으로 실행한다.**
<br>
<br>

<img src="https://user-images.githubusercontent.com/89179590/140484452-51478a50-bf32-4773-b268-70bc59c4c16e.jpg">

