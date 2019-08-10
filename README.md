# hackathon
#include<stdio.h>
#include<conio.h>
void main(){
  int x,p,sum=0,c=0;
  scanf("%d",&x);
  scanf("%d",&p);
  p=100-p;
  if(x>=0&&x<=10000){
    if(p>=0&&p<=100){
      while(x!=0){
         sum=sum+x;
         c++;
         x=(x*p)/100;
      }
      printf("sum of money is:%d\n",sum);
      printf("number of cups of coffee have to drink is:%d",c);
     }
  }
}
