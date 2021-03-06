### DFS 구현
- <a href="https://github.com/hongjw1991/Java-DataStructure-Algorithm-DesignPattern/tree/master/algorithm/problem_solve/dfs/App.java">App.java</a>
    - Main method
- <a href="https://github.com/hongjw1991/Java-DataStructure-Algorithm-DesignPattern/tree/master/algorithm/problem_solve/dfs/DFSWithStack.java">DFSWithStack.java</a>
    - DFS Stack기반 알고리즘 구현
- <a href="https://github.com/hongjw1991/Java-DataStructure-Algorithm-DesignPattern/tree/master/algorithm/problem_solve/dfs/DFSWithRecursive.java">DFSWithRecursive.java</a>
    - DFS Recusive 기반 알고리즘 구현
- <a href="https://github.com/hongjw1991/Java-DataStructure-Algorithm-DesignPattern/tree/master/algorithm/problem_solve/dfs/Vertex.java">Vertex.java</a>
    - Vertex 노드 정의한 코드

### TopologicalOrdering
- 개념
    - DFS를 통해 연결된 Vertex를 계속 탐색 시에 현재 Backward Tracking으로 돌아오지 못한 상태에 있는 Vertex는 기본적으로 방문 중인 상태로 유지함
    - Backward Tracking으로 돌아왔다면 해당 Vertex는 이미 방문 된 것으로 파악
    - 이를 통해, 방문 중인 Vertex가 방문이 완료되지 않은 상태에서 또 다시 탐색 Vertex로 방문된다면 Cycle이 형성된 것이라 파악할 수 있음
- <a href="https://github.com/hongjw1991/Java-DataStructure-Algorithm-DesignPattern/tree/master/algorithm/problem_solve/dfs/TopologicalOrdering.java">TopologicalOrdering.java</a>
    - TopologicalOrdering 구현한 코드
    - ![Alt Text](../image/Topological_graph.png)

### Maze Solve
- 개념
    - 미로를 탈출 할 수 있는 코드를 작성함
    - 주변은 벽으로 막혀 있고 열려 있는 길을 DFS 방식으로 탐사하여 빠져나갈 수 있는 길이 있는지 없는지 조사할 수 있다.
- <a href="https://github.com/hongjw1991/Java-DataStructure-Algorithm-DesignPattern/tree/master/algorithm/problem_solve/dfs/maze_solve">해당 코드 확인</a>

### Cycle Detection
- <a href="https://github.com/hongjw1991/Java-DataStructure-Algorithm-DesignPattern/tree/master/algorithm/problem_solve/dfs/CycleDetection.java">해당 코드 확인</a>

### 백준 알고리즘 코드 내역
- <a href="https://github.com/hongjw1991/Java-DataStructure-Algorithm-DesignPattern/tree/master/algorithm/problem_solve/dfs/baekjoon">참조</a>
    - 해당 Directory에는 DFS 알고리즘 문제를 푼 내역이 들어있음