# 11강 - 모듈(Module)

## 1. 모듈(Module) ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

### 정의
> 재사용 가능한 함수, 상수, 클래스의 집합

---

## 핵심 개념

```text
재사용을 극대화하기 위한 도구
```

---

## 특징
- 코드 재사용 가능
- 유지보수 편리
- 기능 확장 가능
- 공통 기능 공유 가능

---

# 2. 활자 인쇄와 모듈 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐

### 핵심 인물
- Johannes Gutenberg

---

## 핵심 개념

기존:
- 책 한 페이지 전체를 조각

문제:
- 재사용 불가능

---

## 해결
- 활자(Movable Type)

---

## 프로그래밍 의미
> 작은 기능 단위 재사용

---

# 3. 재사용(Reusability) ⭐⭐⭐ 매우 중요

### 중요도
⭐⭐⭐⭐⭐

### 핵심
> 한 번 만든 기능을 여러 프로그램에서 사용

---

# 4. 라이브러리(Library) ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

### 정의
> 여러 기능들을 모아놓은 도구 집합

---

## 특징
- 추가 기능 제공
- 개발 속도 증가
- 코드량 감소

---

## 예시 분야
- AI
- 데이터 분석
- 이미지 처리
- 과학기술 계산

---

# 5. 프레임워크(Framework) ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐

### 정의
> 개발 구조를 미리 만들어 놓은 틀

---

## 특징
- 개발 속도 향상
- 구조 표준화
- 복잡성 감소

---

# 6. 모듈 구조 ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

| 구조 | 의미 |
|---|---|
| Module | 가장 작은 단위 |
| Package | 모듈 집합 |
| Library | 패키지 집합 |

---

# 7. 모듈(Module) 구성 요소 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

### 포함 요소
- 함수(Function)
- 변수(Variable)
- 상수(Constant)
- 클래스(Class)

---

# 8. import ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

## 기본 형식

```python
import module
```

---

## 의미
> 모듈을 현재 프로그램으로 불러오기

---

# 9. import as ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐

## 형식

```python
import module as 별칭
```

---

## 예시

```python
import math as m
```

---

## 장점
- 코드 짧아짐
- 사용 편리

---

# 10. from import ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

## 형식

```python
from module import member
```

---

## 특징
- 특정 기능만 가져옴
- 메모리 효율 증가

---

## 예시

```python
from math import pi
```

---

# 11. from import * ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 형식

```python
from module import *
```

---

## 특징
- 모듈 전체 멤버 사용 가능
- 모듈명 생략 가능

---

# 12. namespace ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

### 정의
> 이름(식별자)을 관리하는 공간

---

## 포함 대상
- 변수
- 함수
- 클래스

---

# 13. namespace 탐색 순서 ⭐⭐⭐ 매우 중요

### 중요도
⭐⭐⭐⭐⭐

## 탐색 순서

```text
지역(Local)
↓
전역(Global)
↓
Built-in
```

---

## 시험 포인트
- 가까운 namespace 우선 탐색

---

# 14. 지역 namespace(Local Namespace)

### 중요도
⭐⭐⭐⭐⭐

### 의미
- 함수 내부
- 클래스 내부

---

# 15. 전역 namespace(Global Namespace)

### 중요도
⭐⭐⭐⭐⭐

### 의미
> 현재 모듈 전체 영역

---

# 16. Built-in namespace ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐

### 의미
> Python 기본 내장 영역

---

# 17. dir() ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

## 기능
> 등록된 모듈 및 멤버 확인

---

## 사용

```python
dir()
```

---

## 모듈 내부 확인

```python
dir(math)
```

---

# 18. help() ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 기능
> 사용법 출력

---

## 예시

```python
help(math.sin)
```

---

# 19. del ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 기능
> 객체/모듈 삭제

---

## 예시

```python
del module
```

---

# 20. 모듈 reload ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐

## 사용 모듈

```python
importlib
```

---

## 기능
> 수정된 모듈 다시 불러오기

---

## 예시

```python
importlib.reload(module)
```

---

# 21. math 모듈 ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

### 정의
> 수학 계산용 모듈

---

# 22. math 상수 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

---

## pi

```python
math.pi
```

---

## e

```python
math.e
```

---

# 23. math 주요 함수 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

| 함수 | 의미 |
|---|---|
| sqrt() | 제곱근 |
| ceil() | 올림 |
| floor() | 내림 |
| fabs() | 절댓값 |
| gcd() | 최대공약수 |

---

# 24. 삼각함수 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐

---

## sin()

```python
math.sin()
```

---

## cos()

```python
math.cos()
```

---

## tan()

```python
math.tan()
```

---

# 25. radians() ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 기능
> 도(degree) → 라디안 변환

---

## 예시

```python
math.radians(60)
```

---

# 26. Random 모듈 ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

### 기능
> 난수(Random Number) 생성

---

# 27. 난수(Random Number) ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

### 정의
> 규칙 없는 임의의 수

---

# 28. Seed ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

### 정의
> 난수 생성 시작값

---

## 특징

| 특징 | 의미 |
|---|---|
| Seed 동일 | 같은 난수 생성 |
| Seed 변경 | 다른 난수 생성 |

---

# 29. randint() ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 기능
> 특정 범위 정수 생성

---

## 예시

```python
random.randint(1, 6)
```

---

# 30. choice() ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 기능
> 시퀀스에서 하나 선택

---

## 예시

```python
random.choice(list)
```

---

# 31. sample() ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

## 기능
> 중복 없이 여러 개 선택

---

## 예시

```python
random.sample(range(1,46), 6)
```

---

# 32. shuffle() ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐

## 기능
> 리스트 섞기

---

# 33. Time 모듈 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

### 기능
> 시간 관련 처리

---

# 34. Unix Epoch ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

### 기준 시간

```text
1970년 1월 1일
```

---

# 35. time() ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 기능
> 현재 시간 반환

---

## 예시

```python
time.time()
```

---

# 36. localtime() ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐

## 기능
> 현재 지역 시간 반환

---

# 37. strftime() ⭐⭐⭐ 시험 핵심

### 중요도
⭐⭐⭐⭐⭐

## 기능
> 시간 형식 지정 출력

---

## 예시

```python
time.strftime("%Y-%m-%d")
```

---

# 38. sleep() ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 기능
> 프로그램 일시 정지

---

## 예시

```python
time.sleep(5)
```

### 의미
- 5초 정지

---

# 39. 가위바위보 프로그램 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐

## 핵심 사용 함수

```python
random.choice()
```

---

# 40. 로또 프로그램 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 핵심 사용 함수

```python
random.sample()
```

---

# 41. 20고개 프로그램 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐

## 핵심 개념
- 랜덤 숫자 생성
- 반복문
- 조건문

---

# 42. 소수 판별 프로그램 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 핵심 개념
- 반복문
- 시간 측정
- 성능 테스트

---

# 43. 프로그램 성능 측정 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 핵심
> 실행 시간 측정 가능

---

# 44. Python의 장점 ⭐⭐⭐ 중요

### 중요도
⭐⭐⭐⭐⭐

## 핵심
- 라이브러리 풍부
- 코드 짧음
- 개발 속도 빠름

---

# 45. 시험 직전 암기 TOP 45

1. Module
2. 재사용
3. Library
4. Framework
5. Package
6. import
7. import as
8. from import
9. namespace
10. Local Namespace
11. Global Namespace
12. Built-in Namespace
13. dir()
14. help()
15. del
16. reload
17. math module
18. pi
19. e
20. gcd()
21. sqrt()
22. sin()
23. radians()
24. Random module
25. Random Number
26. Seed
27. randint()
28. choice()
29. sample()
30. shuffle()
31. Time module
32. Unix Epoch
33. time()
34. localtime()
35. strftime()
36. sleep()
37. 가위바위보
38. 로또 프로그램
39. 20고개
40. 소수 판별
41. 성능 측정
42. importlib
43. 함수 재사용
44. 메모리 효율
45. Python 생산성

11강 "모듈" 강의 내용을 기반으로 정리했습니다. :contentReference[oaicite:0]{index=0}
