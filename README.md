include <stdio.h>

int main()
{
    float side, area,circum;
    printf("Enter the side value");
    scanf("%f", &side);
    area= side * side;
    circum=4 * side;
    printf("Area of a  square unit \n\n", area );
    printf("circumfrence of a square = %.2f square units \n",circum);
    return 0;
}
