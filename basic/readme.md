### 미션 내용 : 로또 번호 추출기 구현

- 사용자가 웹사이트에 접속하여 ‘로또 번호 추출하기’ 버튼을 클릭 시 [1, 5, 30, 21, 20, 40, 45] 형태의 로또번호가 출력

### 목표

- 장고의 디자인패턴 및 흐름에 대한 이해 `urls.py` → `views.py` → `template`→ `views.py`
- 파이썬 구현 능력 향상

### 입력

- 없음

### 출력

- 로또번호 7자리
- 출력 화면


### 가이드

- 기존 `first-django` 프로젝트의 `demo` 앱의 `views.py`에 로또 번호 추출 요청을 처리할 수 있는 함수를 작성
- [`urls.py`](http://urls.py) 새 URL 패턴 추가
- [`views.py`](http://views.py) 로또번호 요청 URL 처리 함수 작성

### 힌트

- 번호 추출 시 `random` 패키지 활용
    - 공식문서 : [https://docs.python.org/ko/3/library/random.html](https://docs.python.org/ko/3/library/random.html)
    - `random.randint(1,45)`
    - `random.sample(list,7)`
