#include <stdio.h>

int main() {
    double t1, t2, t3;
    
    // Ввод значений t1, t2, t3
    scanf("%lf %lf %lf", &t1, &t2, &t3);
    
    // Производительность каждого гостя
    double rate1 = 1 / t1;
    double rate2 = 1 / t2;
    double rate3 = 1 / t3;
    
    // Общая производительность
    double total_rate = rate1 + rate2 + rate3;
    
    // Время, необходимое для съедания одного пирога
    double total_time = 1 / total_rate;
    
    // Вывод результата с округлением до двух знаков после запятой
    printf("%.2f\n", total_time);
    
    return 0;
}
