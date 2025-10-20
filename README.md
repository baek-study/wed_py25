# 파이썬 프로그래밍 입문 - 수 14:00
수강자가 핵심 내용을 쉽게 알고, 실행 시켜 보는 페이지 입니다. <br> 

<hr size = "10px", width ="500px">


<br>

<br>


## [1주차 강의 &nbsp;-&nbsp;파이썬 소개]()
<ul>
  <li>
    특징 - 인터프리터(Interpreter) 언어, 객체지향 언어     
  </li>
  <li>
    통합 개발 환경 - IDLE, Colab, Jupyter Notebook 등  <br>
  </li>
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


## [3주차 강의&nbsp;-&nbsp; 연산자](https://github.com/baek-study/wed_py25/blob/main/source/week3_mju.ipynb)
### [산술 연산자]()
<ul>
  <li> + - * / (사칙연산) <br> 
  - 나눗셈 결과는 실수 &ensp; ex) 2/2 = 1.0 </li>
 <li> //(몫), %(나머지), **(제곱) <br>
  - 몫(정수)&ensp; // &ensp; ex) 5//3 = 1<br>
  - 나머지&ensp; % &ensp; ex) 5%3 = 2</li>
</ul>

### [할당/복합 연산자](https://github.com/baek-study/wed_py25/blob/main/source/week3_mju.ipynb)
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

### [관계 연산자](https://github.com/baek-study/wed_py25/blob/main/source/week3_mju.ipynb)
<ul>
  <li> == != (동등)  <br>
  - ==(같다), !=(같지않다)</li>
  <li>  > < >= <= (비교)<br>
  - >=, <=에서 =가 항상 뒤 </li>
</ul>

### [연산자 우선순위](https://github.com/baek-study/wed_py25/blob/main/source/week3_mju.ipynb)
<ul>
  <li> 산술 > 관계 > 논리 > 할당/대입 <br>
  - (&ensp;) 는 우선순위가 가장 높음</li>
</ul>

<br>

## [4주차 강의&nbsp;-&nbsp;문자열](https://github.com/baek-study/wed_py25/blob/main/source/week4_mju.ipynb)

### [문자열 기본구조](https://github.com/baek-study/wed_py25/blob/main/source/week4_mju.ipynb)
<ul>
  <li> 생성 : msg = '안녕하세요' <br>
  - 인덱스: 첫문자에서 0부터 시작 <br>
  - 음의 인덱스 : 끝 문자에서 -1로 시작 </li>
  <li> 인덱싱 [순번]: msg[0]&ensp; #'안' <br>
    - 특정 순번의 개별 문자 </li>
  <li> 슬라이싱 [시작:끝]: msg[2:4] &ensp; #'하세'<br> 
    - 시작부터 (끝-1)까지 부분문자열 </li>
</ul>

### [문자열 연산/함수](https://github.com/baek-study/wed_py25/blob/main/source/week4_mju.ipynb)
<ul>
  <li> 연산 (+, *, in, == )<br>
   - 'hi'+'mju' : 문자열 결합<br>
   - 'mju'*3 : 문자열 반복<br>
   - 'm' in 'mju' : 멤버쉽<br>
    - 'hi' =='mju' : 문자열 비교<br>
     </li> 
  <li> len(msg) : 문자열 길이 함수 </li>  
  <li> msg.split() : 문자열 분리 메소드 </li>  
  <li> msg.find('안') : 문자열 발견 위치 </li>  
  <li> msg.count('안') : 문자열 발견 횟수</li>  

</ul>


### [서식 : f-문자열](https://github.com/baek-study/wed_py25/blob/main/source/week4_mju.ipynb)
<ul>
  <li> f'..{표현식}..' # 중괄호 사용  <br>
    ex) print(f'hi. {name}, age {25}') </li>
  <li> 형식지정: 정수 d, 실수 f, 문자 s </li>
  <li> 자릿수: {25:5d} &ensp; #다섯자리 확보 </li>
  <li> 정밀도: {3.145:.2f} &ensp; #소수점 몇자리 <br>
    ex) print(f'hi.{name:10s}, age {25:5d}, {PI:.2f}’)
  </li>  
</ul>
<br>

## [5주차 강의&nbsp;-&nbsp;리스트]()

### [리스트 기본 구조]()
<ul>
<li>생성 : temps=[28, 31, 33, 35, 27]  </li>
<li>인덱싱: temps[3], temps[-1]  </li>
<li>슬라이싱: temps[2:5]  &ensp;#시작에서 끝-1 까지 </li>
<li>수정1: temps[3] = 5 &ensp;# 인덱싱 이용한 수정 </li>  
<li>수정2:  temps[2:5] = [1, 2] &ensp;# 슬라이딩 이용힌 수정 </li>    
<li>단순할당 : list1 = temps &ensp;# 같은것 가리킴</li>  
<li>복사 : list2 = list(temps) &ensp;# temps[:] 새로운 리스트 </li>  
</ul>

### [리스트 연산&메소드]()
<ul>
 <li> 연산 (+, *, in, == )<br>
   - 결합 : [1,2]+[3,4,5] <br>
   - 반복 : [1,2]*3 <br>
   - 멤버쉽 1 in [1,2]  &ensp;# not in<br>
   - 비교 : [1,2] ==[3,4,5]  &ensp;# != < > 등<br>
     </li> 
  <li> 추가 : temps.append(5)  </li>  
  <li> 삽입 : temps.insert(1, 100)   </li>  
  <li> 삭제 : temps.remove(100)   </li>  
  <li> 삭제 : t = temps.pop(0)   </li>  
  <li> 검색 : temps.index(31) </li
</ul>

### [2차원 리스트]()
<ul> 
<li>1차원 리스트를 요소로 가지는 리스트</li> 
<li>s = [ <br>
 &ensp; &ensp; [ 1, 2, 3, 4, 5],<br>
 &ensp; &ensp; [ 6, 7, 8, 9, 10]<br>
    ] </li>
<li>s[1][2] &ensp;# 이름[행][열] - 8 </li>   
</ul>

<br>

## [6주차 강의&nbsp;-&nbsp;조건문]()

### [논리 연산자]()
<ul>
  <li>A and B : 둘 다 참이어야 참  </li>
  <li>A or B : 둘 중 하나만 참이어도 참  </li>
  <li>not A : 참이면 거짓, 거짓이면 참  </li>
</ul>

### [제어문]()
<ul>    
  <li>제어 구조 : 순차(직진), 조건(갈림길), 반복(로터리)</li>
  <li>파이썬 제어 포맷 : 헤더 + 스위트<br>
    제어키워드 제어조건 <b>:(콜론)</b>  &ensp;&nbsp; #헤더<br>
    &ensp;&ensp;&ensp;&ensp;들여쓰기된_문장  &ensp;&nbsp;  # 스위트 
  </li>
</ul>

### [단순 if(if~ - 선택 명령 1개)]()
<ul>    
  <li><b>if</b> score >= 60 <b>:</b>&ensp;<br>
    &ensp;&nbsp;  print('pass') <br>
  </li>
</ul>


### [선택 if(if~else - 선택 명령 2개)]()
<ul>    
  <li><b>if</b> score >= 60 <b>:</b>&ensp;<br>
    &ensp;&nbsp;  print('pass') <br>
    <b>else:</b>&ensp; <br>
    &ensp;&nbsp;  print('fail')
  </li>
</ul>

<br>

