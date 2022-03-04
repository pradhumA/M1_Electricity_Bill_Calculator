#include<stdio.h>
#include<stdlib.h>
#include<conio.h>
#include<string.h>
#include<Windows.h>
#include"MaElectricBill.h"

void details()
{
    printf("Enter your  area name:\n");
	scanf("%s", E.area);
	printf("Enter your  name:\n");
	scanf("%s", E.name);
	printf("Enter your Meter Number:\n");
	scanf("%d", &E.meternumber);
    printf("Enter units consumed:\n");
	scanf("%d", &E.unitsconsumed);
    printf("Enter email ID :\n");
    scanf("%s", E.email);
    printf("Enter the permanent address :\n");
    scanf("%s", E.address);
    printf("Enter the phone number : \n");
    scanf("%s", E.phonenumber);
}

void Urban()
{
    int amount=0;
    E.unitsconsumed;
    if(E.unitsconsumed <=30 && E.unitsconsumed >= 0)
    {
        amount = E.unitsconsumed * 3.25; //3.25 is rupees
    }
    else if(E.unitsconsumed >= 31 && E.unitsconsumed <= 100)
    {
        amount = E.unitsconsumed * 4.70;
    }
    else if(E.unitsconsumed >= 101 && E.unitsconsumed <= 200)
    {
        amount = E.unitsconsumed * 6.25;
    }
    else
    {
        amount = E.unitsconsumed * 7.30;
    }

    printf("****Electricity Bill****\n\n");
    printf("Name : %s\n", E.name);
    printf("In Urban, your electricity bill is: %d\n", amount);
    printf("Units you consumed per month: %d\n",E.unitsconsumed);
}

void Rural()
{
    int amount=0;
    E.unitsconsumed;
    if(E.unitsconsumed <=30 && E.unitsconsumed >= 0)
    {
        amount = E.unitsconsumed * 3.15; //3.25 is rupees
    }
    else if(E.unitsconsumed >= 31 && E.unitsconsumed <= 100)
    {
        amount = E.unitsconsumed * 4.40;
    }
    else if(E.unitsconsumed >= 101 && E.unitsconsumed <= 200)
    {
        amount = E.unitsconsumed * 5.95;
    }
    else
    {
        amount = E.unitsconsumed * 6.80;
    }
    printf("Electricity Bill\n\n");
    printf("Name : %s\n", E.name);
    printf("In Urban, your electricity bill is: %d\n", amount);
    printf("Units you consumed per month: %d\n", E.unitsconsumed);
}
