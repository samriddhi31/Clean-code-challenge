#include<stdio.h>
#include<conio.h>
void main()
{
    int number, binary = 0, rem = 0, place_of_variable = 1;
    //inputting the number
    //using loop to input the number greater than 7
    do
    {
        printf("Enter the decimal number: \n");
        scanf("%d", &number);
    }while(number<7);
    
    printf("Binary number of %d is: ", number);
    
    while(number)
    {
        rem = number % 2;
        number = number / 2;
        binary = binary + (rem * place_of_variable);
        place_of_variable = place_of_variable * 10;
    }
    printf("%d\n", binary);
    return 0;
}
