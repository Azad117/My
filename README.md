
#include<stdio.h>
#include<conio.h>
void main()
{
    long int a1=2147483647,a2=2147483648,a3=-2147483649;
    unsigned long int b1=4294967295,b2=4294967296,b3=-1;
    clrscr();
    printf("a1=%ld\t a2=%ld\t a3=%ld\n",a1,a2,a3);
    printf("b1=%llu\t b2=%llu\t b3=%llu",b1,b2,b3);
    getch();
}
