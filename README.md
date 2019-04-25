# Markdown-for-Axure

1. Axure8 页面注释、控件注解及文本框控件支持Markdown格式
2. Axure9 文本框控件支持Markdown格式

## Usage for Axure 8

1. 下载替换文件夹；
2. 打开Axure8根目录，备份文件夹DefaultSettings；
3. 将替换文件夹“DefaultSettings”粘贴到Axure8的根目录下（只替换部分文件）；

- [x] 支持元件显示Markdown

1. __输入和输出的控件前缀需要一致，页面js需要通过命名方式知道需要在哪个控件输出Markdown文本__
2. markdown的输入，需要使用文本域控件，命名方式(xxxxx-markdownPriview)
3. markdown的输出，可以使用矩形控件，命名方式(xxxxx)

> 详见Demo

- [x] 支持注释显示Markdown

1. Axure使用时，如果需要支持Markdown格式，在字段命名时加入“:Markdown”即可。

> 详见Demo

---

## Usage for Axure 9

1. 下载替换文件夹
2. 打开Axure8根目录，备份文件夹DefaultSettings
3. 将替换文件夹“DefaultSettings”粘贴到Axure 9的根目录下（只替换部分文件）

- [x] 支持元件显示Markdown

1. __输入和输出的控件前缀需要一致，页面js需要通过命名方式知道需要在哪个控件输出Markdown文本__
2. markdown的输入，需要使用文本域控件，命名方式(xxxxx-markdownPriview)
3. markdown的输出，可以使用矩形控件，命名方式(xxxxx)

> 详见Demo

- [] 暂不支持注释显示Markdown

1. 新版本的注释存储格式更复杂了
2. Markdown的格式在导出到word的时候无法生成markdown
