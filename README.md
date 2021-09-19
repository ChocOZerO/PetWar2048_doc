# PetWar2048

## 기획초안

### 게임 진행
- 2048게임을 모티브로 한 캐쥬얼 게임
- 기본적인 컨셉은 2048과 동일
- 8x8을 기본맵으로 구성
- 게임 중간에 랜덤으로 발생하는 장애물 칸이 있음
- 블록은 한번에 한개씩 발생(숫자 혹은 장애물)
- 스와이프를 통해 합쳐지면서 부딪히면 장애물이 사라짐
- 강아지 진영과 고양이 진영 선택 가능

### 디자인 초안
- [와이어 프레임](https://www.figma.com/file/wLV5f6His2uGQ831Eue7uu/Untitled?node-id=0%3A1)

### 재미 포인트
- 고양이 vs 강아지 콘텐츠
- 숫자 블록과 장애물 블럭이 사라지는 통쾌감
- 숫자를 증식시키려는 두뇌활용

### 고려사항
- 게임 종료 점수를 진영 점수에 포함
- 장애물 비율은 10%의 랜덤 확률 -> 확률 조정 가능
- 진영은 전세계 유저 대상(서버 관리 필요) -> 제거 가능성

### 실패조건
- 블록이 더이상 발생할 수 있는 칸이 없다면 실패

### 개발 공부 해야할 부분
- 퍼즐 배열 배치
- 랜덤 블록 발생 알고리즘
- 상하좌우 네 방향 스와이프 액션
- 스와이프 액션에 따라 퍼즐들이 이동하는 부분
- 합쳐지면서 연산하는 알고리즘
- 각각의 애니메이션 처리
