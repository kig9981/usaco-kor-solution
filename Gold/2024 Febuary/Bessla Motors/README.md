K번째 최단경로 찾기 문제와 유사합니다. 1번부터 C번까지 정점을 시작점으로 삼는 multi source dijkstra를 사용하여 풀 수 있는데, K번째 최단경로 찾기 문제와 다른 점은 같은 source에서의 경로를 두번 이상 고려하지 않도록 처리해주어야 합니다.

이를 나이브하게 처리할 경우 시간복잡도는 $O(MKlogN+MK^2)$에 전체 문제를 해결할 수 있습니다.