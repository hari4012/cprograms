#include<stdio.h>
#include<math.h>
int main()
{
 int a,b,c,sp,Area,peri;
 printf("\nEnter first side of triangle : ");  
 scanf("%d",&a);  
 printf("\n Enter second side of triangle : ");   
 scanf("%d",&b);   
 printf("\n Enter third side of triangle : ");   
 scanf("%d",&c);  
 sp=(a+b+c)/2;
 Area=sqrt(sp*(sp-a)*(sp-b)*(sp-c));
 peri=a+b+c;
 if(Area==peri)
 {
  printf("\n It is an Equable Triangle");
 }
 else
 {
  printf("\n Not an Equable Triangle");
 }
 return 0;
}
