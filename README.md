# debug
Debug log lib

Usage example:

```c
//>>---------------------- Log control
#define LOG_MODULE_NAME exmpl
#define LOG_MODULE_LEVEL (4)
#include "debug/log_libs.h"
//<<----------------------

int main(void)
{
    LOG_INFO("Hello");

    return 0;
}
```
