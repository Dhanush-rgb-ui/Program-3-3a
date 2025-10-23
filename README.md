# Module-3 Day-1 SEB
## AIM:
To write a program to convert a 11111111 binary value to decimal.

## For example:

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
