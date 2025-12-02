#include <stdio.h>

int main() {
    int hours;
    int minutes, seconds;

    // Input hours
    printf("Enter hours: ");
    scanf("%d", &hours);

    // Convert hours to minutes and seconds
    minutes = hours * 60;
    seconds = hours * 3600;

    // Display the results
    printf("%d hour(s) = %d minute(s) = %d second(s)\n", hours, minutes, seconds);

    return 0;
}
