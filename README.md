# 더치페이하는 우리사이 'N빵'

기획의도 :
디자인 컨셉 : 
<hr>

sass활용
1. global에 변수를 선언한 경우 partitial했던 scss파일에 변수가 정의되지 않았다고 나온다.
- 솔루션 : 변수만 모아둔 partitial파일을 따로 만든 후, 각 partitial파일마다 import한다. (variables)

2. 파일명을 sass가 아니라, scss로 파일로 만든 후 해당 파일에서 작업 후 -> sass로 컴파일 한다.
- sass로 작업해도 괜찮으나, css와 조금 더 친숙한 scss로 작업하는 것이 좋다.(sass로 작업시 중괄호의 유무 등이 헷갈린다.)

3. 부모의 참조가 필요한 경우 `&`를 사용하면 되는데, 이때 부모의 블록레벨 내부에 있어야 한다. (e.g  &:hover)