# Test
#include <stdio.h>
#include <stdlib.h>
int faculteit(int n)
{
    int i, res = 1;
    for(i=1; i<=n; i = i+1)
        {
            res = res * i;
        }
    return res;
}

int main()
{
    int n;

    printf("Please enter the value of n.\n");
    scanf("%d", &n);

    return faculteit(n);
}
