
##全国大学生数学建模竞赛LaTeX论文模板
cumcmthesis 是为全国大学生数学建模竞赛编写的LaTeX模板, 旨在让大家专注于
论文的内容写作, 而不用花费过多精力在格式的定制和调整上. 本手册是相应的参考, 其
中提供了一些环境和命令可以让模板的使用更为方便. 同时需要注意, 使用者需要有一
定的 LaTeX 的使用经验, 至少要会使用 ctex 宏包的一些功能, 比如调节字距或修改字体
大小等等. 对了, 例子文件参看 [example.pdf](https://github.com/latexstudio/CUMCMThesis/blob/master/example.pdf).

另外, 本模板制作了视频使用教程, 参看[这里](https://item.taobao.com/item.htm?spm=a1z10.1-c.w4004-3473795048.2.ZlPoPL&id=43823508044).


# 更新记录

2016年8月1日更新增加了可以去掉前面封面页的选项。具体使用如下:

如果需要去掉封面并把论文标题保留在摘要上面，在加载类的使用如下语句：

    \documentclass[withoutpreface,bwprint]{cumcmthesis}

如果需要封面页，则是与原来一致：

    \documentclass[bwprint]{cumcmthesis}