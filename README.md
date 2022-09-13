# C-Programming
About the C programming, I am uploading the codes I have written 



#include<stdio.h>
#include<conio.h>
int main ()
{
    int a[10],temp,i,j;
    printf("Enter the array element\n");
    for(i=0;i<10;i++)
    {
        scanf("%d",&a[i]);
    }
    for(i=0;i<10;i++)
    {
        for(j=0;j<10;j++)
        {
            if(a[i]<a[j])
            {
                temp=a[i];
                a[i]=a[j];
                a[j]=temp;
            }
        }
    }
    printf("The sorted array element\n");
    for(i=0;i<10;i++)
    {
        printf("%d  ",a[i]);
    }
    return 0;
}
