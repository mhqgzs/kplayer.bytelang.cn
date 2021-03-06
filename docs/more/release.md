---
title: 发布历史
---

发布历史
===

## v0.3.7
2020-7-16
* 添加-g参数，提供预生成缓存文件功能
* 添加可指定缓存输出路径配置
* 修复多插件加载造成动态链接库访问非法(segmentation fault)问题
* 修复多插件偶发性加载时序问题造成的死锁情况
* 修复通过api添加视频资源索引值无效的问题

> [kplayer-v0.3.7-linux_amd64.tar.gz](http://download.bytelang.cn/kplayer-v0.3.7-linux_amd64.tar.gz)

## v0.3.6
2020-4-1
* 接入可信任插件商城。在配置文件中配置完成插件，kplayer将会自动从插件商城拉取插件文件并自动加载。节省手动下载插件的麻烦
* 修复ApiServer在异常情况下的segment fault空指针问题
* 修复Api接口Content-Type返回类型无效的问题，解决浏览器访问接口造成接口数据当做文件下载的问题
> [kplayer-v0.3.6-linux_amd64.tar.gz](http://download.bytelang.cn/kplayer-v0.3.6-linux_amd64.tar.gz)

## v0.3.4
2020-1-6
* 增加依赖资源自动校验下载功能，避免文件必须携带资源文件的不便性
* 修复一赔高版本glibc的问题，解决某些机器上无法运行的错误
> [kplayer-v0.3.4-linux_amd64.tar.gz](http://download.bytelang.cn/kplayer-v0.3.4-linux_amd64.tar.gz)

## v0.3.0
2019-12-26
* 增加kplayer的RESTful风格的api管理接口
* 增加媒体文件缓存，避免重复的编解码操作。大幅降低CPU与内存资源占用
> [kplayer-v0.3.0-linux_amd64.tar.gz](http://download.bytelang.cn/kplayer-v0.3.0-linux_amd64.tar.gz)

## v0.2.3
2019-12-05
* 添加程序启动基础信息输出
* 添加插件版本号判断
* 修复断线重连造成的不稳定情况
* 添加播放列表起始索引配置参数
> [kplayer-v0.2.3-linux_amd64.tar.gz](http://download.bytelang.cn/kplayer-v0.2.3-linux_amd64.tar.gz)

## v0.2.1
2019-12-03
* 修改日志默认级别
* 修复插件异步加载与系统无关性
* 修复filter上下文内存泄漏问题
> [kplayer-v0.2.1-linux_amd64.tar.gz](http://download.bytelang.cn/kplayer-v0.2.1-linux_amd64.tar.gz)

## v0.2.0
 2019-11-23
 * 增加插件模块、增加插件加载功能
 * 增加配置文件向插件参数传参功能
 * 修复插件加载造成的内存泄漏问题
 > [kplayer-v0.2.0-linux_amd64.tar.gz](http://download.bytelang.cn/kplayer-v0.2.0-linux_amd64.tar.gz)

## v0.1.4
 2019-11-07
 * version 0.1.4已发布，作为kplayer的第一个可执行版本。提供基础的每天资源转码、推流、无缝推流多个媒体资源等功能。有以下更新：
 * 提供配置文件对程序参数进行配置
 * 提供Linux amd64平台静态链接版本，不包含任何依赖库。可直接下载并在目标机器执行
 * 添加配置转码质量参数
 > [kplayer-v0.1.4-linux_amd64.tar.gz](http://download.bytelang.cn/kplayer-v0.1.4-linux_amd64.tar.gz)