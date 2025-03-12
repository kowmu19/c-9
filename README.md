# c-9
#include <stdio.h>
int main()
{
    int i,n,sum=0;
    printf("enter the number:\n");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        if(i% 2==0){
            sum+=i;
        }
    }
    printf("sum of even numbers:%d",sum);
    return 0;
}
