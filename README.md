# Brute Force Attack
```
#include <iostream>
#include <string>
using namespace std;
int main()
{
    string passcode;
    while (true) {
        cout << "Enter Passcode: " << endl;
        cin >> passcode;
        if (passcode != "246") {
            cout << "WRONG! Please Try again" << endl;
        }
        else {
            break;
        }
    }
    cout << "CORRECT! Congratz!" << endl;
}
```
# Brute Force Attack (5 Attempts)
```
#include <iostream>
#include <string>
using namespace std;
int main()
{
    string passcode;
    int attempt = 0;
    while (attempt < 5) {
        cout << "Enter Passcode: " << endl;
        cin >> passcode;
        if (passcode != "246") {
            cout << "WRONG! Please Try again" << endl;
            attempt++;
        }
        else {
            break;
        }
    }
    cout << "CORRECT! Congratz!" << endl;
}
```
# Input Improvement
```
```
# Loopy
```
```
