//Задача А 
#include <iostream> 
using namespace std; 
int main() { 
    int h, m; 
    cin >> h >> m; 
    int real_hour = 12 - h; 
    if (real_hour == 12) { 
        real_hour = 0; 
    } 
    int real_minute = 60 - m; 
    if (real_minute == 60) { 
        real_minute = 0; 
    } 
    cout << real_hour << " " << real_minute << endl; 
    return 0; 
}
