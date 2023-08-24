## WindowRect



|            |                                          |                |
| ---------- | ---------------------------------------- | -------------- |
| WindowRect | 框选鼠标当前位置窗口范围（类似窗口截图） | Windows、Linux |



**修改:** 工程由 QMake 修改为 CMake，且修改编码，使得能够在 如下环境 win10 22H2 + Qt 5.15.2 + QtCretor + msvc2022； 编译成功。





**逻辑：** 使用 鼠标穿透，故使用钩子， 获取窗口信息简单，但是获取无法自定义详细的过滤；和自己写的对比，取长补短参考使用。





Ref: https://github.com/mahuifa/QMDemo/blob/master/FunctionalModule/FunctionalModule.md