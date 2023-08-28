<div align="center">

[![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)](#lingpt)

<h1 align="center">LinGPT</h1>

<p align="center">A GPT-4 Webpage with Just a Single HTML File</p>

<p align="center">只有一个html文件的 GPT4 聊天网页</p>

<p align="center">
  <a href="https://github.com/lin2025/gpt4/"><img height="22" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="Github"></a>
  <a href="https://gitee.com/lin2025/gpt4/"><img height="22" src="https://img.shields.io/badge/Gitee-C71D23?style=for-the-badge&logo=gitee&logoColor=white" alt="Gitee"></a>
</p>

[Demo](https://lin2025.github.io/gpt4/) • 
  [Download](https://github.com/lin2025/gpt4/archive/refs/heads/main.zip) • 
  [网盘下载](https://lin2025.github.io/#gpt3.5-code)

Give a Star 🌟 if you like it.

[![](https://lin2025.github.io/img/other-0705.gif)](#lingpt)

</div>


👉 The GPT-4 repository is a duplicate of the ChatGPT repository, completely identical.

👉 LinGPT - ChatGPT: https://github.com/lin2025/gpt3.5 

[![English](https://img.shields.io/badge/English-Readme-success)](#lingpt-1)

## LinGPT
 - LinGPT is a lightweight single-page chat application that can be deployed statically, with no need for a server.
 - Can be uploaded to any static website hosting platform like GitHub and provides a very smooth browsing experience.
 - Download and open the <kbd>index.html</kbd> file on your computer, input API Key to get started.
 - Supports OpenAI API and Third-party APIs (reverse proxy). 
 - Supports the latest GPT-3.5 and GPT-4 models.
 - Supports both OpenAI API Key and Third-party proxy keys. Supports fully automatic intelligent rotation of API keys. 
 - User data is stored only in the browser's local cache, supporting export, import, and deletion. 

## Demo

[https://lin2025.github.io/gpt4/](https://lin2025.github.io/gpt4/)


## Features

> This code does not use streaming response, GPT will generate the complete response text at once.

 - **New Features**: Contextual mode.
 - **New Features**: Support for third-party API keys, optimized for compatibility with third-party proxy platforms.
 - **New Features**: Support for all models of GPT-3.5 and GPT-4.
 - **New Features**: Supports Automatic Retry (intelligently determines whether to retry when a request fails).
 - **New Features**: Supports Auto Key Rotation, intelligently rotates API keys, supports bulk addition.
 - **New Features**: Page Scaling (For Mobile).
 - **New Features**: Multiple chats management, automatic saving, copy creation, data synchronization, export (for backup / sharing), import (restore chat data).
 - **New Features**: Support for browser local storage, with operations including data synchronization, import, export, deletion, and statistics.
 - Smart max_tokens (Automatically adjusts the max_tokens)
 - API key, OpenAI API balance inquiry, custom API endpoint, custom API requests (model, max_tokens, temperature, top_p, presence_penalty, frequency_penalty.).
 - Markdown support (code block, syntax highlighting, displaying images, displaying tables, article formatting, etc.).
 - system prompt, token statistics, one-click copy, automatic parsing of OpenAI error codes, function help.
 - Undo, Retry, Clear Context, and supporting keyboard shortcuts.
 - Supports English and Chinese-Simplified, custom avatars (supports Upload Avatar), custom style (font size, WeChat-style time format, message time, distinguishing multi-turn contexts, etc.).
 - Single-round chat history, all chat history, and operation history can be exported in Markdown format, supporting export as `.md` and `.txt`.


## Updates   

- **August 28th** Added Contextual mode.
- **August 21st** 1) Upgraded to support GPT-4 model. 2) Supports third-party API keys (reverse proxy service providers).


---

###

👉 GPT-4 仓库是基于 ChatGPT 仓库的一个拷贝，完全相同。 

👉 LinGPT - ChatGPT: https://github.com/lin2025/gpt3.5 

[![简体中文](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-Readme-success)](#lingpt-2)

## LinGPT

 - 简介：仅有一个`.html`文件的GPT，轻量，便捷，零门槛
 - 在线：静态网页，体积小，托管在 Github / Gitee 非常流畅
 - 下载：下载到电脑，打开html文件即可使用，像打开一张图片一样简单
 - 上传：可上传至托管平台/主机/服务器，支持所有免费的静态网页托管平台
 - 接口：支持 OpenAI 官方API 和第三方平台API (已适配常见代理平台)，支持免魔法
 - 模型：支持所有最新的 GPT-3.5 和 GPT-4 模型
 - 密钥：支持 OpenAI 官方Key 和第三方平台专用Key，支持**轮询**
 - 数据：仅存储于浏览器本地缓存，支持导出、导入和删除

## 在线体验

 :globe_with_meridians:线路 Github: [https://lin2025.github.io/gpt4/](https://lin2025.github.io/gpt4/)

 :cn:线路 Gitee: [https://lin2025.gitee.io/gpt4/](https://lin2025.gitee.io/gpt4/)

 :cn:多种下载方式（含网盘）: [https://lin2025.gitee.io/#gpt3.5-code](https://lin2025.gitee.io/#gpt3.5-code)


## 功能

> GPT生成回复采用一次性返回，非流式响应，互交体验会降低，但也有优点 - 不会中断、内容多时响应快

 - **新功能**: 记忆模式 (上下文模式)

 - **新功能**: 支持第三方平台的专用Key，适配部分第三方代理平台 (api2d、next-web、openai-sb、aiproxy、openaimax、aigc2d、api2gpt、chatai、closeai、ohmygpt、aiayw、czl...)
				
 - **新功能**: 适配最新模型，支持 GPT-3.5、GPT-4 全部模型

 - **新功能**: 支持自动重问 (当发送失败时，智能判断是否重试)
 
 - **新功能**: 轮询Key，全自动的智能的轮换 API Key，支持批量添加
 
 - **新功能**: 页面缩放 (移动端)

 - **新功能**: 多对话管理、全自动保存、支持创建副本、多标签页数据同步、可导出 (备份/迁移/分享)、可导入 (还原对话)
 
 - **新功能**: 支持浏览器本地存储，支持数据同步、导入、导出、删除、统计等操作
 
 - Smart max_tokens（全自动调节max_tokens）
 
 - API Key、API余额/有效期查询、自定义接口网址、自定义API请求参数（model、max_tokens、temperature、top_p、presence_penalty、frequency_penalty）

 - 支持Markdown（代码块、高亮代码、显示网络图片、显示表格、文章排版)

 - 系统提示词、Token用量统计、一键复制、自动解析OpenAI 错误代码、功能帮助

 - 清空、撤销、重问，并支持快捷键

 - 语言支持简体中文和英语、支持多种方式设置头像（可上传头像）、支持样式设置（字体大小、微信样式的时间、消息时间、区分多轮对话）

 - 可导出单轮聊天记录、全部聊天记录和操作记录，格式为Markdown，支持导出`.md`和`.txt`


## 特点

> 使用 记事本 或 文本编辑.app 即可改代码 修改教程已写在代码里 无需懂技术  
> v6.07 版本开始 多数个性化设置可直接在界面中完成

 - 无门槛 人人都能DIY 小白也能利用免费的静态托管平台轻松建站
 - 支持隐形系统提示词 一分钟即可轻松定制不同用途的AI工具
 - 适合日常轻中度使用场景 多个重要功能正在研究中...


## 更新   

- **8月28日** 新增 记忆模式 (上下文模式)。
- **8月21日** 1) 升级支持 GPT-4；2) 支持第三方API Key，适配第三方代理平台。
