힙 자료구조
(Heap data structure)
======================
  
__힙(Heap)__ 자료구조를 구현한 __C++ 코드__ 입니다.  
소스파일은 _main.cpp_, _heap.h_, _heap.cpp_ 의 세 가지로 구성되어 있습니다.  
아래는 각 소스파일에 대한 내용입니다.  
  
  
  
main.cpp  
--------------------
main 함수가 존재합니다. Heap 클래스를 활용한 여러가지 예시들을 보여주고 있습니다.
  
  

heap.h 
------------------- 
Heap 클래스에 대한 정의 및 멤버 함수들에 대한 정의가 존재합니다. 
 
Heap 클래스의 멤버 변수로는 노드를 담고있는 배열(array), 전체 노드 갯수(size), 배열의 크기(capacity), 그리고 최대/최소 힙 여부(isMax)에 대한 정보가 존재합니다. 
Node 클래스의 멤버 함수로는 힙에 대한 정보를 반환하는 함수들 및 기본적인 기능에 대한 함수들이 존재합니다.
 
자세한 내용은 주석에 명시되어 있습니다. 
 
 
  
heap.cpp
-------------------
Heap 클래스 내부의 멤버 함수들에 대한 정의가 존재합니다. 
 
힙에 대한 정보를 반환하는 함수로는 다음과 같은 것들이 있습니다: 
노드 개수 반환, 깊이 반환, 최대/최소힙 여부 반환
 
기본적인 기능에 대한 함수로는 다음과 같은 것들이 있습니다: 
생성자, 파괴자, 삽입, 삭제, n번째 노드의 값 반환, v값에 대한 번호 반환, 출력
 
 