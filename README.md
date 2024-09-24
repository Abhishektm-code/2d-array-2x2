# 2d-array-2x2
#include <stdio.h>

int main() 
{
    int a[2][2];
    int i=0,j=0;
    int even=0;
    int odd=0;

printf("elements are : \n");
 
    for(i=0;i<2;i++)
    {
        for(j=0;j<2;j++)
        {
            scanf("%d",&a[i][j]);
        }
    }
printf("matrix is :\n");
     for(i=0;i<2;i++)
    {
        for(j=0;j<2;j++)
        {
            printf("%d \t",a[i][j]);
        }
        printf("\n");
    }

    for (int i = 0; i < 2; i++)
     {
        for (int j = 0; j < 2; j++) 
        {
            if (a[i][j] % 2 == 0)
            {
                even++;
            }
            else
            {
                odd++;
            }
        }
    }
    printf("Number of even numbers: %d\n", even);
    printf("Number of odd numbers: %d\n", odd);

}
