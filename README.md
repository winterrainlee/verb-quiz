# 중간고사 영어 학습 자료

고등학교 영어 중간고사 대비용 모바일 학습 자료 모음입니다.

현재 저장소에는 두 가지 주요 화면이 있습니다.

- `index.html`
  시작 화면
  `4회차 수업 자료`와 `전체 단어장`으로 이동할 수 있습니다.
- `midterm/data/school/08_인터랙티브_학습자료.html`
  1회차~4회차 인터랙티브 수업 자료

## 구성

### 1. 4회차 인터랙티브 학습자료

대상 파일:
- [midterm/data/school/08_인터랙티브_학습자료.html](midterm/data/school/08_인터랙티브_학습자료.html)

포함 내용:
- 1회차 경제
- 2회차 심리·사회
- 3회차 심리
- 4회차 사회·인문
- 단어장 탭

기능:
- 모바일 세로 화면 중심 UI
- `수업 / 퀴즈` 분리
- 단어 카드 뒤집기
- 핵심 단어 / 보너스 단어 / 독해 10문장
- 미니 테스트 10문제
- 채점 후 `오답만 다시`
- 1~4회차 통합 단어장

### 2. 전체 단어장

대상 파일:
- [index.html](index.html)

포함 내용:
- 학교 단어장 전체
- `Day 1 ~ Day 20`
- 하루당 30개 단어

기능:
- Day 선택
- 영단어 목록 표시
- 처음에는 한국어 뜻 숨김
- 영단어를 누르면 뜻 표시
- 다시 누르면 뜻 숨김

## 자료 파일

주요 원본 자료:
- [midterm/data/school/학교-단어장.md](midterm/data/school/학교-단어장.md)
- [midterm/data/school/02_올림포스_지문_분류.md](midterm/data/school/02_올림포스_지문_분류.md)
- [midterm/data/example_learning_material.md](midterm/data/example_learning_material.md)

생성된 수업 자료:
- [midterm/data/school/03_중간고사_4회수업_단어계획.md](midterm/data/school/03_중간고사_4회수업_단어계획.md)
- [midterm/data/school/04_1회차_경제_학습자료.md](midterm/data/school/04_1회차_경제_학습자료.md)
- [midterm/data/school/05_2회차_심리사회_학습자료.md](midterm/data/school/05_2회차_심리사회_학습자료.md)
- [midterm/data/school/06_3회차_심리_학습자료.md](midterm/data/school/06_3회차_심리_학습자료.md)
- [midterm/data/school/07_4회차_사회인문_학습자료.md](midterm/data/school/07_4회차_사회인문_학습자료.md)

## 사용 방법

로컬에서 바로 실행:

1. `index.html`을 브라우저에서 엽니다.
2. 원하는 모드를 고릅니다.
3. `학습 시작하기` 또는 `전체 단어장`으로 들어갑니다.

정적 HTML 기반이라 별도 설치 없이 바로 열 수 있습니다.

## 기술 구성

- HTML
- CSS
- JavaScript
- 외부 의존성 없음

## 메모

- 모바일 화면 비율을 우선해서 디자인했습니다.
- 단어 줄바꿈 시 단어가 중간에서 잘리지 않도록 설정했습니다.
