#include<stdio.h>
#include<conio.h>
#include<graphics.h>
#include<math.h>
void main()
{
int x1,x2,y1,y2,dx,dy,xn,yn,i,step;
int gd=DETECT,gm;
initgraph(&gd,&gm,"C:\\TURBOC3\\BGI");printf("x1,y1:\n");scanf("%d,%d",&x1,&y2);
printf(" x2,y2:");
scanf("%d,%d",&x2,&y2);
dx=x2-x1;
dy=y2-y1;
if(abs(dx)>abs(dy))
{
step=abs(dx);
}
else
{
step=abs(dy);
}
xn=dx/step;
yn=dy/step;
for(i=1;i<=step;i++)
{
putpixel(x1,y1,RED);
x1=x1+xn;
y1=y1+yn;
}
getch();closegraph();
}