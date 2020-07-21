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
  
  while(i <= a*b) {
    
    if (i%a == 0 && i%b == 0) break;
    
    i++;
  }
  
  printf("%d\n", i);
}
```

## [C++]

```c++
#include <iostream>

void main() {
  int a = 20, b = 30;
  int i;
  
  if (a>b) {
    i = a;
  } else {
    i = b;
  }
  
  while (i <= a*b) {
    
    if (i%a == 0 && i%b == 0) {
      break;
    }
    
    i++;
  }
  
  std::cout<<i<std::endl;
  
  
}

```

## [java]

```java

public static void main(String[] args) {
  int a = 20, b = 30;
  int i;
  
  if (a>b) {
    i = a;
  } else {
    i = b;
  }
  
  while (i <= a*b) {
    
    if (i%a == 0 && i%b == 0) {
      break;
    }
    
    i++;
  }
  
  System.out.println(i);
  
}

```

## [python]

```python

a = 20
b = 20

if a>b:
  i = a
else:
  i = b
  
while i <= 20*30:
  if i%a==0 and i%b==0:
    break
  i=i+1
  
print(i)

```
