#include <stdio.h>

int main() {
    int number;
    printf("Enter a number: ");
    scanf("%d", &number);

    int sum = 0;

    for (int i = 1; i <= number; i++) {
        if (number % i == 0) {
            sum += i;
        }
    }

    printf("The sum of all factors of %d is %d.\n", number, sum);

    return 0;
}
