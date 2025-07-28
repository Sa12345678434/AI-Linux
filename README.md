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

```import os```

 ```os.chmod("t2.py",0o775)```

775: This number represent the permissions I want to set where:

 r=4, w=2 , x=1
 1. r+w+x=7 (Owner)
 2. r+w+x=7 (Group)
 3. r+x=5 (All users)


5. run program then open terminal
6. writing __ls -l__ to view file permissions

### image for Python file permissions (after change)
![image_alt](https://github.com/Sa12345678434/AI-Linux/blob/main/python2.jpeg?raw=true)

