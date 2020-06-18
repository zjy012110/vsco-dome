# 项目代码片段测试版

### 0.1.0

**调试：**

VSCode 编辑器下按`F5`调试

**打包：**

`npm i vsce -g` 安装打包工具

打包成 vsix 文件：`vsce package`

**本地安装：**

VSCode 点击扩展图标或者按`ctrl+shift+x`，点击扩展列表右上角的`...`(更多操作)，选择从 VSIX 安装

test 版本

基于 elementUI 和 vue 的二次封装组件和方法项目代码片段

**示例：**

消息提示：

![message](https://uploader.shimo.im/f/kFb7fEFdUUEOGcNQ.gif)

分页组件：

![pagination](https://uploader.shimo.im/f/xswbeM3s8CFDg3vh.gif)

## 组件、方法引入

| 关键字                  | 说明                              |
| ----------------------- | --------------------------------- |
| import canEditTable     | 引入可编辑列表 canEditTable       |
| import listFilter       | 引入列表搜索栏 listFilter         |
| import listCommon       | 引用列表表格组件 listCommon       |
| import diaSelect        | 引入放大镜组件 diaSelect          |
| import numeric          | 引入数值组件 numeric              |
| import getSummariesUtil | 引入公共合计方法 getSummariesUtil |
| import pagination       | 引入列表分页组件 pagination       |
| import calculation      | 引入计算方法 calculation          |
| import operationRecord  | 引入操作记录组件 operationRecord  |
| import upload           | 引入公共附件组件 upload           |

## 组件代码片段

| 关键字           | 说明                                 |
| ---------------- | ------------------------------------ |
| canEditTable     | 可编辑列表 canEditTable              |
| listFilter       | 列表搜索栏 listFilter                |
| listCommon       | 列表表格组件 listCommon              |
| diaSelectAuto    | 放大镜组件(类型配置)diaSelect        |
| diaSelectTable   | 放大镜组件-表格型(手动配置)diaSelect |
| diaSelectTree    | 放大镜组件-树型(手动配置)diaSelect   |
| numeric          | 数值组件 numeric                     |
| getSummariesUtil | 公共合计方法 getSummariesUtil        |
| pagination       | 列表分页组件 pagination              |
| upload           | 公共附件上传组件 upload              |
| operationRecord  | 操作记录组件 operationRecord         |
| footerOption     | 底部操作组件 footerOption            |
| printing         | 打印组件 printing                    |

## 方法代码片段

| 关键字            | 说明               |
| ----------------- | ------------------ |
| \$http            | http 请求          |
| diaselect         | 放大镜选择赋值事件 |
| \$message         | 消息提示           |
| \$message.success | 成功消息提示       |
| \$message.warning | 警告消息提示       |
| \$message.error   | 错误消息提示       |
| getSummariesUtil  | 公共合计方法       |
| \$set             | set 赋值           |

[github](https://github.com/zjy012110/vsco-dome)

---

_也可以不用插件，直接将代码片段复制到 VSCode 的用户代码片段中，方便快速更改，免去打包安装环节_

**操作步骤**

点击 VSCode 左下角设置>用户代码片段>选择对应的语言格式(例：vue 选择 vue-html)>将本项目中 snippets 文件中对应 json 代码粘贴到新建的 json 文件中
