# no-of-days-in-a-month
 #include <stdio.h>
int main() {
int m;
printf("Enter a month number (1-12): ");
scanf("%d", &m);
if(m==1||m==3||m==5||m==7||m==8||m==12||m==10)
{printf("IT HAS 31 DAYS");}
else if(m==4||m==6||m==9||m==11){
printf("IT HAS  DAYS");}
else
{
    printf("it has 29");
}
return 0;
}
