# 1. 시간복잡도와 공간복잡도

### 시간복잡도란?

시간복잡도를 알기 전에 점근적 표기법에 대해서 알아야합니다. 각각의 언어마다 따로따로 로직을 표현한다면 매우 귀찮은 작업이 될거라고 생각합니다. 이를 해결하기 위해 등장한 내용이 점근적 표기법입니다. 시간복잡도는 점근적 표기법으로 코드의 횟수를 대략적으로 표현하는 방식입니다.

### 빅빅오표기법: O(N)

시간복잡도에서 대표적으로 사용하는 방식은 빅오표기법입니다. O(N)으로 표현하며 수식의 계산에 N번의 연산이 필요하다는 의미입니다. 평균적으로 1억번의 연산에 1초가 소요됩니다. (이를 알고있으면 코딩테스트 준비에 많은 도움이 되겠죠?) 알고리즘별 시간복잡도를 알고있으면 코딩테스트에 들어가기 전에 문제의 시간을 확인한 뒤, 어떤 알고리즘을 사용해야할지 정하는 것이 훨씬 수월해집니다.

### 왜 빅오표기법을 사용할까?

점근 표기법에는 O, Ω(오메가), θ(세타) 이라는 세가지 표기법이 있습니다. 만약 시간복잡도 측정 과정에서 오메가 표기법을 사용한다면 매우 정확하지만, 현실적으로 특정 코드의 시간복잡도를 완벽하게 알기 힘든 경우도 있으므로, 사용을 피하는 편입니다. 세타표기법을 사용한다면 가장 좋은 경우만 생각하기 때문에 큰 의미가 없습니다. 왜냐하면 프로그래밍에서 중요한 점은 가장 안좋은 연산이 소요되는 시간입니다. 최악의 연산이 일어나지 않으리란 보장이 없기 때문에 최악을 가정해서 빅오표기법을 사용하는 것입니다.

### 공간복잡도란?

시간복잡도가 연산의 소요시간을 나타낸다면 공간복잡도는 연산에 사용되는 메모리의 양을 나타냅니다.

자바스크립트는 글자 하나당 1byte, 숫자는 8byte를 할당합니다. 공간복잡도도 점근적 표기법을 사용하는데 마찬가지로 빅오표기법을 사용합니다. 왜 사용하는지는 [위에 내용에](https://www.notion.so/1-11e900be967b807eb240c325e4e2e5f9?pvs=21) 있습니다.

## 정리

시간복잡도와 공간복잡도는 알고리즘 문제에 접근함에 있어 매우 중요한 부분입니다. 어떤 알고리즘을 선택해야할지, 메모리를 얼마나 사용해야할지 생각해야할때, 무작정 알고리즘에 접근하기 보다는 시간복잡도와 공간복잡도를 생각하고 들어가면 통과활 확률이 올라가기 때문입니다. 따라서 각 알고리즘마다 시간복잡도와 공간복잡도를 알아놓는 것이 중요합니다.
