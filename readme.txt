1、移除工程中.h文件
2、更改Target为Project
3、更改uCOS-III为只读，将Port中IAR编译器和TrueSTUDIO 删除，保留RealView完整路径，以确定内核类型
4、更改Device为STM32F407ZGTx
5、更改STM32F4xx为只读，并移动至【根目录】下
6、将cstartup.s文件更改为只读，并移动至uC/CPU下
7、将开发板路径改为项目路径，Projects