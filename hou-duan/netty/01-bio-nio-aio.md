# 01 BIO、NIO、AIO

阻塞与非阻塞：线程访问资源，该资源是否准备就绪的一种处理方式。阻塞会一直等待资源就绪，而非阻塞会立即响应结果，先处理其他资源。

同步和异步：访问数据的一种机制。

![&#x963B;&#x585E;&#x4E0E;&#x975E;&#x963B;&#x585E;](https://raw.githubusercontent.com/chanshiyucx/yoi/master/2019/BIO-NIO-AIO/01_阻塞与非阻塞.png)

![&#x540C;&#x6B65;&#x4E0E;&#x5F02;&#x6B65;](https://raw.githubusercontent.com/chanshiyucx/yoi/master/2019/BIO-NIO-AIO/02_同步与异步.png)

![BIO](https://raw.githubusercontent.com/chanshiyucx/yoi/master/2019/BIO-NIO-AIO/03_BIO.png)

![NIO](https://raw.githubusercontent.com/chanshiyucx/yoi/master/2019/BIO-NIO-AIO/04_NIO.png)

![AIO](https://raw.githubusercontent.com/chanshiyucx/yoi/master/2019/BIO-NIO-AIO/05_AIO.png)

![&#x751F;&#x6D3B;&#x5B9E;&#x4F8B;](https://raw.githubusercontent.com/chanshiyucx/yoi/master/2019/BIO-NIO-AIO/06_生活实例.png)

![&#x4E09;&#x8005;&#x533A;&#x522B;](https://raw.githubusercontent.com/chanshiyucx/yoi/master/2019/BIO-NIO-AIO/07_三者区别.png)

## Reactor 线程模型

![&#x5355;&#x7EBF;&#x7A0B;&#x6A21;&#x578B;](https://raw.githubusercontent.com/chanshiyucx/yoi/master/2019/BIO-NIO-AIO/08_单线程模型.png)

![&#x591A;&#x7EBF;&#x7A0B;&#x6A21;&#x578B;](https://raw.githubusercontent.com/chanshiyucx/yoi/master/2019/BIO-NIO-AIO/09_多线程模型.png)

![&#x4E3B;&#x4ECE;&#x7EBF;&#x7A0B;&#x6A21;&#x578B;](https://raw.githubusercontent.com/chanshiyucx/yoi/master/2019/BIO-NIO-AIO/10_主从线程模型.png)

