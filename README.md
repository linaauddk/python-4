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
    
