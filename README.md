# Readme
A note about Event-driven Procedure-arranged Programming.

现实是由事件驱动的，而任务是由过程编排的。所以，应该按照事件驱动的范式进行编程，同时在注册事件处理器中反映执行任务的过程。有两点需要注意：
- 第一，要求程序中存在事件侦听器，当其侦听到注册事件发生时，要调用对应的注册事件处理器。
- 第二，要求通过注册事件处理器的嵌套层次反映执行任务的过程。
