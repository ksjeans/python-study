<!DOCtype html>
<head>
    <h1> Study </h1>
</head>
<body>
    <a href = "https://krafton.enterprise.slack.com/docs/T0GCQMN07/F05QBPC5FED"> 슬랙 캔버스로 일단 만들어봄 </a>
    <h2> 과제 1번 </h2>

연산자|int|float|str|list|tuple|set|dict|
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
'+'| 가능|가능|가능|가능|가능|불가능|불가능
'-'|가능|가능|불가능|불가능|불가능|불가능|불가능
'*'|가능|가능|가능|가능|가능|불가능|불가능
'/'|가능|가능|불가능|불가능|불가능|불가능|불가능
---
    
<h2> 과제 2번 </h2> 
   
연산자|int+float|int+str|int+list|float+str|float+list|str+list|str+tuple|list+tuple|
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
'+'|가능|불가능|불가능|불가능|불가능|불가능|불가능|불가능|
결과|float|X|X|X|X|X|X|X|
---
연산자|int-float|int-str|int-list|float-str|float-list|str-list|str-tuple|list-tuple|
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
'-'|가능|불가능|불가능|불가능|불가능|불가능|불가능|불가능|
결과|float|X|X|X|X|X|X|X|
---
연산자|float-int|str-int|list-int|str-float|list-float|list-str|str-tuple|list-tuple
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
'-'|가능|불가능|불가능|불가능|불가능|불가능|불가능|불가능|
결과|float|X|X|X|X|X|X|X|
---
연산자|int x float|int x str|int x list|int x tuple|float x str|float x list|str x list|list x dict|
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
'*'|가능|가능|가능|가능|불가능|불가능|불가능|불가능|
결과|float|str|list|tuple|X|X|X|X|
---
연산자|float x int|str x int|list x int|str x float|list x float|list x str|tuple x str|tuple x list
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
'*'|가능|가능|가능|불가능|불가능|불가능|불가능|불가능|
결과|float|str|list|X|X|X|X|X|
---
<h2> 과제 3번 </h3>

\- int * float: int와 float 타입을 곱하면 결과가 어떻게 되나요?

- [x] A = int 3 / B = float(5) 곱하면 15.0 으로 결과가 출력

\- int * str: int 타입을 str 타입과 곱하면, 문자열이 어떻게 되나요?
- [x] A = int 3 / B = "aaa" 곱하면 aaaaaaaaa 으로 결과가 출력

\- int * list: int 타입을 list 타입과 곱하면, 리스트가 어떻게 되나요?

- [x] A = int 3 / B = [5,6,7] 곱하면 [5,6,7,5,6,7,5,6,7] 으로 결과가 출력

\- int * tuple: int 타입을 tuple 타입과 곱하면, 튜플이 어떻게 되나요?

- [x] A = int 3 / B = (2,7,8) 곱하면 (2,7,8,2,7,8,2,7,8) 으로 결과가 출력
</body>
</html>
