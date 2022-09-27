# 计算机体系结构

cpu: alu

register

R 1/2 cache

ram & rom

disk

bus: addr-bus & data-bus

network-card

router

electric signal

base station

optical fiber & cable & wifi

化学 ： 硅片, 光纤材料等的组成元素

材料学: 光纤材料，电缆材料等

物理学: 电路，电信号

# 网络

我们写的网络代码 调用 语言对网络封装的 socket API， 完成数据包的发送和接收

操作系统将传输层数据包加上IP头后发送到网卡

网卡把数据发送到指定路由器(需要操作系统调度么？)

传输层数据包

传输层属于网络分层模型

程序利用操作系统线程 给 给/从网卡发送/接收数据

操作系统线程调度 CPU 完成1组指令的操作

这组指令的操作的是内存或硬盘或寄存器里面的数据
