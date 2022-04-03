# 연습문제 2.5번
코드에서 사용된 적절한 표식을 찾으려면 연습이 필요하다. 이 연습 문제를 통해 코드에서 표식을 사용하는 것을 훈련해보자.

#### 1단계: 코드 선정
잘 알지 못하는 코드베이스를 선택하되 자신이 잘 아는 언어로 된 코드를 선정하기 바란다.
가능하다면 지인이 그 코드베이스르 자세히 알고 있으면 좋다. 그럼 자신이 이해한 것이 맞는지 그 사람을 통해 확인을 받을 수 있다. 이제 선정한 코드베이스에서 메서드나 함수 하나를 선택한다.

답: 아래에 있는 코드로 선정하였다. 함수는 Null_Coalescing()를 선택하였다.
https://github.com/ttu/csharp-tutorial/blob/master/csharp-tutorial/03_Null.cs

#### 2단계: 코드 파악
1단계에서 선택한 메서드나 함수를 파악하고 코드가 하는 일을 요약해보라.

답: Coalescing 뜻 자체적으로 병합하다는 뜻이 있는데, null을 병합하는 함수인거 같다.
문자열을 체크하고, null 일 경우 병합하는 테스트 코드로 구성되어 있다.
Assert.Equal로 문자열 2개의 값이 맞는지 비교까지 한다.

#### 3단계: 사용하는 표식의 적극적 확인
읽는 도중 '아, 그렇구나'라는 생각이 들면서 그 코드의 의미를 좀 더 이해하게 되면 잠시 멈추고 왜 그렇게 생각했는지를 적어보아라. 주석문, 변수명, 메서드명, 임시 저장값 등 어느 것이든 표식이 될 수 있다.

답: 주석문을 통해 좀 더 상세하게 빠르게 이해 할 수 있었고, 메서드명 또한 번역기를 돌리면 금방 뜻을 이해 할 수 있었다.
다만, print1,print2,print3이라고 이름 지은건 좀 그랬다..

#### 4단계: 회고
코드를 충분히 이해하고 표식을 나열했으면 이제 다음 질문들에 대해 답해보자.
- 어떤 표식을 찾았는가?
답: 네, 주석문, 변수명, Assert.Equal
- 찾은 표식들은 코드의 요소인가, 아니면 사람의 언어로 된 정보인가?
답: 코드의 요소도 있고, 사람의 언어도 있다.
- 그 표식들은 무엇에 관해 알려주고 있는가?
답: 코드에 대해 이해할 수 있도록 도와 주고 있다.
- 그 표식들은 코드의 도메인에 대한 지식을 나타내는가?
답: 네
- 그 표식들은 코드의 기능에 대한 지식을 나타내는가?
답: 네

#### 5단계: 코드에 다시 적용 (생략 가능)
항상 그런 것은 아니지만, 어떨 때는 선택한 표식이 개선 가능하거나 확장될 수 있다. 혹은 코드에는 없지만 표식이 더 필요할 수 도 있다. 이때가 바로 코드를 좀 더 풍성하게 만들 수 있는 좋은 기회로, 표식을 새로 추가하거나 기존의 표식을 수정함으로써 그렇게 할 수 있다. 
이 연습 전에는 선택한 코드베이스를 잘 알지 못했지만 이제는 그 코드를 모르는 다른 누군가가 코드를 이해하려고 할 때 어떤 도움이 필요할지 알고 있을 것이다.

답: 생소한건 주석이 달아 있으면 좀 더 파악하기 편하고, 변수명이나 다른 부분을 실생활에서 많이 접하거나 이해하기 쉬운 단어로 이루어져 있으면 이해하기가 빠른거 같습니다. 

#### 6단계: 다른 사람과 비교 (생략 가능)
팀 동료나 친구 중에 표식 활용을 더 잘하고 싶은 사람이 있다면 연습을 함께 해도 된다.
찾은 표식이 어떻게 다른지 확인해보는 것도 흥미로울 것이다. 초급 개발자와 숙력된 개발자 사이에는 큰 차이가 있기 때문에 이 연습을 통해 자신의 프로그래밍 실력이 어는 정도 수준인지 확인해볼 수 있을 것이다.

답: 이건 서로 pr 올린 후에 비교를 해보아야 할 것 같습니다~