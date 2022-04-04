### 미션 내용 : 로또 번호 추출기 구현

- 사용자가 웹사이트에 접속하여 ‘로또 번호 추출하기’ 버튼을 클릭 시 [1, 5, 30, 21, 20, 40, 45] 형태의 로또번호가 출력

### 입력

- 없음

### 출력

- 로또번호 7자리
- 출력 화면

### 만든 결과
![ezgif com-gif-maker](https://user-images.githubusercontent.com/67627129/161563272-22d08071-4ce2-4b2f-8882-5c3bd450c7a0.gif)

### 특이사항

- (힌트) 번호 추출 시 `random` 패키지 활용
    - 공식문서 : [https://docs.python.org/ko/3/library/random.html](https://docs.python.org/ko/3/library/random.html)
    - `random.randint(1,45)`
    - `random.sample(list,7)`

- "힌트"와 View.py Code가 다름
    - 'random.sample(list,7)' 사용하지 않음
