boost 1.59 编译：
找不到Python.h，这是因为没有安装python-de， 使用yum search python |grep devel找到了可用版本。python-devel.x86_64 : The libraries and header files needed for Python                     : development

解决办法

一、执行：yum  install python-devel.x86_64
