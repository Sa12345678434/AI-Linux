# AI-Linux

## Task description
In this task, a flowchart of file permissions is created and the permissions of Python file are changed to __rwxrwxr-x__

## Softwares used
1. Ubuntu
2. Visual Studio
3. Word

## image for flowchart 

![image_alt](https://github.com/Sa12345678434/AI-Linux/blob/main/flowchart.png?raw=true)

## Steps to change permission for Python file

### The first method (writing code inside Python script)
1. create file in terminal named t2.py
2. writing command: __ls -l__ to view file permissions  
### image for Python file permissions (before change)
![image_alt](https://github.com/Sa12345678434/AI-Linux/blob/main/python1.jpeg?raw=true)

3. open Visual Studio > open file > t2.py
4. Writing code to change permission of Python file using __chmod__ command
```import os

 os.chmod("t2.py",0o775)```



