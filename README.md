# STM32-Template

1. Frequently Used STM32 Templates.
2. STM32F103C8T6 Project Template——20240831
3. 关于移植的一些问题——20240902
	- 以改为 **STM32F103C8T6** 举例
		1. “Options for target > devices”选项下需要选择芯片型号为“STM32F103C8”.
		2. “Options for target > C/C++”选项下的STM32宏需要使用“STM32F10X_MD”（不含引号）.
		3. 工程的启动文件组 “STARTUP”下需要使用文件“startup_stm32f10x_md.s”.

![STM32F103C8T6移植相关](https://github.com/Siyuan-Wang-UP/STM32-Template/blob/main/Picture/%E5%85%B3%E4%BA%8E%E7%A7%BB%E6%A4%8D.png)

4. STM32命名规则

![STM32命名规则](https://github.com/Siyuan-Wang-UP/STM32-Template/blob/main/Picture/%E5%91%BD%E5%90%8D%E8%A7%84%E5%88%99.png)

