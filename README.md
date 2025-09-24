/*
Name: Victor Maina Kuria 
registration no:PA106/G/28732/25
description: program to display acceptance or delay of annual income 
*/

#include <stdio.h>

int main(){

//variable declaration 
int age;
float annualincome;

//prompt the user th display age
printf("Enter your age");
scanf("%d",&age);

//prompt the user to display annual income
printf("Enter your annualincome");
scanf("%f",&annualincome);

if(age>= 21 && annualincome>= 21000){
printf("Congratulations,you qualify for the loan.\n");
}

else{
printf("unfortunately,we are unable to offer you a loan at this time.\n");
}

return 0;
}

