# 파이썬 프로그래밍 입문 - 수 14:00
수강자가 핵심 내용을 쉽게 알고, 실행 시켜 보는 페이지 입니다. <br> 

<hr size = "10px", width ="500px">
## [3주차 강의&nbsp;-&nbsp;수식과 연산자]()
### [산술 연산자]()
<ul>
  <li> + - * / (사칙연산) <br> 
  - 나눗셈 결과는 실수 &ensp; ex) 2/2 = 1.0 </li>
 <li> //(몫), %(나머지), **(제곱) <br>
  - 몫(정수)&ensp; // &ensp; ex) 5//3 = 1<br>
  - 나머지&ensp; % &ensp; ex) 5%3 = 2</li>
</ul>

### [할당/복합 연산자]()
<ul>
  <li> x = 10 # 왼쪽 변수공간에 오른쪽 값 할당 </li>
  <li>다중 할당 : x=y=z=1 <br>
    -  x,y = 1, 2 # 여러 개 값을 각 변수에
  </li>
  <li>자기 할당 : x = x + 3  </li>
  <li>복합 : x += 3 &ensp;# x=x+3 <br>
  - 할당과 산술/기타 연산자 결합 
  </li>
</ul>

### [관계 연산자]()
<ul>
  <li> == != (동등)  <br>
  - ==(같다), !=(같지않다)</li>
  <li>  > < >= <= (비교)<br>
  - >=, <=에서 =가 항상 뒤 </li>
</ul>

### [논리 연산자]()
<ul>
  <li> and or not<br>
  - and(모두 참이면 참)<br>
  - or (하나만 참이어도 참) </li>
</ul>

### [연산자 우선순위]()
<ul>
  <li> 산술 > 관계 > 논리 > 할당/대입 <br>
  - (&ensp;) 는 우선순위가 가장 높음</li>
</ul>

<br>

## [2주차 강의&nbsp;-&nbsp;변수와 자료형](https://github.com/baek-study/wed_py25/blob/main/source/week2_mju.ipynb)

### [변수(variable)]()
<ul>
  <li>변수 : 데이터를 저장하는 공간 </li>
  <li>이름 규칙 : 알파벳(a~z, A~Z), 숫자(0~9), 밑줄(_)로 구성 <br>
  - 시작시 숫자 안됨, 공백 안됨, 예약어 안됨 </li>
   <li>정의 : 변수이름 = 값 <br>
     ex) x = 100 &ensp; #변수이름은 왼쪽
    </li> 
</ul>


### [자료형(Data Type)](https://github.com/baek-study/wed_py25/blob/main/source/week2_mju.ipynb)
<ul>
  <li> 정수형(123), 실수형(3.14, 3.14e12) </li>
  <li>  문자열("hi", 'hi'), 논리형(True,False) </li>
  <li>  자료형 확인 함수 : type(1234) </li>
  <li>  정수로 변환 함수 : int("100")   </li>
</ul>

### [표준 입력함수 input()](https://github.com/baek-study/wed_py25/blob/main/source/week2_mju.ipynb)
<ul>
   <li>키보드를 통해 입력한 값을 '문자열'로 반환</li>
    <li> msg = input('안내메시지')&ensp;#문자열로 반환</li>
    <li> age = int(msg)&ensp;#정수변환</li>
    <li> fage = float(msg)&ensp;#실수변환</li>
</ul>

### [표준출력함수 print()](https://github.com/baek-study/wed_py25/blob/main/source/week2_mju.ipynb)
<ul>
    <li> 문자열 출력 : print('hello') </li>
    <li> 다양한자료형 : print(1004);print(3.14);</li>
    <li> 여러개 값: print(2, '+', 3)&ensp;#콤마 이용</li>
    <li> 출력제어문자: print('탭키 \t 줄바꿈 \n ')</li>
  </li>
</ul>

<br>

<br>

## [1주차]()
<ul>
  <li>
    파이썬 소개 - 인터프리터(Interpreter) 언어, 객체지향 언어     
  </li>
  <li>
    파이썬 통합 개발 환경 - IDLE, Colab, Jupyter Notebook 등    
  </li>
