#include <stdio.h>

int main() {
    double x, result = 1;
    int y, i;
    printf("Enter the value of x: ");
    scanf("%lf", &x);
    printf("Enter the value of y: ");
    scanf("%d", &y);
    for (i = 0; i < y; i++) {
        result *= x;
    }
    printf("%.2lf raised to the power of %d is: %.2lf\n", x, y, result);
}
