# Solving-8-puzzle-problems-using-BFS
 - 2017년 1학기 성균관대학교 이지형 교수님 인공지능 수업 1번째 과제  
 - 8-puzzle problem 을 search strategy인 DFS, BFS를 이용하여 푸는 문제
 - 2017 1st semester Sungkyunkwan University professor Jee Hyong Lee's Artificial Intelligence class, 1st assignment
 - Solving 8-puzzle problem using search strategy DFS, BFS

## 1. Problem
 - 다음 4가지의 initial state를 시작으로 8-puzzle problem을 풀어라.
 - Initial state
 
   ![image](https://user-images.githubusercontent.com/26705935/40484585-0efdf7c0-5f97-11e8-9265-80ac5a421b89.png)
   
## 2. Environment
 - language : C++
 - IDE : Microsoft Visual studio 2017
 
## 3. Result
 - 실행 결과 표
  
   ![image](https://user-images.githubusercontent.com/26705935/40484756-a6240dba-5f97-11e8-8e2f-801fa67896d9.png)
  
 - DFS는 탐색 경과 시간이 매우 방대하여, 탐색 횟수에 한계를 지정하였다. 모두 100,000번을 탐색 한계로 지정하였고, 그 결과 BFS는 solution을 찾았지만 DFS는 탐색 시간 1분을 넘기고 나서도 solution을 찾지 못하였다.
 
## 4. Future work
 - A* algorithm을 이용하여 8-puzzle problem을 푸는 코드도 작성하여 업도르할 것이다.
