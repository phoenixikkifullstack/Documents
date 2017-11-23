# 语法高亮与代码行数

1. 你可以给你的代码块添加任何一种语言的语法高亮
2. 如果你想要你的代码块显示代码行数，只要添加 line-numbers class 就可以了。
例如：
```cpp {.line-numbers}
#include <stdio.h>
int main(int argc, char *argv[])
{
    int i;
}
```
```bash {.line-numbers}
export EMICALLDEV_SOURCE_ROOT
export MYSQL_LIB="`mysql_config --libs_r`"
export MYSQL_CFLAGS="`mysql_config --cflags`"
#export EMICALLDEV_CFLAGS="-O3 -Werror"
export EMICALLDEV_CFLAGS="-O -g -Werror -Wno-deprecated-declarations"
