# 파이썬 기초
---
+ 데이터(data) : 이론을 세우는데 기초가 되는 사실, 또는 바탕이 되는 자료
+ 정보(information) : 데이터를 가공하지 않은 경우, 이를 위한 기초적인 자료가 데이터
+ 단순구조 : 정수, 실수, 문자(숫자이외의 정보를 표현하는 방법), 문자열(둘 이상의 문자의 결합)등
+ 인코딩 : 문자를 컴퓨터가 이해할 수 있는 숫자로 변환(아스키 코드)
+ 데이터 타입 : 데이터의 형태, 의미, 크기와 해당 자료형의 값이 저장되는 방식
<br/> 문자(character) ex) "A", "Hello"
<br/> 유리수(numeric) ex) 10, 20, 1.178
<br/> 정수(integer) ex) 5, 10, 2
<br/> 논리값(logical) ex) TRUE, FALSE

+ 코드 : 설명
<br/>\n : 문자열 안에서 줄을 바꿀 때 사용
<br/>\t : 문자열 사이에 탭 간격을 줄 때 사용
<br/>\\\ : 문자 \를 그대로 표현할 때 사용
<br/>\\' : 작은따옴표(')를 그대로 표현할 때 사용
<br/>\\" : 큰따옴표(")를 그대로 표현할 때 사용

![image](https://github.com/user-attachments/assets/3c96eddd-352e-4430-a249-479919cae083)

#### 스칼라의 개념
+ 스칼라 : 일반적으로 숫자(예: 정수 또는 부동 소수점), 문자, Bool 또는 컬렉션이 아닌 기타 값(예: 목록 또는 부동 소수점)이 될 수 있는 단일 값을 나타냄
#### 리스트의 개념
+ 선형구조-리스트
<br/> 데이터 유형을 저장하고, 저장된 데이터들을 그룹화할 수 있는 데이터 구조
<br/> 숫자, 문자, 논리값... 등등 다양한 데이터 유형의 요소가 포함될 수 있음
+ 튜플 : 불변성(한 번 생성되면 해당 요소를 추가, 제거 또는 변경할 수 없음)은 특정 상황에서 여러가지 효율성과 이점을 제공함
#### 배열의 개념
+ 프로그램에서의 벡터
<br/> 값을 저장하고 조작할 수 있는 기본 데이터 구조
<br/> 숫자, 문자 또는 논리 값과 같은 동일한 데이터 유형의 요소를 보유할 수 있는 1차원 배열
<br/> Python의 벡터는 [요소1, 요소2, 요소3,....]로 표현할 수 있음
+ List(리스트)
<br/> 자료를 순서대로 한 줄로 저장하는 자료구조
<br/> 여러 자료가 일직선으로 서로 연결된 선형 구조(리스트에 있는 데이터는 몇 번째 인지 의미를 가짐)
+ Array(배열)
<br/> 단일 타입으로 구성되는 자료구조
+ 대규모 다차원 배열
<br/> 데이터의 대부분은 숫자 배열로 볼 수 있음
<br/> 흑백 이미지는 픽셀의 밝기와 명함을 2차원 배열로 표현할 수 있고 소리 같은 경우는 1차원 배열로 나타낼 수 있음
+ List(리스트)와 Array(배열)
<br/> List는 [1,2,"kim",2.5,True,False]와 같은 실수형, 정수형, 문자형과 같은 다양하게 관계없이 구성이 가능함
<br/> array는 모두 단일 타입으로 구성됨

