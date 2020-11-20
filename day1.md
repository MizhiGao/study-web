## Linux 命令操作
### 绝对路径与相对路径
绝对路径：/User/username/Desktop/test/hello.js <br/>
相对路径：test/hello.js ( 当前在 Desktop 目录 ）
相对路径：../test/hello.js （ 当前在 Desktop/tmp/ 目录中，../ 表示相对自身当前的上一级目录 ）
1. 根目录 / ，在 window 根目录上一般有 c 盘、d 盘、e 盘，在 mac 根目录上一般有 Applications 应用目录、Users 用户目录等等 。
2. 用户目录 ~ *英文状态下的~*，无论是 windos、mac 系统用户目录都存放于当前用户相关的文件，例如该用户特有的 桌面、文档、图片 等等。不过 window 和 mac 的用户目录的路径会不一样，因为 mac 没有 c 盘、d 盘的概念，window 的用户目录会在 c 盘 的 users 目录下的当前 username 目录，而 mac 会在更目录下的 users 目录的 <username> 目录。
### 切换目录与查看文件
- pwd ，是 Print Working Directory 的缩写，用于显示当前路径。
- cd，是  Change Directory 的缩写，用于切换文件夹。
    - cd /命令进入到根目录 （ 注意加空格： cd + 空格 + / ）
    - cd ～ 进入用户目录 
    - cd Desktop 相对路径命令进入到桌面目录
- ls ，是 list 的缩写，用于列举目录内容。
### 创建文件夹、文件
- mkdir ，是 make directory的缩写，用于创建目录。
- tounch ，用于创建文件
## vscode 编辑器
### 插件安装
1. Chinese (Simplified) Language 简体中文  汉化包
2. auto rename tag 修改开始标签的同时自动修改结束标签
3. open in browser 代码界面右键选择以浏览器方式打开
### 快捷键
- • 打开新的页签 command + n 
- • 保存文件 command + s 
- • 注释整行 command + ？
- • 删除整行 command + delete
- • 当前文件搜索 command + f
- • 全局文件搜索 command + shift + f
- • 全选 command  + a 
## Markdown 基础使用
1. 标题的标记语法为 # ，一个 # 标记一级标题，两个 ## 标记二级标题，三个 ### 标记三级标题。
2. 列表的标记为 - ，如果是有序列表可以使用数字和点来标记。
3. 斜体的语法为两边使用 * 号标示，例如入：文字里面这个是*斜体*，多用于文件名称。
斜体的语法为两边使用 ** 号标示，例如入：文字里面这个是**加粗**，多用于重点突出词组。
4. 链接使用 []() 来标记，[] 中括号里面放置展示内容，() 大括号里面放置跳转地址。
图片使用 ![]() 来标记，[] 中号中放置图片加载失败展示的名称，() 大括号里放置图片资源地址。



