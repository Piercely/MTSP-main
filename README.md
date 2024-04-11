# ✨基于YOLOv8🚀的多端车流检测系统-MTAS (Multi-Platform Traffic Analysis System)

## ⚒️1、客户端环境配置

🚀**第一步 配置python环境**

> - 下载python（版本：python>=3.8）(建议使用访问Anaconda官网配置虚拟环境，具体步骤如下)
>
> - 1）访问Anaconda官网：https://www.anaconda.com/products/individual
>   2）选择相应的操作系统版本并下载对应的安装包（推荐下载64位版本）
>   3）打开下载的安装包，按照提示进行安装即可
>   4）创建一个虚拟环境：
>
>   ~~~
>   conda create --name 自命名 python=3.9.16
>   ~~~

🚀 **第二步 下载库**

> **注意：下载库前，如果想要更好的帧数体验请安装cuda版本哦(因为一般默认会安装cpu的版本)**
>
> - pip换源：
>
> - ~~~
>   pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
>   ~~~
>
> - 切换到项目文件夹下，下载依赖：
>
> - ~~~
>   pip install -r requirements.txt
>   ~~~
>
> - 我自己使用的环境：`python3.9+CPU`

🚀 **第三步 运行项目（如果不需要（开启网页端） 或 （对接RTSP））**

> - 可直接运行项目：python main.py
>
> 🚀**如果需要使用RTSP：**
>
> - 推荐手机安装app——`IP摄像头`
>
> 🚀**如果需要使用网页端：**
>
> - 可参考下面的配置说明


## ⚒️2、配置前端环境（使用网页端）

>🚀**第一步 配置npm与下载依赖**
>
>- 下载node.js（我使用的是16.4版本的）
>
>- npm换源：
>
>- ~~~
>  npm install -g cnpm --registry=https://registry.npm.taobao.org
>  ~~~
>
>- 切换到项目文件夹下，下载依赖：
>
>- ~~~
>  npm install
>  ~~~
>
>🚀**第二步 运行前端**
>
>- ~~~
>  npm run dev
>  ~~~

