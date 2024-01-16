#include<stdio.h>
int main()
{
    long long int n,prime=1;
    scanf("%d",  &n);
    for(int i=2; i<n; i++)
    {
        if (n%i==0)
        {
            prime=0;
            break;
        }
    }

    if(prime==0 || n==1 && n!=2)
    {
        printf("no");
    }


    else
    {
        printf("yes");
    }
    return 0;
}

