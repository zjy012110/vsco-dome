# 项目代码片段测试版

### 0.1.0

test版本

基于elementUI和vue的二次封装组件和方法项目代码片段  

也可以不用插件，直接将代码片段复制到VSCode的用户代码片段中，方便快速更改，免去打包安装环节  

**操作步骤**  

点击VSCode左下角设置>用户代码片段>选择对应的语言格式(例：vue选择vue-html)>粘贴到新建的json文件中

## 组件、方法引入  

| 关键字 | 说明 |
| --- | --- |
| import canEditTable | 引入可编辑列表canEditTable |
| import listFilter | 引入列表搜索栏listFilter |
| import listCommon | 引用列表表格组件listCommon |
| import diaSelect | 引入放大镜组件diaSelect |
| import numeric | 引入数值组件numeric |
| import getSummariesUtil | 引入公共合计方法getSummariesUtil |
| import pagination | 引入列表分页组件pagination |
| import calculation | 引入计算方法calculation |
| import operationRecord | 引入操作记录组件operationRecord |
| import upload | 引入公共附件组件upload |

## 组件代码片段  

| 关键字 | 说明 |
| --- | --- |
| canEditTable  | 可编辑列表canEditTable |
| listFilter | 列表搜索栏listFilter |
| listCommon | 列表表格组件listCommon |
| diaSelectAuto | 放大镜组件(类型配置)diaSelect |
| diaSelectTable | 放大镜组件-表格型(手动配置)diaSelect |
| diaSelectTree | 放大镜组件-树型(手动配置)diaSelect |
| numeric | 数值组件numeric |
| getSummariesUtil | 公共合计方法getSummariesUtil |
| pagination | 列表分页组件pagination |
| upload | 公共附件上传组件upload |
| operationRecord | 操作记录组件operationRecord |
| footerOption | 底部操作组件footerOption |
| printing | 打印组件printing |

## 方法代码片段  

| 关键字 | 说明 |
| --- | --- |
| $http  | http请求 |
| diaselect | 放大镜选择赋值事件 |
| $message | 消息提示 |
| $message.success | 成功消息提示 |
| $message.warning | 警告消息提示 |
| $message.error | 错误消息提示 |
| getSummariesUtil | 公共合计方法 |
| $set | set赋值 |  

**调试：**  

VSCode编辑器下按`F5`调试  

**打包：**  

`npm i vsce -g` 安装打包工具  

打包成vsix文件：`vsce package`

**本地安装：**

VSCode点击扩展图标或者按`ctrl+shift+x`，点击扩展列表右上角的`...`(更多操作)，选择从VSIX安装

[github](https://github.com/zjy012110/vsco-dome)

