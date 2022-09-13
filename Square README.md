#include<stdio.h>
int main(){
int num,square,cube;
printf("enter an integer:");
scanf("%d",&num);
square=num*num;
cube=num*num*num;
printf("square of %d is :%d\n",num,square);
printf("cube of %d is :%d",num,cube);
}
return 0;
}
