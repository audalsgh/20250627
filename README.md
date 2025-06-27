# 5일차 내용 
## 자동차 코드 사용시 고려되야 할 기준들
https://docs.google.com/document/d/1r5Uor8GDQ9IjDMNfYauvbfUjBhyt0xBH3RkPyPy_ty4/edit?usp=sharing

## 자율주행에서 쓰이는 "딕셔너리 리스트" 예제들
https://docs.google.com/document/d/1t382g5OzXLUNuUKXkqBH96oRROo97or9S--7e7AUBos/edit?tab=t.0

```python
lidar_distance = [ 0.9 3.8 15.7 ... 8.5 ]  #라이다 센서 데이터값을 받아 리스트로 정리해두었다. 
safe_distances = [dist for dist in lidar_distances if dist > 5.0]  #(딕셔너리 + for문)으로, 특정 거리 이하이면 장애물과 가까운 것으로 판단하는 코드들이 중요하다
```

## 자율주행에서 쓰이는 "튜플" 예제들
https://docs.google.com/document/d/1MSmcpGo_pFJ1uCgVH93B4UuOHtGw23Z4YGOGA_APMLI/edit?usp=sharing

**튜플을 쓰는이유**

![image](https://github.com/user-attachments/assets/d39c7ade-f921-472d-9575-867a755c4113)

**튜플 언패킹, 변수를 여러번 정의할 필요없이 튜플값 순서대로 할당됨!**

![image](https://github.com/user-attachments/assets/542cc0ec-9a1e-4a68-9a4a-9542609b31f9)
