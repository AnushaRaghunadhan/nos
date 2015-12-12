#include<stdio.h>
int main()
{
    int n1,sum=0,i;
    printf("enter the number");
    scanf("%d",&n1);
    for(i=0;i<n1;i++)
    {
        sum=sum+i;
    }
    printf("the sum is %d",sum);
    return 0;
}
