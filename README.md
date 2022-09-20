# Data-Structures-CSA0375
1.PROGRAM FOR MATRIX MULTIPLICATION:
#include<stdio.h>
int main()
{
	int a[2][2],b[2][2],c[2][2];
	int i,j,k,sum;
	printf("Enter A Matrix\n");
	for(i=0;i<2;i++)
	{
	  for(j=0;j<2;j++)
	  {
	   scanf("%d",&a[i][j]);
      } 
	}
	
	printf("Enter B Matrix\n");
	for(i=0;i<2;i++)
	{
	  for(j=0;j<2;j++)
	  {
	   scanf("%d",&b[i][j]);
}
}
	for(i=0;i<2;i++)
	{
	  for(j=0;j<2;j++)
    {
	   c[i][j]= 0;
	   for(k=0;k<2;k++)
	{
		c[i][j]+= a[i][k]*b[k][j];
		
	}
    } 
   }
   
   printf("\nthe multiplication of two matrices \n");
   	for(i=0;i<2;i++)
   	{
	   
   	 for(j=0;j<2;j++)
   {
   	
   	printf("%d  ",c[i][j]);
	   	   }   	
	   	   printf("\n");
	   }
}
OUTPUT:
![2022-09-20](https://user-images.githubusercontent.com/113410100/191207230-e63ff6b6-90ff-4475-8925-14c3c3ffef4b.png)


2.PROGRAM FOR ODD OR EVEN:
#include <stdio.h>
int main()
{
    int num1, rem1;
 
    printf("Input an integer : ");
    scanf("%d", &num1);
    rem1 = num1 % 2;
    if (rem1 == 0)
        printf("%d is an even integer\n", num1);
    else
        printf("%d is an odd integer\n", num1);
}
OUTPUT:
![image](https://user-images.githubusercontent.com/113410100/191208251-3922f8d9-54d9-4bc0-bb78-97ce624dfbd2.png)

