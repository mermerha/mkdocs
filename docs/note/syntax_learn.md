# mkdocs 学习

## 干活
### 吃饭
吃饭很重要
### 睡觉 
睡觉也很重要
### 喝水
喝水也很重要
### 横切面
横切面不是牛肉面也不是兰州拉面

## note
??? note
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    ``` python
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```

!!! note
    this is a note

??? info 
    this is a info

!!! tip
    this is a tip


## button

### 添加按钮
[Subscribe to our mailing list](#){: .md-button }
还有其他图形化的按钮
### 添加键盘键

这个是++ctrl+alt+del++  


## 分组

### 代码块分组
=== "C"

    ``` c
    #include <stdio.h>
    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>
    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

### 其他内容的分组
=== "Unordered list"

    * Sed sagittis eleifend rutrum
    * Donec vitae suscipit est
    * Nulla tempor lobortis orci

=== "Ordered list"

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

### 嵌入内容块中
??? example

    === "Unordered List"

        _Example_:

        ``` markdown
        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
        ```

        _Result_:

        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci

    === "Ordered List"

        _Example_:

        ``` markdown
        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci
        ```

        _Result_:

        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci


## 表格
| Method      | Description                          |
|:----------- |:------------------------------------ |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |


### footnote
Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit.[^2]
[^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
[^2]: gugugagaga

### 符号转换
- ==This was marked==
- ^^This was inserted^^
- ~~This was deleted~~
- H~2~0
- A^T^A


### emoji
:smile:从emojipedia中寻找

## image
![Placeholder](https://dummyimage.com/600x400/eee/aaa){: align=left }

:smile:这是一个smile