# Matrix_addition
#include<stdio.h>

int main()
{
	int a[4][4],b[4][4],c[4][4];
	int i,j;
	printf("Enter the values of the  matrix a:- \n");
		for(i=0;i<4;i++)
	{
		for(j=0;j<4;j++)
		{
			scanf("%d",&a[i][j]);		
		}
	}
	printf("\n");
	
	printf("The array a is :- \n");
		for(i=0;i<4;i++)
	   {
		  for(j=0;j<4;j++)
		   {
		    	printf("%5d",a[i][j]);		
		   }
		printf("\n");
	}
	
	
	printf("Enter the values of the  matrix b :-  \n");
		for(i=0;i<4;i++)
	{
		for(j=0;j<4;j++)
		{
			scanf("%d",&b[i][j]);
		}
	}
	
		printf("\n");
	
	printf("The array b is :- \n");
		for(i=0;i<4;i++)
	   {
		  for(j=0;j<4;j++)
		   {
		    	printf("%5d",b[i][j]);		
		   }
		printf("\n");
	}
	for(i=0;i<4;i++)
	{
		for(j=0;j<4;j++)
		{
			c[i][j]=a[i][j]+b[i][j];		
		}
	}
	
	printf("The result of addition is given below:- \n");
	for(i=0;i<4;i++)
	{
		for(j=0;j<4;j++)
		{
			printf("%5d ",c[i][j]);
		}
		printf("\n");
	}
	return 0;
}
