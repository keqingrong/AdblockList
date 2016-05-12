在Mac OS X中：
1. 默认只有一个`.bash_history`文件，而没有`.bash_profile`和`.bashrc`文件。
2. 打开Terminal，默认的bash是以login shell的形式运行的，所以只会读取`~/.bash_profile`。

> `login shell`会读取`.bash_profile`
> `non-login shell`会读取`.bashrc`
