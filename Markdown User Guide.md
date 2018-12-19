---
title: Pandoc-Markdown 用户手册
author: 刘军
date: \today
CJKmainfont: Heiti SC
mainfont: Helvetica
fignos-cleveref: True
fignos-plus-name: 图
fignos-caption-name: 图
...

# 表格
## Grid Table
+---------------+---------------+--------------------+
| Fruit         | Price         | Advantages         |
+===============+===============+====================+
| Bananas       | $1.34         | - built-in wrapper |
|               |               | - bright color     |
+---------------+---------------+--------------------+
| Oranges       | $2.10         | - cures scurvy     |
|               |               | - tasty            |
+---------------+---------------+--------------------+


: Sample grid table.

+---------------+---------------+--------------------+
| Fruit         | Price         | Advantages         |
+===============+===============+====================+
| Bananas       | $1.34         | - built-in wrapper |
|               |               | - bright color     |
+---------------+---------------+--------------------+
| Oranges       | $2.10         | - cures scurvy     |
|               |               | - tasty            |
+---------------+---------------+--------------------+

## Simple Table
  Right     Left     Center     Default
-------     ------ ----------   -------
     12     12        12            12
    123     123       123          123
      1     1          1             1

: Demonstration of simple table syntax.{#tbl:simple}

## multiline tables

-------------------------------------------------------------
 Centered   Default           Right Left
  Header    Aligned         Aligned Aligned
----------- ------- --------------- -------------------------
   First    row                12.0 一个行跨
                                    多行的例子

  Second    row                 5.0 这是另一行
                                    注意表格行与行
                                    之间的空行哦~~
-------------------------------------------------------------



| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |


# 代码
## C++ Example
```C++
#include <iostream>
using namespace std;
int main(int argc, char* argv[])
{
    cout << "Hello,Markdown!" << endl;
    return 0;
}
```

## Python Example
```Python
import os
import sys

# Entry
if __name__ == '__main__':
    print("Hello,Python!")
```

## Java Example
```Java
class Example{
  public static void Main(String[] args){
    System.out.println("Hello,Java!");
  }
}
```
# 插图
