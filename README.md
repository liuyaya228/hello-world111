# hello-world111
add
#include <stdio.h>
main()
{	unsigned long int a,b,c,d;
printf("这是一个用于算鸡兔同笼的小程序(仅能输入整数,使用回车键切换)\n请输入鸡兔的总数");
scanf("%d",&a);
printf("\n请输入鸡兔脚的总数");
scanf("%d",&b);
if(b%2 != 0)
{
printf("输入的鸡兔脚的总数有错误！");
return 0;
}
c=(4*a-b)/2; // 鸡的数目
d=a-c;  // 兔的数目
if(c*2+d*4==b) printf("鸡有%ld只\n兔有%ld只",c,d);
else printf

