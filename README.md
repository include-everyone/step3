# step3

file, open, read, write, close

- step3 에서는 파일을 열고 닫고 생성하고 수정하는 방법을 알아봅니다.

### step3-0
- open, read, write, close 함수들을 찾아봅니다.

### step3-1
```
hello world!!!
c
python
c++
java
c#
php
go
```
- 임의의 내용이 들어간 파일을 하나 작성하고 프로그램에서 파일을 열고 내용을 출력하는 프로그램을 작성해 봅니다.

### step3-2
- 파일의 내용에서 어떤 문자 또는 문자열을 포함하는 줄을 다른 새로운 파일에 저장해 봅니다.

> 예시
```
infile
  hello world!!!
  c
  python
===============
step3_fn(file_name, find_str), find_str == l
outfile
  infile
  hello world!!!
===============
$> grep l infile
infile
hello world!!!
```
