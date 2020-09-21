#include<stdio.h>
int main(){
	int n,i;
	printf("enter the number:");
	scanf("%d",&n);
	for(i=2;i<=n/2;i++){
		if(n%i==0)
		{printf("%d is not prime",n);
		break;
		}
		if(i==n/2)
		{printf("%d is prime",n);
		break;
		}
	}
}
