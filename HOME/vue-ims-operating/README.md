# 运营后台管理系统

## Prepare 

1. 先安装[node.js](https://nodejs.org),安装完成之后执行如下命令验证是否安装成功

```bash
> node -v //输出 `v8.11.1`
> npm -v //输出 `5.6.0`
```

2. 设置npm的远程镜像源为国内快速源

```bash
> npm set registry https://registry.npm.taobao.org/
```

3. 全局安装工具包`yarn`、`webpack`、`webpack-cli`

```bash
> npm i -g yarn webpack webpack-cli 
```

检测`yarn`是否安装成功
```bash
> yarn -v //输出`1.5.1`
```

## Build Setup

``` bash
# 启动服务
npm run serve
```


## 疑问

1. 如果动态的绑定到路由，

   1) 启动nodejs服务的时候先获取数据库对应的路由映射关系;
   2) 然后封装跳转页面的方法;
   3) 