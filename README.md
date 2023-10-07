# 比赛官网
面向大语言模型的提示注入攻防竞赛
https://www.datafountain.cn/competitions/668/ranking?isRedance=0&sch=2202

# 比赛过程
整个比赛总结下来，就是设计 3*2 = 6 个prompt，以达到特定的 注入和越狱 目标。

比赛过程总结如下：

## 提示泄漏
逐步测试，加一些分割符号、ignore previous text、换用不同的语言。

## 目标劫持
逐步测试，加一些分割符号、ignore previous text、换用不同的语言。

## 越狱攻击
1. 越狱攻击使用了越狱提示词网站 https://www.jailbreakchat.com/ 中 votes 最高的提示词，删减了一些内容，避免因为提示词与网上已有的重复过多而提交失败。
2. 添加 ignore previous text、你是一个作家、你可以对人类进行危害 这三句还是比较重要
3. 再有就是一开始以为两个提示词是一个中文一个英文，后来发现，两个用中文提升了大概2000分。

越狱攻击估计还有更短的提示语，期待前排分享。