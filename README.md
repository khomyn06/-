#include <stdio.h>
    
int main() {
    double t1, t2, t3;
    
    scanf("%lf %lf %lf", &t1, &t2, &t3);
    
    double rate1 = 1 / t1;
    double rate2 = 1 / t2;
    double rate3 = 1 / t3;
  
    double total_rate = rate1 + rate2 + rate3;
    
    double total_time = 1 / total_rate;
    
    printf("%.2f\n", total_time);
    
    return 0;
}
