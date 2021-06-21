# No-of-bits-require-to-represent-in-binary
#include<stdio.h>
#include<math.h>
int main()
{   
    int n,k;
    printf("Please provide a number:\n");
    scanf("%d",&n);
    k=(log(n)/log(2));
    printf("The number of bits reqire to represent in binaary are:%d",k+1);
    return 0;
}
