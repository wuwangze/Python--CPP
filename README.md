该项目使用Python语言进行编写，通过调用本地gcc.exe文件从而实现对C语言代码的编译运行。
使用该项目时，请将gcc.exe文件与WWZ-CPP.py文件放在同一目录下，或者修改代码中的  compile_command = f"gcc.exe {current_file_path} -o {current_file_path}.exe"  gcc.exe将其改为真实物理路径。
