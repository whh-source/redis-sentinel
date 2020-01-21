# redis-sentinel 
Spring boot redis - 哨兵模式 (重写 RedisTemplate)


#### 1,  采用哪个 客户端做连接
    lettue 
    
#### 2，重写 RedisTemplate的好处
    可以打开写主读从。
    
#### 3，注意
    配置哨兵时，别把master ip 配成127.0.0.1了。远程会连不上
   