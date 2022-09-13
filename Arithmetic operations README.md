#include <stdio.h>
#include<math.h>
int main() {
    int x,n,c,r=0;
    scanf("%d",&x);
    scanf("%d",&n);
    scanf("%d",&c);
    switch(c){
        case 1:
        r=pow(x,n);
        break;
        case 2:
        r=x+n;
        break;
        case 3:
        r=x-n;
        break;
        case 4:
        r=x*n;
        break;
        case 5:
        r=x/n;
        break;
    }
    printf("%d",r);
    return 0;
}
