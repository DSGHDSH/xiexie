# xiexie
My daima
#define _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>
#include<string.h>
struct BOOK 
{char name[20];
short price;
};

int main()
{
	struct BOOK b1={"C语言程序设计"};
char* pb=&b1.name;
	printf("%s\n",pb);
		return 0;
		
