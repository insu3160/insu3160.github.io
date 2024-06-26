---
layout: "single"
title:  "마크다운 문법 알아보기"
excerpt : "마크다운"
toc : true
toc_label : "목차"
toc_sticky : true

categories:
  - Etc
---
# 마크다운(Markdown) 그게 뭔데?

## 개요

>블로그를 쓰고 싶은데 어떻게 써야할 지 막막하다. 뭐부터 쓰는 게 좋을까? 하다 떠오른 마크다운 문법! 그래서 마크다운이 뭔데?


## 마크다운(Markdown)이란?

>텍스트 기반의 마크업 언어, 온갖 태그로 범벅된 HTML 문서와 달리 읽기도 쓰기도 쉬운 문서 양식을 지향하는 것 요즘 보기 쉬운 README.md 또한 .md 확장자 파일로 마크다운 문법을 활용한 문서. 


# 마크다운(Markdown) 문법

## 1. 헤더
```
# 제목1 - h1  
## 제목2 - h2  
### 제목3 - h3  
#### 제목4 - h4  
##### 제목5 - h5  
###### 제목6 - h6
``` 
+ ### 헤더 출력 결과
   + <h1> 제목1 - h1 </h1>
   + <h2>제목2 - h2 </h2>
   + <h3>제목3 - h3 </h3>
   + <h4> 제목4 - h4 </h4>
   + <h5> 제목5 - h5 </h5> 
   + <h6> 제목6 - h6 </h6>

-----------------------
## 2. 코드 블록
    ```   
    이건 코드 블록입니다.  
    ```

+ ### 코드 블록 출력 결과
  ```
  이건 코드 블록입니다.
  ```
  **\```대신 \~~~물결과 스페이스 4번**을 사용해도 가능.

----------------------
## 3. 글씨 강조
```
이건 \*\*굵은 글씨\*\*입니다.  
이건 \*기울어진 글씨*입니다.  
이건 \*\*\*기울어진 굵은 글씨\*\*\*입니다.  
이건 \~~줄그어진 글씨\~~입니다.
```
+ ### 굵은 글씨 출력 결과
   + 이건 **굵은 글씨**입니다.  
   + **\**대신 \__언더바 두 개**를 사용해도 가능.

+  ### 기울어진 글씨 출력 결과
   + 이건 *기울어진 글씨*입니다.  
   + **\*대신 \_언더바 한 개**를 사용해도 가능.

+ ### 기울어진 굵은 글씨 출력 결과
   + 이건 ***기울어진 굵은 글씨***입니다.  
   + **\*대신 \_언더바**를 사용해도 가능.

+ ### 줄 그어진 글씨 출력 결과
   + 이건 ~~줄 그어진 글씨~~입니다.  

------
## 4. 인용문
```
> 인용문1
>> 중첩 인용문2
```

+ ### 인용문 출력 결과
> 인용문1
>> 중첩 인용문2
-----

## 5. 수평선
```
---
```
+ ### 수평선 출력 결과
    + -와 _와 *중 하나를 3개 이상 입력 시 아래와 같이 수평선이 생성.

---

## 6. 목록
```
1. 순서 목록1
1. 순서 목록2
    1. 순서 목록2-1
    1. 순서 목록2-2
1. 순서 목록3

+ 순서 없는 목록1
+ 순서 없는 목록2
    + 순서 없는 목록2-1
    + 순서 없는 목록2-2
+ 순서 없는 목록3
```
+ ### 순서 있는 목록 출력 결과
1. 순서 목록1
1. 순서 목록2
    1. 순서 목록2-1
    1. 순서 목록2-2
1. 순서 목록3  

+ ### 순서 없는 목록 출력 결과
+ 순서 없는 목록1
+ 순서 없는 목록2
    + 순서 없는 목록2-1
    + 순서 없는 목록2-2
+ 순서 없는 목록3
+ *와 +와 -중 어떤 것을 입력해도 가능.

---

## 7. 링크
```
[이름](링크 주소)
[깃허브](https://github.com/) //이름으로 링크 사용
깃허브 : <https://github.com/> //링크로 링크 사용
```
+ ### 링크 출력 결과 
  + [깃허브](https://github.com/)  
  + 깃허브 : <https://github.com/>
---

## 8. 이미지
```
![이미지에 대한 텍스트](../../images/cat.jpg)
```
+ ### 이미지 출력 결과
![이미지에 대한 텍스트](../../images/cat.jpg)

## 9. 체크 박스
```
[ ] 난 아직 체크 안됨
[X] 난 체크 됨
```
+ ### 체크 박스 출력 결과
  + [ ] 난 아직 체크 안됨
  + [X] 난 체크 됨

# 마무리
마크다운 문법에서 사용되는 기호를 직접 사용하고 싶을 경우는 \를 이용해 보세요!
앞으로 마크다운 문법을 이용한 즐거운 포스팅 생활 시작해보겠습니다. 