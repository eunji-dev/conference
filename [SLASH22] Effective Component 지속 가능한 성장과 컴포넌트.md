# [SLASH22] Effective Component : 지속 가능한 성장과 컴포넌트

> https://youtu.be/fR8tsJ2r7Eg

<br>

## 소감

```
하위의 컴포넌트를 props로 보내는 방식으로 리팩토링하는것이 인상적이었다.
```

<br>

## Action Item

```
- 인터페이스 먼저 고민하기
```

<br>

## 회고

```
컴포넌트를 props로 넘기는 방식을 좀 더 잘 활용하면 좋을거같다.

컴포넌트를 props로 넘기는 방식을 사용해서 리팩토링을 해봤는데 props drilling이 줄어 들었고 조건에 따라 컴포넌트를 보여줄때도 코드가 좀 더 깔끔해진것 같다.

그리고 변경에 좀 더 유연한 컴포넌트를 만들 수 있게 된 것 같다.
```

<br>

---

<br>

## 내용정리

<br>

> Headless 기반 추상화 <br>
> 한가지 역할만 하는 컴포넌트 <br>
> 도메인 포함/미포함 분리

<br>

새로운 니즈 발견 => 변경<br>
변경을 예측하는것이 아니라 대응한다.<br>
작은 컴포넌트 합치기 => 많아지면 기능 분리

<br>

### 컴포넌트의 역할

1. 데이터 관리
2. 데이터 보여주기 (ui)
3. 사용자와의 상호작용

<br>

### 컴포넌트를 분리하기 전 생각해볼것!

-> 실제 복잡도를 낮추는지<br>
-> 재사용 가능한지<br>
-> 꼭 분리해야하는지 고민
