# C-STL
### swap() : 매개변수 2개를 바꾸는 것

예시: swap(arr[a+i],arr[b-i]);

## \<algorithm\>
  reverse() : 말 그대로 거꾸로 뒤집는 함수, 인자로 start, end를 받음
  
  참고 : https://cplusplus.com/reference/algorithm/reverse/

  
  max_element(), min_element() : 순서가 없는 배열, 벡터, 리스트 등에 있는 데이터에서 사용.
  
  max_element(start,end) = [start,end)범위 중 가장 큰 iterator를 반환
  
  *max_element(start,end) = [start,end)범위 중 가장 큰 value를 반환
  
  fill(start,end,value) : start부터 end전까지 value로 채워 넣겠다는 의미(전체를 특정값으로 채워 넣고 싶을 때 사용함)

## C++ 기본
전역변수의 초기값은 0

for(int e : arr) vs for(int& e : arr)의 차이점

앞의 경우 복사해서 들어가기에 변경 시 원본에 영향이 없고 뒤에껀 주소를 그대로 가져가기에 변경 시 원본에 영향이 있음
