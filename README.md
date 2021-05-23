>>> scalar 3       

vector [2, 3, 4] + 5
  [2, 3, 4] + [5, 5, 5]

matrix [ [1, 2], [3, 4] ]

tensor [ [[1,2], [3,4]], [[5,6],[7,8]] ]

n-tensor

cumsum
n ==> number


 2^8 == bit 8개 = 256 == 1바이트 
 정수 : -128 ~ 127 
 양수 : 0 ~ 255 

수의 표현 방식 
1) 부호와 절대 값
2) 1의 보수 
3) 2의 보수 
부호==>  0은 양수, 1은 음수 

000  0         -4 ~ 3      [ row , column ]
001  1                     [ : , : ]
010  2                     [ : : , : : ]
011  3

100  -0
101  -1
110  -2
111  -3




00
01
10
11











진법, 진수 : 한 자리수로 표현 가능한 경우의 수 
2진수, 8진수, 16진수 
0
000
001
...
0000
0001
















NaN, NULL, None - 空 -- 결측치 

정규표현식  
처음 ^   : ^a, ^ac
끝  $  : exe$
0번 이상 중복 * : ab*,   괴랄하다  like '이%'    
한 문자 와일드카드 _ : a_b, a__b,   
 
$ls a*
$ls  ^ap*
 


 
join : 여러 테이블에서 필요한 내용만 추출 
merge : 합친다. - 병합


seaborn
bokeh
folium
 repl.it 
 
apt  list | grep jdk 
apt  list | grep  java 
apt  list | grep  ^java 
cd 
mkdir  bb
cd  bb 
ls  -al 
apt  list >  apt_list 

ls -alRSt   / 
ls  /etc 
ls  /etc  |  grep  conf$

cd 
mkdir b1 

cd b1
cat > a1 
서울
부산
대구
^D        ====> EOF                            

$cat > a2 
500
600
800
^D
$nl a1 
$nl a2
$cd  
$cd  /usr/local
$pwd
$cd  /etc/X11

* linux 필수 명령어 

ls - 디렉터리 내용보기 
pwd - 현재 위치 확인 
whoami - 나는 누구인가?
cd - change directory
mkdir - 디렉터리 만들기 
rmdir - 디렉터리 삭제 
cat  - 파일 내용 보기 
nl   - 행번호 붙여 파일 내용 보기 
clear - 화면 지우기 ^L 
^D - EOF - end of file 
. 현재 디렉터리
.. 부모  디렉터리
~  HOME  디렉터리
/  최상위 루트  디렉터리


>create  table Book(
  title  char(20),
  price  int);

>.schema
>insert into Book values('정석수학', 2000);
>insert into Book values('영단어2000', 3000);
>select * from Book;
>.help
>.quit

~$ python
Python 3.8.9 (default, May  3 2021, 02:40:41) 
[GCC 7.5.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print('hahaha')
hahaha
>>> quit()
~$ cat > a.py
for i in range(5):
    print(' Python zzang... ')
~$ python a.py
 Python zzang... 
 Python zzang... 
 Python zzang... 
 Python zzang... 
 Python zzang... 
