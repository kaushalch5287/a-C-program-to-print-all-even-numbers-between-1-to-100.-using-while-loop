/******************************************************************************

Welcome to GDB Online.
GDB online is an online compiler and debugger tool for C, C++, Python, PHP, Ruby, 
C#, VB, Perl, Swift, Prolog, Javascript, Pascal, HTML, CSS, JS
Code, Compile, Run and Debug online from anywhere in world.

*******************************************************************************/
#include <stdio.h>
int main()
{
 int i, n;
 printf("Print all even numbers till: ");
 scanf("%d", &n);
printf("All even numbers from 1 to %d are: \n", n);
 i=1;
 while(i<=n)
 {
 if(i%2==0)
 {
 printf("%d\n", i);
 }
 i++;
 }
 return 0;
}
