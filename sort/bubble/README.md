# [C]

```c

#include <stdio.h>

void main() {
  int i,j;
  int temp;
  int a[5] = {4,2,3,5,1};
  
  for (i = 0; i < 4; i++) {
    for (j = 0; j < 4-i; j++) {
      
      if (a[j] > a[j + 1]) {
        
        temp = a[j];
        a[j] = a[j+1];
        a[j+1] = temp;
      }
    }
  }
  
 for (i = 0; i < 5; i++) {
  printf("%d\n", a[i]);
 } 
}

```

# [C++]

```c++
#include <iostream>

void main() {
  int i,j;
  int temp;
  int a[5] = {4,2,3,5,1};
  
  for (i = 0; i < 4; i++) {
    for (j = 0; j < 4-i; j++) {
      
      if (a[j] > a[j+1]) {
        temp = a[j];
        a[j] = a[j+1];
        a[j+1] = temp;
      }
    }
  }
  
  for (i = 0; i < 5; i++) {
    std::cout<<a[i]<<std::endl; 
  }
}


```

# [java]

```java

public static void main(String[] args) {
  int i,j;
  int temp;
  int[] a = {4,2,3,5,1};
  
  for (i = 0; i < 4; i++) {
    for (j = 0; j < 4-i; j++) {
      
      if (a[j] > a[j+1]) {
        
        temp = a[j];
        a[j] = a[j+1];
        a[j+1] = temp;
      }
    }
  }
  
  for (i = 0; i < 5; i++) {
    System.out.println(a[i]);
  }
}

```

# [python]

```python

temp = 0;
a = [4,2,3,5,1];

for i in range(0,4) :
  for j in range(0,4-i) :
    if (a[j] > a[j+1]) {
      temp = a[j];
      a[j] = a[j+1];
      a[j+1] = temp;
    }
    
print(a);
  

```
