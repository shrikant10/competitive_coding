#include<stdio.h>

int main(void){
	int n,i,t,k;
	scanf("%d",&t);
	int amt[t];
	for(i=0;i<t;i++){
		scanf("%d",&n);
		int month[n];
		int count=0;
		int due_amount=0;
		for(k=0;k<n;k++)
			scanf("%d",&month[k]);
		for(k=0;k<n;k++){
			if(month[k]==0){
				count++;
				due_amount+=1100;
			}
			else{
				if(count!=0){
					due_amount+=100;
				}
			}
		}
		amt[i]=due_amount;
	}
	for(i=0;i<t;i++){
		printf("%d\n",amt[i]);
	}
return 0;
}
