1.#include <stdio.h>

int main() {
    float celsius, fahrenheit;

    // Ask the user to enter temperature in Celsius
    printf("Enter temperature in Celsius: ");
    scanf("%f", &celsius);

    // Convert Celsius to Fahrenheit
    fahrenheit = (9.0 / 5.0) * celsius + 32;

    // Display the result
    printf("%.2f°C is %.2f°F\n", celsius, fahrenheit);

    return 0;
}


Enter temperature in Celsius: 25
25.00°C is 77.00°F


2.#include <stdio.h>

int main() {
    float base_salary, hra_percent, da_percent, ta_percent;
    float hra, da, ta, gross_salary;

    // Input base salary
    printf("Enter base salary: ");
    scanf("%f", &base_salary);

    // Input percentages
    printf("Enter HRA percentage: ");
    scanf("%f", &hra_percent);

    printf("Enter DA percentage: ");
    scanf("%f", &da_percent);

    printf("Enter TA percentage: ");
    scanf("%f", &ta_percent);

    // Calculate HRA, DA, and TA amounts
    hra = (hra_percent / 100) * base_salary;
    da  = (da_percent / 100) * base_salary;
    ta  = (ta_percent / 100) * base_salary;

    // Calculate gross salary
    gross_salary = base_salary + hra + da + ta;

    // Output the results
    printf("\n--- Salary Breakdown ---\n");
    printf("Base Salary: %.2f\n", base_salary);
    printf("HRA: %.2f\n", hra);
    printf("DA: %.2f\n", da);
    printf("TA: %.2f\n", ta);
    printf("Gross Salary: %.2f\n", gross_salary);

    return 0;
}

Output 

Enter base salary: 30000
Enter HRA percentage: 20
Enter DA percentage: 10
Enter TA percentage: 5

--- Salary Breakdown ---
Base Salary: 30000.00
HRA: 6000.00
DA: 3000.00
TA: 1500.00
Gross Salary: 40500.00

#include <stdio.h>

int main() {
    float angle1, angle2, third_angle;

    // Assume angle1 is 90 (right angle)
    angle1 = 90.0;

    // Input one of the other angles
    printf("Enter one of the other angles of the triangle: ");
    scanf("%f", &angle2);

    // Calculate third angle
    third_angle = 180.0 - angle1 - angle2;

    // Output result
    printf("The third angle of the triangle is: %.2f degrees\n", third_angle);

    return 0;
}

3.
#include <stdio.h>

int main() {
    float angle1, angle2, third_angle;

    // Assume angle1 is 90 (right angle)
    angle1 = 90.0;

    // Input one of the other angles
    printf("Enter one of the other angles of the triangle: ");
    scanf("%f", &angle2);

    // Calculate third angle
    third_angle = 180.0 - angle1 - angle2;

    // Output result
    printf("The third angle of the triangle is: %.2f degrees\n", third_angle);

    return 0;
} 
Output 

Enter one of the other angles of the triangle: 45
The third angle of the triangle is: 45.00 degrees
