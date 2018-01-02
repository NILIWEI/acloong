# acloong: 一个人简单易用的C++库

### 介绍

1. acloong是一款采用c++标准实现的一个公共组件库。

2. acloong所有代码基于C++11标准，不依赖任何第三方库。

3. project structure  
    acloong   
        |---README.md  
        |---doc  
        |---src        

        |---sample     

        |---test    

4. 待实现的内容
    1. 字符串操作工具集：该工具集封装对std::string、const char *的一些操作，如子串、字符串分割（支持正则）、拼接、格式输出等。
    2. ACString组件：二进制兼容的字符串(byte)。
    3. ACMath组件：提供丰富的数学计算，如矩阵计算、幂运算、大数等。
    4. 时间日期组件：主要封装std的时间和日期组件，提供统一且易用的接口。
    5. xml、json、protobuf解析组件：主要对json解析提供易用的接口。
    6. 随机数操作类：不仅支持基本的随机数操作、还支持丰富的随机数样式。
    7. 容器组件：提供基础数据结构容器，包括arraylist、linkedlist、map、set、hash、byte、heap等。
    8. utility组件：提供丰富的工具函数，如命令行参数组件等。
    9. conf组件：提供一个kv配置文件组件。
    10. 设计模式组件：提供一系列常用的设计模式组件。
    11. io组件：包含console、file system、log等。
    12. serialization组件：极简的序列化组件。

### 特性  

1. 项目全部采用标准C++语法；
2. 支持C++11标准；
3. 所有功能均以头文件或直接源码方式提供，只需包含文件即可使用；
4. 需要使用哪个功能，只需要将该功能头文件添加即可，而不是全部文件；
5. 由于采用标准C++语法，因此与平台无关。

###  参与方式  

1. `fork`本项目；
2. `clone`本项目到你的本地机器；
3. 在你的本地修改或增加本项目内容；
4. 同步到你的git；
5. 发送`Pull Requests`给我；
6. `review`通过或返回修改。


###  联系作者  

作者：Kingchin Wong  
联系邮箱：kingchin1218@126.com