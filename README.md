#include<stdio.h>
#include<conio.h>
void main()
{
int i,s,k[50],x,r,q;
float n1,n2,per,res,p,tot;
printf("press 1 for addition \n press 2 for differance \n press 3 for multiple \n press 4 for division \n press 5 for modulo \n
press 6 for percentage \n press 7 for average ");
printf("\n enter the number");
scanf("%d",&x);
switch(x)
{
case 1:
printf("enter the two number");
scan("%f %f",&n1,&n2);
res=n1+n2;
printf("\n the addition of two number is %.2f",res);
break:
case 2:
printf("enter the two number");
scan("%f %f",&n1,&n2);
res=n1-n2;
printf("\n the differance of two number is %.2f",res);
break;
case 3:
printf("enter the two number");
scan("%f %f",&n1,&n2);
res=n1*n2;
printf("\n the multiply of two number is %.2f",res);
break;
case 4:
printf("enter the two number");
scan("%f %f",&n1,&n2);
res=n1+n2;
printf("\n the divisio of two number is %.2f",res);
break;
case 5:
printf("enter the two number");
scan("%d %d",&r,&q);
printf("\n the modulo of two number is %d",r%q);
break;
case 6:
printf(" \n enter the total number");
scan("%f",&tot);
printf("\n enter the gets number");
scanf("%f",&p);
per=p*100/tot;
printf("\n the percentage of  gets number is %.2f",per);
break;
case 7:
printf("enter the number");
scan("%d",&s);
printf(" \n enter the values");
for(i=1;i<=s;i++)
{
scanf("%d",&k[i]);
}
for(i=1;i<=s;i++)
{
tot=tot+k[i];
}
printf("display the total values %.2f",tot);
res=tot/s;
printf("the average of given values is %.2f",res);
break;
default:
printf("invalid service");
break;
}
getch();
}
