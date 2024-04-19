# menifest

## 📃 说明

一群`臭·搞技术`的不知道是哪里的逆向源代码，错误的搭建了一个GitHub项目。

## 🥗 食用

下载本项目里的`docker-compose.yml`到你想要的目录。

根据自己的阶段进行执行对应的服务。

### 🌰 栗子

#### 初始化

就只保留`init`服务，然后执行`docker-compose up`并等待结束。

#### 同步代码

和`初始化`一样，仅保留`sync`服务，然后再执行`docker-compose up`并等待结束。

#### OpenGrok

开启端口在`1103`，如果您是本机服务，[新建窗口直达](http://localhost:1103)。

> 提示
>
> 1103端口是有意义的，有兴趣的可以自行查找。

## ❓ 看不懂？

那说明这个项目本来就不是为你服务的，请按下`Alt+F4`来打开帮助。

## 🍭 提示

因为[Grok](https://hub.docker.com/r/opengrok/docker)只提供`Linux x64`的镜像，所以这个项目只能在`Linux x64`平台上运行。

