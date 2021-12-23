# vector-4
## code
```
#include <iostream>
#include <vector>

int main()
{   
    int n;
    std::vector<int> v;
    std::cin >> n;
    for (int i = 0; i < n; i++)
    {
        v.push_back(i);
    }
    std::cout<< sizeof(std::vector<int>) + (sizeof(int) * v.size());
}
```
