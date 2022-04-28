# STM32_Project_Build
>stm32工程建立
* **CMISS文件夹创建**

在**CMISS文件夹**中存放的是我们**内核控制**相关的文件，这里还放了**启动文件**

* **FWLIB文件夹创建**

**FWLIB文件夹**是存放ST**标准库文件**的地方，里面有ST编写的提供给用户调用的规范化代码，例如对引脚口、系统时钟、DMA等等的操作

inc存放头文件，src存放的是源文件

* **Project文件夹创建**

  **Project文件夹**主要放置的是通过keil5创建项目生成的文件，像.uvprojx就是工程文件，以及一些输出文件，这些文件都是创建工程时keil自动生成的文件和文件夹，我们只需要建立一个文件夹存放keil编译时的输出文件即可。
  
 
* **USER文件夹创建**

**USER文件夹**存放用户代码，我们这里先在里面新建main.c文件供后续keli工程建立时使用

* USERLIB文件夹

* DEVICE文件夹

存放**外设**相关文件
>如can、gpio、usart、timer等
* HARDWARE文件夹

存放**硬件**相关文件
>如MPU陀螺仪、remoter遥控器等

———————————————————————————————————————
>参考文章：[keil5新建STM32工程文件--实践篇手把手教学（以STM32F103为例）](http://t.csdn.cn/cSs8x)

---
**此外还要添加：**
* Define：`STM32F427_437xx,USE_STDPERIPH_DRIVER`
* 头文件路径
