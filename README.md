#Husky 简易C++的HTTP服务框架

## 主要模块：

### ServerFrame.cpp/h

ServerFrame主要是一个http服务的socket通信框架，这个ServerFrame需要传入IRequestHandler这个接口类。   
当每次有http请求进来时，会调用IRequestHandler这个类的相关函数进行处理。   

### HttpReqInfo.cpp/h 

http参数的解析

