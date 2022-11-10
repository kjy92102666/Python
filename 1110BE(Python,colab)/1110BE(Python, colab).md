
==colab== 
= 
(구글지원, == 아나콘다를 옮겨놨다~)
- mnist_test.csv  //몇만개의 숫자가 들어있다. 데이터 분석용들...
- 파일에 여러 폴더들은 colab에서 Linux를 통째로 줬다...??
- 마운트 (경로 설정?)
    (윈도우는 자동으로 마운트, Linux는 수동으로 설정 해줘야..)
 - `a[9:15] ==> [9]~[15-1]까지 값들이 출력`
   [시작인덱스:끝인덱스-1]
 - `a=100
   `b=200
   `print("I eat %d apples, $d " % a b) //한개 이상일때, () 로 묶어서 쓴다~
 - `a=100
	`d=3.14
	`b='철수'
	`print("정수 %d 실수 %.2f, 문자열 %s" % (a,d, b))`

 - `str = 'five'
	`str2 = 'two'
	`"I eat{0} apples{1}".format(str,str2)`
	`=I eatfive applestwo`
 - `"{0:<10}".format("Hello")
	 `Hello       `
 - `"{0:^10}".format("Hello") `
	`  Hello   `
 - `"{0:-^10}".format("Hello")`
	`--Hello---`
 - `d = {'name':'홍길동','age':30} ㅡJSON 표기법`
  ` f'나의 이름은{d["name"]} 나이는 {d["age"]} 입니다.'
  {d[]}' - key:value, f 생략시 문자열로 출력! f사용해야 Json기법 작동!! 
★ 함수, 메소드(객체 내에서만)차이 : 기능의 작동범위. 
  함수 : 맞는 데이터만 주면 기능 작동.
  메소드 : 객체 내에있는 한정된 데이터로 작동.
 - `a="Python is the best choice"
	`a.find('b')`
	`=14`
	º`a.index('e') 
 - `#문자열 삽입
   `",".join('abdc')`
	`=a,b,d,c
	`
	`a=['a', 'student', 'friend','mother']
	`print("_".join(a))
	`=a_student_friend_mother`

	```
	a="""     
	hi          """
	a.strip()
	="hi"
	```

   - replace. 문자 패턴 재배
	`a=  Life is too short
	`a.replace("Life", "삶")	
	`= 삶 is too short
 ```
 a='Life is too short'
 b=a.split()
 c=",".join(b)
 c
 =Life,is,too,short
 d=c.split(",")
 d
 =['Life', 'is', 'too', 'short']
 ```


- 리스트 자료구조, 배열객체, 리스트 컬렉션
 ```
 odd = [1,3,5,7,9]
 odd[0:3]
 =[1, 3, 5]
```


  ```
  a=[]
  b=[1,2,3]
  c=['Life','is','too','short']
  d=[1,2,'Life','is']
  e=[1,2,['Life','is']]
  s=e[2]
  s[0]
  ```

 a=[]

b=[1,2,3]

c=['Life','is','too','short']

d=[1,2,'Life','is']

e=[1,2,['Life','is',['apple','banana']]]

s=e[2][2][0]

s
[회원 아이디 : 1, 이름 : 1, 이메일 : 1, 주소 : 1, 나이 : 1 , 
회원 아이디 : 2, 이름 : 2, 이메일 : 2, 주소 : 2, 나이 : 2 , 
회원 아이디 : 3, 이름 : 3, 이메일 : 3, 주소 : 3, 나이 : 3 ] 





























`1`