#include <stdio.h>

int main()
{
    float heart_rate;

    printf("Enter heart rate in BPM: ");
    scanf("%f", &heart_rate);

    if (heart_rate < 60)
    {
        printf("Low Heart Rate");
    }
    else
    {
        if (heart_rate <= 100)
        {
            printf("Normal Heart Rate");
        }
        else
        {
            printf("High Heart Rate");
        }
    }

    return 0;
}
