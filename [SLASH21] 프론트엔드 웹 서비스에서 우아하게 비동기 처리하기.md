# [SLASH21] 프론트엔드 웹 서비스에서 우아하게 비동기 처리하기

> https://toss.im/slash-21/sessions/3-1

<br>

## 소감

```
성능 개선이란 말이 잘 와닿지 않았었고 뭘 말하는지 모르고 있었는데 성능 개선을 어떤식으로 할 수 있는지 좀 더 이해를 할 수 있었다.

next를 좀 더 공부 해봐야겠다.
```

<br>

## Action Item

```
- errorboundary, suspense 적용할 수 있는 부분 적용해보기
- concurrent mode, useTransition, useDeferredValue 키워드 찾아보기
```

<br>

## 회고

```
액션 아이템을 아직 제대로 실행 못해봄
```

<br>

---

<br>

## 내용정리

<br>

### 좋은코드의 원칙이란?

- 어떤 역할을 하는 함수인지 한번에 알 수 있음
- 성공/실패의 경우를 분리해서 처리 => 함수의 책임이 명확해짐
- 성공하는 경우만 다루고 실패의 경우를 외부에 위임, catch에서 분리해서 사용

<br>

### 사용자 경험 향상 키워드

- Concurrent mode
- UseTransition
- UseDeferredValue
