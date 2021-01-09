#include <stdio.h>
#include <stdlib.h>

int main()
{
    int a, b, dzielnikA=0, dzielnikB=0;
    scanf("%d %d", &a, &b);
    if(a>0 && b>0)
    {
        for(int i=1; i<=a; i++)
        {
            if(a%i==0)
                dzielnikA++;
        }
        for(int i=1; i<=b; i++)
        {
            if(b%i==0)
            dzielnikB++;
        }
        if(dzielnikA==2 && dzielnikB==2)
        {
            if(a-b==2 || b-a==2)
                printf("true");
            else
                printf("false");
        }
        else
            printf("false");
    }
    else
    printf("false");
    return 0;
}
