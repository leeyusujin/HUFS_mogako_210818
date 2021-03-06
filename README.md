### HUFS_mogako_210818
----


#### 활동 내용


신찬수교수님의 방학 알고리즘 구름강의에서 Dynamic Programming 파트를 공부해보았다. 원래는 힙정렬 부분을 공부할 예정이었지만 지난 1학기때 자료구조에서 배운 내용과 유사하고 약간의 변화만 주는 것이 힙정렬파트의 내용이었다. 그래서 일단은 혼자 따로 공부할 사람은 공부하고 모각코 활동을 할 때는 건너뛰고 DP, Dynamic Programming파트로 바로 들어가기로 하였다. 교수님의 강의 중 DP가 무엇인지 개념설명하는 강의와 최대 구간의 합을 계산하는 것에 대한 강의와 실습까지 공부하였고 행렬곱셈문제는 다음에 수강하기로 하였다. 


먼저 DP는 동적 계획법으로, 문제를 여러가지로 작게 나누어 재귀적으로 해결하는 방법이다. 즉 큰 문제의 해답이 작은 문제들의 해답들로 만든 식으로 표현되는 것으로, 이 답들은 필요할 때 마다 재귀적으로 얻는 것이 아닌 기록해놓았던 값을 재귀 식에 따라 계산하는 것이다. 교수님께서 설명하며 사용하신 예시로 피보나치수를 계산하는 방법이 있다. 피보나치는 이전의 두 수를 더하면 다음 수가 되는 수로 하나의 수를 구하기 위해 적어도 두 개의 수를 구해야 한다. F(n-2)와 F(n-1)을 구해야 F(n)을 구할 수 있는 것이다. 우리가 흔히 아는 DC는 F(n-2)와 F(n-1)는 함수를 재귀 호출하여 그 둘의 합을 계산하여 구하는 방법이다. DP는 F(n-2)와 F(n-1)의 답을 미리 계산하여 저장한 후에 F(n) = F(n-2) + F(n-1) 이라는 식을 계산하여 구하는 방법이다. 즉, 구하고자하는 문제의 답을 작은 문제들로 쪼개어 그 문제들의 재귀 식으로 표현하는 것이 가장 중요하다. 


----
##### 느낀점


활동 바로 직전까지 팀원들 모두 바빴던 하루였다. 그래서 다들 활동 시작하기 바로 직전에 부랴부랴 모여서 정신도 없었지만 그래서인지 다들 더 열심히 임한 하루였던 것 같다. 이때까지 파이썬을 배우거나 다른 언어를 배우면서 한 번씩 고비가 있었다. 포인터, 전역변수 등이었는데 오늘 배운 DP도 나한테는 약간 이해하는데에 시간이 필요한 내용이었다. 개념적으로는 문제가 없지만 실습 문제를 풀려고 도전했을 때 어떻게 접근을 해야 좋을지 몰라서 이 내용은 조금 더 공부를 해야겠다는 생각이 들었다.
