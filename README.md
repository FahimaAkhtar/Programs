# Programs
#include <stdio.h>
#include <stdlib.h>

int main()
{
   int n,i;
   printf("Enter the number of CT:");
   scanf("%d",&n);
   int CT_mark[n];
   printf("\nEnter %d CT marks:",n);
   for(i=0;i<n;i++)
    scanf("%d",&CT_mark[i]);

    int total=0;
    for(i=0;i<n;i++)
    {
        total=total+CT_mark[i];
    }
    printf("\nTotal marks:%d",total);
    float average=total/n;
    printf("\nAverage:%f",average);
    return 0;
}
