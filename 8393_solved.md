# 문제 제목: 

## 문제 정보
- **출처:** noj.am/8393
- **난이도:** Medium-Hard

## 문제 설명
n이 주어졌을 때, 1부터 n까지 합을 구하는 프로그램을 작성

## 해결 과정
n을 입력받고 반복문을 사용해서 해결

### 접근 방법

## 코드
```python
n = int(input())
sum = 0
i = 1
while i <= n:
    sum += i
    i += 1
print(sum)
