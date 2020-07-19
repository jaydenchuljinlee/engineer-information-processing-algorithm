# 최소 공배수 예제

## [C]

```c
#include<stdio.h>

void main() {
  int a = 20, b = 30;
  int i;
  
  if (a > b) {
    i = a;
  } else {
    i = b;
  }
  
  while(i <= 20*30) {
    
    if (i%a == 0 && i%b == 0) break;
    
    i++;
  }
  
  printf("%d\n", i);
}
```

## [C++]

## [java]

## [python]
