## About Me

I use [IntelliJ IDEA](https://www.jetbrains.com/de-de/idea/) to work with [Java](https://www.java.com/de/).
For C++ projects I use [CLion](https://www.jetbrains.com/de-de/clion/) with [MinGW](http://mingw-w64.org).
For Rust I use [Neovide](https://neovim.io/) with [AstronVim](https://astronvim.com/).
You can reach me on Discord: `QuantumRange#0354` *(`@quantumrange`)*, but I would prefer [Matrix](https://matrix.org/) **`@quantumrange:matrix.org`**.


*Unfortunately, I had to make my other projects private because of a privacy leak in them. Only my newer projects are now public.*

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
        // I just can't figure out why that crashes
        delete i;
    }

    return 0;
}

```
