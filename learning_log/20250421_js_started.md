# 입실 체크 해주세요!! 😀

20250421 -> 20250421_js_started.md 파일로 변경

# JavaScript

## 실습 환경 구축하기
1. window + 기본 이라고 검색 -> 기본앱 -> 웹브라우저를 크롬으로
2. js_sql_study에서 새 폴더 -> js_study 생성
3. ch01 폴더 생성
4. 새 파일 -> index.html 생성
5. live server 실행
6. ctrl + shift + i -> 개발자도구를 켭니다.

### Hello, JavaScript
- console창에 출력하는 명령어
```js
console.log('Hello, JavaScript');
```

## Console과 주석 사용하기
### 콘솔
- 최종 사용자가 아닌 개발자를 위한 메시지 출력을 목적으로, 주로 개발 도중에 중간 결과를 확인하고, 디버깅을 위해 사용되는 영역.

```java
System.out.println(1  2  3);
System.out.print(1);
System.out.print(" ");
System.out.print(2);
System.out.print(" ");
System.out.print(3);
// 결과값이 1 2 3 -> 근데 자료형이 int여야해
```
Java에서는 %d을 사용하지 않으면 저렇게 작성해야하는 데 반해서,
```js
console.log(1, 2, 3); // 결과값 : 1 2 3 -> 자료형은 number
```
즉 콘솔 기능의 장점은 괄호 내에 쉼표(,)를 이용하여 여러 데이터를 한 번에 출력 가능하다는 점입니다.
### 주석(Comment)
- 모든 프로그래밍 언어에서 활용하는 개념으로, 컴퓨터가 무시하는 메시지.
- // : JavaScript에서의 주석 방법
- /**/ : 다중 주석
- ctrl + / : 일단 코드 써놓고 사후 주석처리 방법