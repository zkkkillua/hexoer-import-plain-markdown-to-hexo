# Hexoer  
### 将普通的markdown文档转换为hexo格式
[EN](https://github.com/zkkkillua/hexoer-import-plain-markdown-to-hexo/blob/master/README.md#hexoer)  
  
### Features
- 遵从你的hexo配置和文件模板。
- 让hexo决定新的文件名称。
- 使用旧文件的修改时间作为新文件的创建时间。
  
### Requirements
- Python3
- os
- subprocess
- time
  
### Usage
1. 在hexo博客的根目录下创建一个空的文件夹（推荐使用英文名称）。
2. 将"hexoer.py"移动到新创建的文件夹中。
3. 复制所有待修改的markdown文件到新创建的文件夹中。
4. `python hexoer.py` 并等待完成。
