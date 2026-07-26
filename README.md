#include<stdio.h>
int main(){
printf("Hello,world!\n");
return 0;
}
#include<stdio.h>
void main(){
int n,i,count=0;
printf("Enter n value");
scanf("%d",&n);
for(i=1;i<=n;i++){
if(n%i==0){
count+=1;
}
}
if (count==2){
printf("%d is prime",n);
}
else{
printf("%d is not prime",n);
}
}

