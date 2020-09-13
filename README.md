# Tutorial
#include <stdio.h>
#include <cs50.h>
{
int main(void)
int a;
int age;
a = get_int("What's your age?: \n");
age = a * 365;
printf("You are %i days old!\n", age);
}
