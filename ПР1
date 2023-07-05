#include <stdio.h>
#include <math.h>

int main() {
    int t1, t2, t3;
    scanf("%d %d %d", &t1, &t2, &t3);

    float speed1 = 1.0 / t1;
    float speed2 = 1.0 / t2;
    float speed3 = 1.0 / t3;

    float total_speed = speed1 + speed2 + speed3;

    float total_time = 1.0 / total_speed;

    float rounded_time = roundf(total_time * 100) / 100; // Округлюємо до двох знаків після коми

    printf("%.2f\n", rounded_time);

    return 0;
}
