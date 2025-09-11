# 파이썬 프로그래밍 입문 - 수 14:00
수강자가 핵심 내용을 쉽게 알고, 실행 시켜 보는 페이지 입니다. <br> 


| 주차 | 수업내용 | 과제 |
| --- | --- | --- |
| 1주 | 교과목 소개, 파이썬 개발환경 설정 |   | 
| 2주 | 자료형1 - 변수와 자료형 |   | 
| 3주 | 자료형2 - 수식과 연산자 |   | 
| 4주 | 자료형3 - 문자열 | 1차 과제 | 
| 5주 | 자료형4 - 리스트 |  | 
| 6주 | 제어문1 - 조건문(if) |  | 
| 7주 | 제어문2 - 다중 조건문 |2차 과제 | 
| 8주 | <p>$\bf{\large{\color{#6580DD}중간시험\ (이론시험)\}}$</p> |  | 
| 9주 | 제어문3 - 반복문(for)  |  | 
| 10주 | 제어문4 - 반복문(while), 보조제어문  |  | 
| 11주 | 함수1 - 함수 정의/함수 호출 |3차 과제  | 
| 12주 | 함수2 - 함수 변수/표준 모듈  |  | 
| 13주 | 중급1 - 딕셔너리  | | 
| 14주 | 중급2 - 파일 입출력 |4차 과제  | 
| 15주 | <p>$\bf{\large{\color{#6580DD}기말시험\ (이론시험)\}}$</p> | | 
<hr size = "10px", width ="500px">

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
  <li> 정수(123), 실수(3.14, 3.14e12) </li>
  <li>  문자열("hi", 'hi'), 논리(True,False) </li>
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
