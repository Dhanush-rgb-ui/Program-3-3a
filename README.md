# Module-3 Day-1 SEB
## AIM:
To write a program to convert a 11111111 binary value to decimal.

## For example:
<img width="356" height="68" alt="image" src="https://github.com/user-attachments/assets/c34503ea-f562-48d4-8a5e-7e566d247967" />


## Program:
```c
#include <stdio.h>
int main(){
    int a=11111111;
    int sum=0;
    int base=1,reminder;
    
    while(a>0){
        reminder=a%10;
        sum=sum+reminder*base;
        a=a/10;
        base=base*2;
    }
    printf("11111111 in binary = %d in decimal",sum);
    return 0;
}
```

## Result:
<img width="726" height="73" alt="image" src="https://github.com/user-attachments/assets/d3792f1c-324d-4ca8-9cc1-d1817556833e" />

