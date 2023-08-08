# hackerrank-si-basic
right-angled triangled pattern2.c




#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,i,j,k;
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        k=i;
        for(j=1;j<=i;j++)
        {
            printf("%d ",k);
            k=k+(n-j);
        }
        printf("\n");
    }
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}

