# c-4
triangle pattern
#include<stdio.h>
int main()
{
	int i,j,n;
	printf("enter the row matrix:");
	scanf("%d",&n);
	for(i=1;i<=n;i++){
		for(j=1;j<=i;j++){
			printf("* ");
}
printf("\n");
}
	return 0;
}
