# practice_for_markdown

# 1. 글자크기정하기

* 입력
```
# 제목1  
## 제목2  
### 제목3  
#### 제목4  
##### 제목5  
###### 제목6  
```
* 출력
-----
# 제목1  
## 제목2  
### 제목3  
#### 제목4  
##### 제목5  
###### 제목6 
-----

# 2. 목록(들여쓰기)

    (1) 순서가 있는 목록  
※ 들여쓰기는 스페이스 4번  
※ 숫자는 반드시 1,2,3 순서로 갈 필요가 없음.  
* 입력
```
1. 제목1  
2. 제목2  
    1. 제목(1)  
    1. 제목(2)  
3. 제목3
    1. 제목(1)
    1. 제목(2)  
        1. 제목((1))  
        2. 제목((2))    
```
* 출력
---
1. 제목1  
1. 제목2  
    1. 제목(1)  
    2. 제목(2)  
1. 제목3  
    1. 제목(1)  
    1. 제목(2)  
        1. 제목((1))  
        1. 제목((2))  
---


    (2) 순서가 없는 목록  
※ 들여쓰기는 스페이스 4번  
※ "+","*","-" 모두가능
* 입력
```
- 제목1  
- 제목2  
    - 제목(1)  
    - 제목(2)  
- 제목3
    + 제목(1)
    - 제목(2)  
        * 제목((1))  
        - 제목((2))    
```
* 출력
---
- 제목1  
- 제목2  
    - 제목(1)  
    - 제목(2)  
- 제목3
    - 제목(1)
    - 제목(2)  
        - 제목((1))  
        - 제목((2))  
---

# 3. 코드블럭
* 입력
```
　``` c  
  int num=10;  
　```
```


* 출력
``` c
int num=10;
for (int i; i<10; i++) {
    cout<<i<<endl;
}
```

# 4. 폰트
* 입력
```
**굵게**
*기울여쓰기*
~취소선~
```

* 입력  
**굵게**  
*기울여쓰기*  
~취소선~  
