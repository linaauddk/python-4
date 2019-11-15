# python-4
for 변수 in 시컨스
 print (---------)
 for fruit in ["바나나 ", " 사과" , "배", "감"]:
	print("과일 이름 : " + fruit)
과일 이름 : 바나나
과일 이름 : 사과
과일 이름 : 배
과일 이름 : 감

for int in [0,1,2,3,4,5,6,7,8,9]:
	print(int)
0
1
2
3
4
5
6
7
8
9

for int in [0,1,2,3,4,5,6,7,8,9]:
	print(int, end=" ") ,줄바꾸지말고 출력
0 1 2 3 4 5 6 7 8 9 

for int in [0,1,2,3,4,5,6,7,8,9]:
	print('정수 %d 입니다.'%int)
정수 0 입니다.
정수 1 입니다.
정수 2 입니다.
정수 3 입니다.
정수 4 입니다.
정수 5 입니다.
정수 6 입니다.
정수 7 입니다.
정수 8 입니다.
정수 9 입니다.


for int in [0,1,2,3,4,5,6,7,8,9]:
	print('%d번째값, 정수 %d 입니다.' %(int+1, int))
1번째값, 정수 0 입니다.
2번째값, 정수 1 입니다.
3번째값, 정수 2 입니다.
4번째값, 정수 3 입니다.
5번째값, 정수 4 입니다.
6번째값, 정수 5 입니다.
7번째값, 정수 6 입니다.
8번째값, 정수 7 입니다.
9번째값, 정수 8 입니다.
10번째값, 정수 9 입니다.

for num in range(10):   <--- 0에서 숫자 -1 까지 출력
	print(num)
0
1
2
3
4
5
6
7
8
9

for num in range(0,10):   <------ (start. stop) start에서  stop -1 
	print(num)
0
1
2
3
4
5
6
7
8
9

sum = 0
for num in range(1,11):
    sum = sum + num
print(sum)
55

for num in range(0,10,2):  <--- start, stop, step   start에서 stop-1까지 step 간격으로
    print(num)
0
2
4
6
8 
    
i=0
while i < 10:
      i=i+1
      if i == 5:
        print("if 문을 통해 break.")
        break
      print(i)
1
2
3
4
if 문을 통해 break.

i=0
while i < 10:
      i=i+1
      if i == 5:
        print("if 문을 통해 contiue.")
        continue
      print(i)
1
2
3
4
if 문을 통해 contiue.
6
7
8
9
10

i = 0
while i < 10:
    print(i)
    i=i+1
0
1
2
3
4
5
6
7
8
9

i=1
while i < 10:
    print("5*%d = %d" %(i, 5 * i))
    i=i+1
5*1 = 5
5*2 = 10
5*3 = 15
5*4 = 20
5*5 = 25
5*6 = 30
5*7 = 35
5*8 = 40
5*9 = 45

import turtle



t=turtle.Pen()

for i in range(5):
    t.forward(50)
    t.right(144)
파일이름 turtle xx

def 함수이름 (매개변수1, 매개변수2): 외부로부터 함숫값 받음, 없어도 상관 없엄
실행할 문장
실행할 문장

def greeting(name, age):
    print("만나서 반가워")
    print("난 %s이야"%name)
    print("난 %d살이야"%age)
    print("친하게 지내자")
    
   >>> greeting("규정",26)
만나서 반가워
난 규정이야
난 26살이야
친하게 지내자
