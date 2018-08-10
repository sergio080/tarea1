# tarea1
tarea#include <stdio.h>

 int main()
 {
 int n,u,c=0;
printf("coloque numero");
scanf("%d",&n);
for (u=1;u<=n;u++)
{
if (n%1==0)c++;
}
if (c==2)
printf("el numero es primo");
else printf ("el numero no es primo");
return 0;
