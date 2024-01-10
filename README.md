# Markdown 기초

<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> : vscode 의 명령창 열기

## 문단 
첫번째 문단입니다.
아직도 첫번째 문단이에요.

두번째 문단입니다(한 번 이상만 띄우면 그 다음 문단이 됩니다).

가독성을
위해서
엔터를 한번만 하는 경우는
같은 문단으로 봅니다.

## 제목

# 제목
## 제목
### 제목
#### 제목
##### 제목
###### 제목

*하나만 쓰면* 기울임체

**두개를 쓰면** 볼드체가 됩니다.

***세개를 쓰면*** 볼드 + 기울임체.

~~취소선~~

## 이모지
이모지를 VSCode에서 보려면, 플러그인을 설치해야 합니다.

:kissing: 

## 리스트
순서가 없는 목록은 -*+를 사용합니다.
순서가 있는 목록은 번호.을 사용합니다.

과일 리스트
- 사과
- 배
- 오렌지

채소 리스트
- 토마토
- 상추

중첩된 리스트
- 알고리즘
    - 기본
    - 응용
- 코딩
    - 자바
    - 프론트
        - JavaScript
        - HTML
        - CSS
    - 백엔드
    - DB
    - Spring
    - Vue.js

## 순서가 있는 리스트
1. 사과
2. 배
3. 오렌지
8. 포도

a. 지원
b. 되지
c. 않습니다.

### To do list
- [x] 출근하기
- [ ] 퇴근하기

## 링크 넣기
대괄호, 소괄호 순으로 작성합니다.

[네이버](https://www.naver.com)

[소프트웨어 엑스퍼트 아카데미](https://swexpertacademy.com)

## 이미지 넣기
느낌표, 대괄호, 소괄호 순으로 작성합니다.

대괄호 - alt text: 이미지가 안 보일 때 대신 보여줄 텍스트

소괄호 - 이미지 주소, 경로

![고양이](/img/cat.jpg)
![고양이](/img/cat.jp)
![고양이](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Cat03.jpg/1024px-Cat03.jpg)

## 가로줄

가로줄은


--- 

대시 세개를 사용하여 넣습니다.

## 코드 넣기
백틱 세개를 사용합니다.
```
console.log('hello');
```

syntax highlighting 이용하기
```javascript
console.log('hello');
```

