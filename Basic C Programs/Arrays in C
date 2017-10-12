// Programs to Remove Duplicate Elements in an Array entered by User .
#include<stdio.h>
int main()
{   int i,n,j,dup;
    dup=0;
    int a[10];
    printf("Enter Size");   //Obtaining the size of Array.
    scanf("%d",&n);
    printf("Enter The Array -");  //Obtaining the Array.
    for(i=0;i<n;i++)
    {   scanf("%d",&a[i]);
    }
    for(i=0;i<n;i++)
    {   for(j=i+1;j<=n;j++)
        {   if(a[i]==a[j])
            {   dup=j;          // Locating The DUplicate Element.
                for(int k=dup;k<n;k++)
                {   a[k]=a[k+1];               //Adjusting the arrys Indexes in order to remove the duplicate element.
                }
                n=n-1;
            }
        }

    }

    printf("- NEW ARRAY -");
    for(i=0;i<n;i++)
    {   printf("%d",a[i]);
    }

    return 0;
}
