 <center>
     
```cpp
#include <iostream>
using namespace std;

int main() {
    string languages[] = {"X86 Assembly", "Bash", "C", "C++", "JavaScript", "PHP", "Python"};
    int size = sizeof(languages) / sizeof(languages[0]);
    cout << "I write ";
    for (int i = 0; i < size; i++) {
        cout << languages[i];
        if (i < size - 2) {
            cout << ", ";
        } else if (i == size - 2) {
            cout << " and ";
        }
    }
    cout << ".\n";
    return 0;
}

```

</center>
