# 1. Animation 정의
요소에 애니메이션을 설정/제어한다.

# 2. Animation 종류 도식표
|값|의미|기본값|
|---|:---:|---:|
|animation-name|@keyframes 규칙의 이름 지정|none|
|animation-duration|애니메이션의 지속시간 설정|0s|
|animation-timing-function|타이밍 함수 지정|ease|
|animation-delay|애니메이션의 대기시간 설정|0s|
|animation-iteration-count|애니메이션의 반복 횟수 설정|1|
|animation-direction|애니메이션의 반복 방향 설정|normal|
|animation-fill-mode|애니메이션의 전후 상태(위치) 설정|none|
|animation-play-state|애니메이션의 재생과정지 설정|running|

# 3. Animation 종류 각각의 값 도식표


## 3-1. animation-iteration-count
|값|의미|기본값|
|---|:---:|---:|
|숫자|반복 횟수 설정|1|
|infinite|무한반복||

## 3-2. animation-direction
|값|의미|기본값|
|---|:---:|---:|
|normal|정방향만반복|normal|
|reverse| 역방향만반복|
|alternate|정방향에서 역방향으로 반복|
|alternate-reverse|역방향에서 정방향으로 반복|

## 3-3. animation-fill-mode

|값|의미|기본값|
|---|:---:|---:|
|none|기존위치시작점-->애니메이션 시작위치 이동-->동작-->기존위치에서 끝|none|
|forwards|기존위치시작점-->애니메이션 시작위치 이동-->동작-->애니메이션 끝 위치에서 끝|
|backwards|애니메이션 시작위치에서 시작-->동작-->기존위치에서 끝|
|both|애니메이션 시작위치에서 시작-->동작-->애니메이션 끝 위치에서 끝|

## 3-4. animation-play-stats

|값|의미|기본값|
|---|:---:|---:|
|running|애니메이션을 동작|running|
|paused|애니메이션을 동작 정지|

# 4.Multi-columns 정의  
일반 블록 레이아웃을 확장하여 여러 텍스트 다단으로 쉽게 정리하며, 가독성 확보를 한다.

# 5.Columns 종류 도식표
|값|의미|
|---|---:|
|column-count|단의 개수 설정|
|column-width|단의 너비 설정|
|column-rule|선 지정|
|column-gap|단과 단사이의 간격 설정|


