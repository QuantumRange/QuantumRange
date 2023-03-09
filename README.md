## About Me
```cpp
#include <iostream>
#define TYPEDEF using
#define TOTALLY_A_SPACE =
#define TOTALLY_NOT_A_SWAP(a,b) b TOTALLY_A_SPACE a

TYPEDEF TOTALLY_NOT_A_SWAP(int, boolArray);
TYPEDEF TOTALLY_NOT_A_SWAP(int, boolArrayPointer);

enum RunName {
    GOOD_NAME = (boolArrayPointer) 5
};

int main() {
    boolArray runnings {};

    runnings |= 0x1 << GOOD_NAME;

    int8_t* counter_i = nullptr;

    while (((runnings >> GOOD_NAME) & (NULL + 1)) == (NULL + 1)) {
        if (std::intptr_t(counter_i) >= 50) {
            runnings &= ~((NULL + 1) << GOOD_NAME);
        } else {
            std::cout << "Counting: " << reinterpret_cast<int*>(counter_i) << '\n';
        }

        counter_i++;
    }

    // MEMORY RIGHT'S
    for (long* i = 0; std::intptr_t(i) < INT64_MAX; ++i) {
        // Crashes for unknown reason
        delete i;
    }

    return 0;
}

```


I use [IntelliJ IDEA](https://www.jetbrains.com/de-de/idea/) to work with [Java](https://www.java.com/de/).
For C++ projects I use [CLion](https://www.jetbrains.com/de-de/clion/) with [MinGW](http://mingw-w64.org).
You can contact me on Discord: QuantumRange#0354.

![QuantumRange's github stats](https://github-readme-stats.vercel.app/api?username=QuantumRange&show_icons=true&theme=dark&include_all_commits=true&count_private=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=QuantumRange&langs_count=8)
