## 9934

### 핵심
1. 완전 이진 트리이므로 규칙을 발견할 수 있었음
2. 높이가 4인 완전 이진 트리를 임의로 만들어 규칙 발견
    k = 4 -> 노드 개수 = 2^4 - 1 = 15

    18
    10 25
    8 13 20 28
    3 9 12 15 19 23 26 30
    
    중위 순회 -> 3 8 9 10 12 13 15 18 19 20 23 25 26 28 30

    트리를 index로 나타내면
    7						-> 노드 개수 / 2
    3 11						-> 8 차이
    1 5 9 15					-> 4 차이
    0 2 4 6 8 10 12 14		-> 2 차이

    ㄴ> 시작점이 4, 2, 1씩 작아짐 
<br/>

### 사용
1. BufferedReader
2. StringTokenizer
3. Math.pow()
