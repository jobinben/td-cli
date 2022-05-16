# td-cli

一个简易版脚手架：减少ctrl+c ctr+v的操作。可以直接生成api以及entity和对应的模块目录结构


## 安装

```shell
npm install -g td-cli
```

## 使用

1. 创建一个模块
   
```shell
td-cli add LoginAccount
```

2. 主入口为其他命名，或者是`List.vue`
```shell
td-cli add LoginAccount -m List
```

3. 查看版本
```shell
td-cli -v
```

4. 查看其余指令 
```shell
td-cli -h
```
