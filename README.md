#include <stdio.h>
int main() {
    float celsius, fahrenheit;
printf(“25331A05D6\n”);
    // Celsius to Fahrenheit
    printf("Enter temperature in Celsius: ");
    scanf("%f", &celsius);

    fahrenheit = (celsius * 9 / 5) + 32;   // expression using operators
    printf("Fahrenheit = %.2f\n", fahrenheit);

    // Fahrenheit to Celsius
    printf("Enter temperature in Fahrenheit: ");
    scanf("%f", &fahrenheit);

    celsius = (fahrenheit - 32) * 5 / 9;   // expression using operators
    printf("Celsius = %.2f\n", celsius);

    return 0;
}

