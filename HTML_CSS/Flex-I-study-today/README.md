# 1. Flex 정의
`Flex`는 요소의 크기가 불분명하거나 동적인 경우에도, 각 요소를 정렬할 수 있는 효율적인 방법을 제공한다.

## 1-1. Flex 개념
Flex는 2개의 개념으로 나뉜다. 첫 번째는 Container, 두 번째는 Items이다. Container는 items를 감싸는 부모이며, 각 Item을 정렬하기 위해선 Container가 필수이다. 

## 1-2. 주축과 교차 축 개념
값 row는 Items를 수평축으로 표시하므로 이때는 `주축`이 `수평`이며 교차 축은 수직이 됩니다. 즉, 방향에 따라 `주축`과 `교차` 축이 달라진다. 

## 1-3. 시작점과 끝점 개념
주축이나 교차 축의 시작하는 지점과 끝나는 지점을 지칭하고 방향에 따라 `시작점`과 `끝점`이 달라집니다.

## 1-4. `Flex Container` 속성 도식표
|속성|의미|
|---|---:|
|display|Flex Container 정의|
|flex-flow|flex-direction과 flex-wrap의 단축속성|
|flex-direction|flex items의 주축을 설정|
|flex-wrap|flex items의 여러 줄 묶음 설정|
|justify-content|주축의 정렬 방법을 설정|
|align-content|교차 축의 정렬 방법을 설정(2줄 이상)|
|align-items|교차 축에서 items의 정렬 방법을 설정(1줄)|

## 1-5. `Flex Items` 속성 도식표
|속성|의미|
|---|---:|
|order|flex item의 순서를 설정|
|flex|flex-grow, flex-shrink, flex-basis의 단축 속성|
|flex-grow|flex item의 증가 너비 비율을 설정|
|flex-shrink|flex item의 감소 너비 비율을 설정|
|flex-basis|flex item의 기본 너비 설정|
|align-self|교차 축에서 item의 정렬 방법을 설정|

---