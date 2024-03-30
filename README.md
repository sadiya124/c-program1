# c-program1
to display  hello world and greeting to the user
#include<stdio.h> #include<conio.h> #include<string.h>

int main()
{
char a[50];
printf("Enter your name:"); gets(a);
printf("Hello World");
printf("\nHello %s\n",a); return 0;
}

