# Info
[31863 내진 설계](https://www.acmicpc.net/problem/31863)

## 💡 풀이 방법 요약
1. 입력값을 전처리하여 각 빌딩의 좌표와 남은 수명을 저장하는 딕셔너리 구축
2. 초기 진원지부터 4방향으로 두 칸씩 방문해 보며 무너지는 건물의 좌표를 큐의 초기값으로 삽입
3. 구축 완료된 큐를 사용하여 BFS 탐색을 진행하고, 건물의 수명이 0이 될 때 마다 카운트를 증가

## 👀 실패 이유
`if not (0 < nr <= N and 0 < nc <= M):`
범위 밖 예외처리할때 등호 방향을 반대로 줬습니다...바본가

## 🙂 마무리
None
