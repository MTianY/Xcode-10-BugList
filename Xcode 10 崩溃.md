# Xcode 10 崩溃

今天升级 Xcode 10 之后,老项目直接崩溃,原因如下: 

##### 错误原因: 

![](media/15366461122075/15372630830512.jpg)


#### 解决办法:

找到 `Build Phases` ---> `[CP]Copy Pods Resources`, 然后删除 `Output Files 里的` 


![](media/15366461122075/15372637878865.jpg)


