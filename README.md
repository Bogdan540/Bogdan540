#include <iostream>
#include <iomanip>

int main() {
    double t1, t2, t3;
    std::cin >> t1 >> t2 >> t3;

    // Розрахунок загальної швидкості
    double total_rate = (1.0 / t1) + (1.0 / t2) + (1.0 / t3);

    // Розрахунок часу
    double total_time = 1.0 / total_rate;

    // Вивід результату, округленого до 2 знаків після коми
    std::cout << std::fixed << std::setprecision(2) << total_time << std::endl;

    return 0;
}
