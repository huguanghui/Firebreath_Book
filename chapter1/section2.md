# 1.2 准备工作

### 需要下载的文件
- firebreath的源代码, boost库
- python
- CMake

### 链接地址
[firebreath的github地址](https://github.com/firebreath)

### 创建工程步骤
- a.从github上下载firebreath源码

    git cloeng git://github.com/firebreath/FireBreath firebreath

- b.安装第三方bootst库

    git submodule update --recursive --init

- c.创建项目工程

    python.exe fbgen.py

- d.创建VS工程

    move project ..
    cd ..
    .\firebreath\prep2015.cmd project build