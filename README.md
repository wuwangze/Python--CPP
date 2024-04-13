该项目使用Python语言进行编写，通过调用本地gcc.exe文件从而实现对C语言代码的编译运行。

使用该项目时，请将gcc.exe文件与WWZ-CPP.py文件放在同一目录下，或者修改代码中的  compile_command = f"gcc.exe {current_file_path} -o {current_file_path}.exe"  gcc.exe将其改为真实物理路径。


该项目遇到了和vscode同样的问题，在编译运行C语言代码后，弹出的运行代码会闪退，解决办法放在了“示例代码”文件中
