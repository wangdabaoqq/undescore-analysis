## underscore源码解析
> underscore.js 是我在第一个认真去读去理解、去分析打印、测试的js源码。为什么选择去解析underscore.js的原因, 就像很多人推荐的原因一样, 第一是短小精悍, 代码量相对比较少, 但是功能很齐全。第二个原因是目前关于underscore.js的文章较多, 如果遇到不理解的, 也好查询。

## 当前解析版本
`1.9.1`

## 调试方式

目前使用了`console`进行`function`方法进行调试。

## 为什么要解析源码
其实说是解析源码, 我到觉得更好的说法是, 学习源码的设计角度。

## 进度
由于我是参考文档采用的倒叙的方式, 后来发现, 一些函数内部, 调用的其他函数, 导致我需要去先去看其他函数。
这里我建议采用正序的方式去分析解读。