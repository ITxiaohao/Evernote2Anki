本插件是一款与小能熊终身学习学院「知识内化训练营」配套的笔记自动化导入插件。

# 特性

## 导入普通笔记（以「Q：A：」为卡片分隔）

- 支持行内元素：加粗、斜体、下划线、颜色、高亮、字体字号
- 支持块元素：有序和无序列表、表格、分割线、代码块
- 支持图片（和笔记同时导出）
  
## 导入 Markdown 笔记（以 h2 为卡片分隔）

- 支持行内元素：加粗、斜体、下划线、删除线、超链接、行内代码和公式
- 支持块元素：有序和无序列表、标题、引用、分割线、图片、代码块和公式块

# 准备

- 安装 Anki 2.1 for Windows / macOS
- 在下方获取插件 ID 并在 Anki 中安装

# 使用

Step 1：在印象笔记中制作 Q&A 笔记，注意「问题」必须以 Q：开头，「答案」必须以 A：开头，它们的行数不限；

![](http://img.candobear.com/2019-10-06-050738.png)

Step 2：在印象笔记中将笔记导出为 HTML 格式；

![](http://img.candobear.com/2019-10-06-050821.png)

Step 3：在 Anki 中点选 工具（Tools） - 「从 HTML 或 Markdown 文档导入」，并根据界面指示操作。

![](http://img.candobear.com/2019-10-06-051050.png)

![](http://img.candobear.com/2019-10-06-051244.png)

# 已知问题

- 在 HTML 中，「Q：」和「A：」必须直接位于一行的开始，而不能将它们放到代码块中；
- 在 Markdown 中不支持表格

# 更改日志

## 【未发布】｜version 1.0

## 2019 年 10 月 29 日｜version 0.2.1

### 修正

- 修正 Windows 下 HTML 解析

## 2019 年 9 月 10 日｜version 0.2

### 添加

- 基本实现 Markdown 解析功能
- 可以同时导入 HTML 文件同一目录下的媒体文件

### 修正

- 改善用户界面
- 修正界面卡住的问题

## 2019 年 7 月 21 日｜version 0.1

### 添加

- 导入对话框编写
- 基本实现 HTML 解析功能（用 Beautiful Soup 4 库完成解析）。

## 加入开发

- 你可以在插件页面上添加评论，或在插件的 [GitHub 页面](https://github.com/tansongchen/Evernote2Anki) 提交 Issues；
- 你可以联系我的邮箱 tansongchen@pku.edu.cn；
- 你可以在【An 部就班】微信群中找到我。