<!--
 * @Author: wzdnzd
 * @Date: 2022-03-06 14:51:29
 * @Description: 
 * Copyright (c) 2022 by wzdnzd, All Rights Reserved.
-->

## 功能
打造免费代理池，爬一切可爬节点
> 拥有灵活的插件系统，如果目标网站特殊，现有功能未能覆盖，可针对性地通过插件实现

> 欢迎 Star 及 PR。对于质量较高且普适的爬取目标，亦可在 Issues 中列出，将在评估后选择性添加

## 使用方法
> 略，自行探索。我才不会告诉你入口是 `collect.py` 和 `process.py`。**强烈建议使用后者，前者只是个小玩具**，配置参考 `subscribe/config/config.default.json`

>安装依赖：pip3 install pyYAML tqdm

>运行代码：终端里进入到项目的 aggregate 目录下，执行命令 python -u subscribe/collect.py -s

>等待运行结束，最终会得到 4 个文件：

>clash.yaml：实际可用的代理节点

>subscribes.txt：订阅地址列表

>valid-domains.txt：支持免费白嫖的机场列表

>domains.txt：支持临时邮箱或无需验证邮箱的机场列表

## 免责申明
+ 本项目仅用作学习爬虫技术，请勿滥用，不要通过此工具做任何违法乱纪或有损国家利益之事
+ 禁止使用该项目进行任何盈利活动，对一切非法使用所产生的后果，本人概不负责
