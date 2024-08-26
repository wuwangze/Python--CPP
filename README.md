该项目使用Python语言进行编写，通过调用本地gcc.exe文件从而实现对C语言代码的编译运行。

使用该项目时，请将gcc.exe文件与WWZ-CPP.py文件放在同一目录下，或者修改代码中的 
# compile_command = f"gcc.exe {current_file_path} -o {current_file_path}.exe"  gcc.exe
将其改为真实物理路径。

该项目和vscode有同样的问题，在编译运行C语言代码后，弹出的运行代码会闪退，解决办法放在了“示例代码”文件中

特仑苏曾经说过，不是所有的功能，都是可以使用的功能，部分功能没有完善，只是徒有虚表

# 注意，程序窗口顶部的“文件”和“编辑”也是可以点击的按钮！
