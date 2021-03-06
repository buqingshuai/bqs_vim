# bqs_vim

## 1. 安装

```
git clone https://github.com/buqingshuai/bqs_vim.git ~/.bqs_vim
cd ~/.bqs_vim
bash ./install.sh
```

## 2. 快捷键

> 如下快捷键，请在Normal模式中使用

### 2.1 <Fn>键的功能和cscope命令说明

|         <Fn>键的功能         |       cscope命令说明          |
|------------------------------|-------------------------------|
| <F1> vim help 窗口           | :cs show 查看已加载的数据库   |
| <F2> tagbar   窗口           | :cs add  加载指定的数据库     |
| <F3> 文件浏览 窗口           | ,ss      查找symbol           |
| <F4> 切换窗口 (panel & tag)  | ,sg      查找定义             |
| <F5> 打开终端                | ,sd      查找本函数调用的函数 |
| <F6> 粘贴模式                | ,sc      查找调用本函数的函数 |
| <F7> 代码折叠                | ,st      查找指定的字符串     |
| <F9> 生成tags                | ,se      查找egrep模式        |
| <F12>生成cscope.out          | ,sf      查找并打开文件       |
|                              | ,si      查找包含本文件的文件 |

### 2.2 标签页快捷键和ctags跳转

|     标签页快捷键      |      ctags跳转        |
|-----------------------|-----------------------|
| ,c   创建新标签页     | Ctrl+]   跳转到定义   |
| ,x   删除标签页       | Ctrl+o   返回上一级   |
| ,[   移动到前一个标签 |                       |
| ,]   移动到下一个标签 |                       |

