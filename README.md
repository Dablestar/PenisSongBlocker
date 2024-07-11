# P*nisSongBlocker - In Development

## (KR) 크롬 확장기능 - P*nis Song Blocker
### 1. 기획 의도:
####   들으면 오글거리고 ㅈ같은 노래들을 쇼츠에서 스킵하기 위함

### 2. 구조
####   Chrome Extensions를 통해 배포가 가능한 자바스크립트 기반 확장기능

### 3. 구현
####   1) Youtube Shorts에는 사용된 source를 공개하는 음원들이 있음.
####   2) 해당 음원들을 list에 등록(link 복사 붙여넣기를 통한 수동 등록 or extension 기능으로 우클릭 후 리스트 등록)
####   3) 쇼츠 로딩 시 list에 해당 음원이 있을 경우 즉시 skip

### 3-1. 구현 상세 계획
####   1) 쇼츠 재생 시 현재 재생중인 쇼츠의 정보를 가져오는 기능 구현
####   2) 원격으로 스킵하는 기능 구현
####   3) 데이터베이스 구축 기능 구현

### 4. 예상되는 장점
####   1) 좆같은 노래 안들어도 됨
####   2) 정신건강에 좋음

### 5. 예상되는 단점
####   1) 쇼츠 로딩시간이 길어질 것으로 예상됨
####   2) 아무리 싫어도 한번은 들어야함
####   3) 오리지널 오디오로 집어넣은 우덜식 소스의 경우 차단할 수 없음

## (EN) Chrome Extension - P*nis Song Blocker
### 1. Reason of Development
#### I hate some meme songs(Skibidi, Japanese Anime Song, etc..) keep appears in Youtube Shorts.

### 2. What is this?
#### Javascript-based Chrome extension

### 3. How it works?
#### 1) Extract source music URL from Shorts
#### 2) Add on Ban List(banList.txt)
#### 3) Check source music before shots play. If the source is included in banList.txt, It will skip the clip immediately

### 4. Pros
#### 1) Block P*nis Songs
#### 2) Solve mental issues from p*nis songs

### 5. Cons
#### 1) Expected to increase loading time
#### 2) Should listen p*nis music at least one time
#### 3) Cannot block original audio sources(source music which is uploaded by user. Not using a library)
