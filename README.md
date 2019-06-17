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

Ik heb de main functie verwijderd.
