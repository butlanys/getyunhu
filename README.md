# 用cli查看云湖社交app 群组 / 用户 的信息

## 正常输出
```
root@armbian:~# ./getyunhu-linux-arm64 7058262
请输入用户ID或群ID(输入exit或ctrl+d退出)
[7058262 Feng(工作中) 2021-12-16 12:00:26]
```

## json输出
```
root@armbian:~# ./getyunhu-linux-arm64 7058262 -j
请输入用户ID或群ID(输入exit或ctrl+d退出)
{"userId":"7058262","userName":"Feng(工作中)","registerTime":"2021-12-16 12:00:26"}
```
## 交互
```
root@armbian:~# ./getyunhu-linux-arm64
请输入用户ID或群ID(输入exit或ctrl+d退出)
>7058262
[7058262 Feng(工作中) 2021-12-16 12:00:26]
>
退出程序
```
