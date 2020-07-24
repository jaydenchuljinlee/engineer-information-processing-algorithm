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
