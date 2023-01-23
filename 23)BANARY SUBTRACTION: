#include<stdio.h>


void Subtract(int n, int a[], int b[])
{
	for(int i = 0; i < n; i++)
	{
		
		if(b[i] == 1)
		{
			b[i] = 0;
		}
		else
		{
			b[i] = 1;
		}
	}

	for(int i = n - 1; i >= 0; i--)
	{					
		if(b[i] == 0)
		{
			b[i] = 1;
			break;
		}
		else
		{
			b[i] = 0;
		}
	}
	int t = 0;						
	for(int i = n - 1; i >= 0; i--)
	{
		a[i] = a[i] + b[i] + t;
		if(a[i] == 2)
		{
			a[i] = 0;
			t = 1;

		}
		else if(a[i] == 3)
		{
			a[i] = 1;
			t = 1;
		}
		else
			t = 0;
	}
	printf("\n");
	if(t==1)
	{	
		for(int i = 0; i < n; i++)
		{
			printf("%d",a[i]);	
		}
	}
	else				
	{				
		for(int i = 0; i < n; i++)
		{				
			if(a[i] == 1)
				a[i] = 0;
			else
