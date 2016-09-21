### 一、Emacs 基础

##### 1. 按键的基本概念
Emacs 很多操作通过键盘命令实现的，键盘命令是一些按键的组合。

- 组合键的种类
    - complete key，一次按键对应一个命令
    - prefix key，需要和其它键继续组合，才能对应一个命令，输入prefix key之后可以松开键盘，继续输入后续的键

- 两个重要的键
    - `C` windows 的 Ctrl 键
    - `M` windows 的 Alt 键

- 命令的基本形式
  - `C-<chr>` 表示当输入字符 `<chr>` 的同时，按住 Ctrl 键。比如 `C-f` 代表: 按住 Ctrl 键，再输入 f
  - `M-<chr>` 表示当输入字符 `<chr>` 的同时，按住 Alt 键。比如 `M-b` 代表: 按住 Alt 键，再输入 b
      - 特别需要注意的如果使用SecureCRT等远程终端，要确认终端是否吞掉了Alt键，因为Alt键被很多Windows程序用作菜单快捷键。

  - `C-<chr1> C-<chr2>`
    - `C-<chr1>` 是 prefix key, 表示输入字符 `<chr1>` 的同时，按住 Ctrl 键。输入完成可以松开键盘。
    - `C-<chr2>` 是 后续 key，表示输入字符 `<chr2>` 的同时，按住 Ctrl 键。

##### 2. Emacs 的进入与退出
- 进入
    - 命令行输入 `emacs` 即可进入 emacs 界面
    - 命令行输入 `emacs 文件名` 即可打开文件
- 退出
    - 命令行输入 `C-x C-c` 即可退出 emacs 界面
    -
