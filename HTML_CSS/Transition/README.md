# 1.Transition 정의

-`transition`은 css속성의 전환효과를 지정한다. 

# 1-1.Transition 방법
값으로 시간과 transition-timing-function을 같이 쓸 수 있다. 초를 2s 3s라 적으면 2s는 duration이고, 3s는 delay라고 인식한다.


---
# 1-2.Transition 도식표
|transition 값|의미|기본값|
|---|:---:|---:|
|transition-property|전환효과를 사용 할 속성 이름|all|
|transition-duration|전환효과의 지속시간 설정|0s|
|transition-timing-function|타이밍 함수 지정|ease|
|transition-delay|전환효과의 대기시간 설정|0s|

---
# 1-3.Transition-Timing-Function 도식표
|값|의미|cubic bezier 값|
|---|:---:|---:|
|ease|빠르게-느리게|cubic-bezier(n, n, n, n)|
|linear|일정하게|cubic-bezier(n, n, n, n)|
|ease-in|느리게-빠르게|cubic-bezier(n, n, n, n)|
|ease-out|빠르게-느리게|cubic-bezier(n, n, n, n)|'
|ease-in-out|느리게-빠르게-느리게|cubic-bezier(n, n, n, n)
|cubic-bezier(n,n,n,n)|자신만의 값을 정의(0~1)
|steps(n)|n번 분할 된 애니메이션|
# 2.Transform 정의
`transform`은 요소의 변환효과(변환)를 지정 한다.

# 2-1.Transform 방법
 2D 변환함수와 3D 변환함수 종류로 translate, scale, rotate, skew, matrix 등으로 사용 할 수 있다.

# 2-2. Transform 변환속성 도식표
|속성|의미|
|---|---:|
|transform-origin|요소변환의 기준점 설정|
|transform-style|3D변환요소의 자식요소도 3D 변환을 사용할지 설정|
|perspective|하위요소를 관찰하는 원근 거리를 설정|
|perspective-origin|원근 거리의 기준점을 설정|
|backface-visibility|3D 변환으로 회전된 요소의 뒷면 숨김을 설정|

# 2-3. Transform-origin 도식표
|값|의미|기본값|
|---|:---:|---:|
|X축|left, right, center, %, 단위|50%|
|Y축|top, bottom, center, %, 단위|50%|
|Z축|단위|0|

# 2-4. Transform-style 도식표
|값|의미|기본값|
|---|:---:|---:|
|flat|자식 요소의 3D 변환 사용안 함|
|preserve-3d|자식 요소의 3D 변환을 사용함|

# 2-5. perspective 도식표
|값|의미|기본값|
|---|:---:|---:|
|단위|px, em, cm 등 단위로 지정|

# 2-6. perspective-origin 도식표
|값|의미|기본값|
|---|:---:|---:|
|X축|left, right, center, %, 단위|50%|
|Y축|top, bottom, center, %, 단위|50%|

# 2-7. backface-visibility 도식표
|값|의미|기본값|
|---|:---:|---:|
|visible|뒷면숨기지않음|visible|
|hidden|뒷면숨김|
