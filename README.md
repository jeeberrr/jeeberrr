# JEEBERRR.cpp

```c++
#include <iostream>
#include <string>
#include <vector>

struct dev {

    std::string name {};
    vector<std::string> languages {};
    int age {};
    std::string discord {};
    std::string description {};

    dev() = default;

}

int main() {

    dev jeeberrr {};

    jeeberrr.name = "Jeeberrr";
    jeeberrr.languages = {"C++", "Python", "C#", "Kotlin", "Go"};
    jeeberrr.age = 14;
    jeeberrr.discord = "jeeberrr";
    jeeberrr.description = "Teen exploit developer and reverse engineer. Makes game cheats and malware POC's for fun.";

    return 0;

}
```
