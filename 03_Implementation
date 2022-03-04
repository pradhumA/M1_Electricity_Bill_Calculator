#include <stdio.h>
#include <stdlib.h>
#include <conio.h>
#include <string.h>
#include <Windows.h>
#include "MaElectricBill.h"
#include "Bill.h"
void Urban();
void Rural();
void main()
{ 
	details();
	int option;
	do
	{
		printf("Electric Bill\n");
		printf("Please enter your choice from below (1-2):\n");
		printf("1. Urban\n");
		printf("2. Rural\n");
		printf("3. EXIT\n");
		printf("Electricity Board Helpline: 8435 2340\n");
		printf("Enter your choice :\n");
		scanf("%d", &option);
		system("cls");
		switch (option)
		{
		case 1:
			Urban();
			break;
		case 2:
			Rural();
			break;
		default:
			printf("SORRY WRONG CHOICE!\n");
			printf("PLEASE CHOOSE FROM 1 or 2\n");
		}
		getch();
	} while (option != 3);
}
