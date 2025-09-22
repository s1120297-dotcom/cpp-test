# cpp-test#include <iostream>
#include <iostream>
using namespace std;

int main() {
    // 宣告變數
    double fahrenheit, celsius;
    
    // 提示使用者輸入華氏溫度
    cout << "請輸入華氏溫度：";
    cin >> fahrenheit;
    
    // 計算攝氏溫度
    celsius = (fahrenheit - 32) * 5.0 / 9.0;
    
    // 輸出結果
    cout << "對應的攝氏溫度是：" << celsius << "°C" << endl;
    
    return 0;

}

