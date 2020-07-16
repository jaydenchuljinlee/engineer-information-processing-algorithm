
# 소스코드

```java

public static void main(String[] args) {
  int a= 10, b = 15;
  int i;
  int m;
  
  //a와 b 중에 큰 값을 m에 넣는다.
  if (a>b) {
    m = b;
  } else {
    m = a;
  }
  
  //i를 하나씩 감소시키면서 a와 b의 공약수를 찾는다
  for (i = m; i >= 1; i--) {
    if (a % i == 0 && b % i == 0) {
      System.out.println(i);
      break;
    }
  }
}

```
