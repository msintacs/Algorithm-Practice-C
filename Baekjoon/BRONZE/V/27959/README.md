## 27959. 초코바

### 문제
밤고는 
$100$원 동전을 
$N$개 갖고 있고, 그 돈으로 가격이 
$M$원인 초코바를 사 먹으려고 한다. 밤고는 갖고 있는 돈으로 초코바를 사 먹을 수 있는지 알고 싶어 한다.

밤고가 가진 돈이 초코바의 가격 이상이면 밤고는 초코바를 살 수 있다. 밤고가 가진 돈이 초코바를 사기에 충분한지 판단해주자.

### 입력
첫 번째 줄에 두 정수 
$N$과 
$M$이 공백을 사이에 두고 주어진다. (
$1 \le N \le 100$, 
$1 \le M \le 10\ 000$)s

### 출력
밤고가 초코바를 살 수 있으면 `Yes`를, 없으면 `No`를 출력한다.

### 예제 입력 1
```
30 300
```

### 예제 출력 1
``` 
Yes
```

### 예제 입력 2
```
5 10000
```

### 예제 출력 2
``` 
No
```

### 예제 입력 3
```
7 785
```

### 예제 출력 3
``` 
No
```

### 알고리즘 분류
* 수학
* 사칙연산
  
#

scanf 로 동전의 갯수와 초코바의 가격을 입력받는다.
입력받은 동전갯수에 * 100 하여 실제 금액을 계산한다.

이후, 가격과 가진 돈을 비교하여 가진 금액이 초코바금액보다 크거나 같을 때 `Yes` 를 출력하고 가진돈이 초코바 가격보다 적다면 `No`를 출력한다.

