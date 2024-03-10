# Walnut App Template

This is a simple app template for [Walnut](https://github.com/TheCherno/Walnut) - unlike the example within the Walnut repository, this keeps Walnut as an external submodule and is much more sensible for actually building applications. See the [Walnut](https://github.com/TheCherno/Walnut) repository for more details.

## Getting Started
Once you've cloned, you can customize the `premake5.lua` and `WalnutApp/premake5.lua` files to your liking (eg. change the name from "WalnutApp" to something else).  Once you're happy, run `scripts/Setup.bat` to generate Visual Studio 2022 solution/project files. Your app is located in the `WalnutApp/` directory, which some basic example code to get you going in `WalnutApp/src/WalnutApp.cpp`. I recommend modifying that WalnutApp project to create your own application, as everything should be setup and ready to go.

## 项目配置
使用**VS 2022** 运行此项目

安装Vulkan
https://vulkan.lunarg.com/sdk/home

克隆项目
`git clone --recursive https://github.com/callightman233/RayTracing`

运行RayTracing\scripts中的`Setup.bat`

打开`RayTacing.sln`，使用`release`模式运行


## 操作解释
W:视角前移
A:视角左移
S:视角后移
D:视角右移

Q：物体水平上移
E：物体水平下移

鼠标右键:按住移动视线
鼠标右键按住 + A(D):切换视线角度 

Accumulate：勾选开始模拟
SlowRandom:取消勾选后开启随机数优化
