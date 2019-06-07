# cmrc2019-project

## 官网
https://hfl-rc.github.io/cmrc2019/

## Github（baseline）
https://github.com/ymcui/cmrc2019

## 任务描述
第三届“讯飞杯”中文机器阅读理解（CMRC 2019）的任务是句子级填空型阅读理解（Sentence Cloze-Style Machine Reading Comprehension, SC-MRC）。 <br \>
根据给定的一个叙事篇章以及若干个从篇章中抽取出的句子，建立模型，将候选句子精准的填回原篇章中，使之成为完整的一篇文章。 <br \>
本任务需要机器能够根据上下文的逻辑关系判断空缺部分的内容，进一步提升了机器阅读理解的难度。

## 和一般填空型机器阅读理解任务（如，CNN/Daily Mail, CBTest）的比较
一般Cloze-style MRC，根据给定的篇章/段落/文档/上下文，将问题/查询中缺失的一个[实体]补充完整。且该[实体]必须在篇章中出现过。  <br \>
而SC-MRC，给定一个叙事篇章，从篇章中抽取若干个句子作为候选项，任务的目标是将这些抽取出的句子重新填回篇章中去。 <br \>
所以Cloze-Style MRC是填充一个实体，而SC-MRC则需要填充多个句子。

## SC-MRC数据集样本示例
SC-MRC数据集由json文件存储，{"data":[]}


