# OmniFocus 4 批量生成子任务插件
### 插件简介
一个可以在选中父任务下，批量生成子任务的 OmniFocus 插件。  
**⚠️ 本插件为中文用户设计，界面、字段、默认行为偏向中文场景。**

### 功能特色
- 在父任务下批量生成 $n$ 个子任务
- 自动设置子任务的推迟日期和截止日期
- 设置预计持续时间
- 支持时区调整
- 父任务自动勾选「用最后一个动作完成」

### 安装方法
1. 下载本仓库中的 `批量生成子任务.omnifocusjs` 文件
2. 打开 OmniFocus → Automation → Plug-Ins
3. 将 `.omnifocusjs` 文件拖入 Plug-Ins 窗口
4. 插件将出现在 Automation → Actions 菜单中

### 使用方法
1. 选中一个父任务
2. 运行本插件
3. 填写表单，设定子任务数量、时间、预计时长、时区等
4. 点击创建，批量生成子任务

### 许可证
本项目基于 MIT 许可证开源，允许自由使用、修改和分发。

---

# OmniFocus 4 Batch Subtasks Plugin  

### About
An OmniFocus plug-in for batch creating subtasks under a selected parent task.
**⚠️ This plugin was originally designed for Chinese users and workflows. Some UI elements, field names, and default behaviors are based on Chinese usage context.**  

### Features
- Batch generate N subtasks under a parent task
- Automatically set Defer Date and Due Date
- Set Estimated Duration
- Support timezone adjustments (default: Asia/Tokyo or Asia/Beijing)
- Parent task auto set to “Complete with last action”

### Installation
1. Download `批量生成子任务.omnifocusjs` from this repository
2. Open OmniFocus → Automation → Plug-Ins
3. Drag and drop the `.omnifocusjs` file into the Plug-Ins window
4. The plugin will appear in Automation → Actions menu

### Usage
1. Select a parent task
2. Run this plugin
3. Fill in form parameters (subtask count, dates, duration, timezone)
4. Click 创建 → Subtasks will be generated under the parent task

### License
This project is open-sourced under the MIT License. See the LICENSE file for details.
