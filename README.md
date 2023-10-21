# 普中STC89C51RC开发板小项目

## 环境依赖

keil

stc-isp 串口下载工具

## 部署步骤

1. 添加系统环境变量
    export $PORTAL_VERSION="production" // production, test, dev


2. npm install  //安装node运行环境

3. gulp build   //前端编译

4. 启动两个配置(已forever为例)
    eg: forever start app-service.js
        forever start logger-service.js

## 目录结构描述

```text
├── Project_1		//51项目
├── Project_2
│   ├── Hardware		//硬件驱动函数,诸如LCD1602
│   ├── Library			//便利函数,诸如Delay()
│   ├── Listings		//
│   ├── Objects			//hex文件在这里
│   ├── Picture			//项目实拍图
│   ├── System			//
│   ├── User			//主要code区,例如main.c
│   └── Project.uvproj			//keil project
├── Project_3
└── README.md
```

 

## V0.1.0 版本内容更新

1. 新功能     可调实时闹钟