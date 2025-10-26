#include <stdio.h>//数组的遍例
int main()
{
	int a[6];
	int i;
	int t;
	for (i = 0; i <=5; i++)
	{
		scanf("%d", &a[i]);
	}
	for (i = 0; i <= 5; i++)
	{
		printf("%d ", a[i]);
	}
	printf("\n");
	for (i = 0; i <=2; i++)
	{
		t = a[i];
		a[i] = a[5- i];
		a[5 - i] = t;
	}
	for (i = 0; i <=5; i++)
	{
		printf("%d ", a[i]);
	}
}
