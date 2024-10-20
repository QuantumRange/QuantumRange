```cpp
int main() {
    for (long* i = 0; std::intptr_t(i) < INT64_MAX; ++i) {
        *i = 0;
    }

    return 0;
}
```
