 <center>
     
```cpp
#include <iostream>
using namespace std;

int main() {
    string languages[] = {"C++", "Python"};
    int size = sizeof(languages) / sizeof(languages[0]);
    cout << "i write ";
    for(int i = 0; i < size; i++) {
        cout << languages[i];
        if(i < size - 1) cout << ", ";
    }
    cout << ".\n";
    return 0;
}
```

</center>
