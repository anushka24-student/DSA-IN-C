# Finding-Previous-Greater-element-DSA-IN-C-
Write a program to find the previous greater element for each element in an array.    For each element in the array, the previous greater element is the nearest element to its left that is strictly greater than it. If no such element exists, print "-1" for that position.

#include <stdio.h>
int main(){
	int n,i,j;
	scanf("%d",&n);
	int a[n];
	for(i=0;i<n;i++){
		scanf("%d",&a[i]);
	}
	for(i=0;i<n;i++){
		int found=0;
		for(j=i-1;j>=0;j--){
			if(a[j]>a[i]){
				printf("%d ",a[j]);
				found=1;
				break;
			}
		}
		if(found==0){
			printf("-1 ");
		}
	}
}

