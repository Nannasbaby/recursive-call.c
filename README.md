#include <stdio.h>
int f1(int x)
{
    if(x==0||x==1)
    return 1;
    else 
      return x*f1(x-1);
}
int main()
{
    int x;
    scanf("%d",&x);
    int res=f1(x);
    printf("%d",res);
}
