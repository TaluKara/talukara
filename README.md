```cpp
#include <iostream>
using namespace std;

int main() {
    string languages[2] = {"C++", "Python"};
    int size = sizeof(languages) / sizeof(languages[0]);
    cout << "I write ";
    for(int i = 0; i < size; i++) {
        cout << languages[i];
        if(i < size - 2) { cout << ", "; }
        else if(i == size - 2) { cout << ", "; }
        else { cout << ".\n"; }
    }
    return 0;
}

```