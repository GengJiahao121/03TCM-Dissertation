## 所有的文件都存在阿里云盘中

**由于文件太多，阿里云分享不了永久链接，所以只能创建1天的快传链接，如果有需要找我要吧**

**可以联系我的微信或者邮箱gjh_fmily@163.com**

这些文件和代码我之前都是放在AutoDL上的，在其auto-tmp文件夹下，所以所有的文件路径都是基于`/root/autodl-tmp`的

并且我是用的vscode 通过ssh连接到服务器在本地进行调试与运行的

调试与运行需要用到debug功能，其配置文件都在`.vscode/setting.json`中，其中最重要的就是没有项目运行需要的主函数和对应的参数，这个没有的话，运行不了

解压后的目录文件结构应为：

```

/root/autodl-tmp
├── BalancedLossNLP
├── bert_kg
├── bert_kg_OTSeq2Set_gru_NoNumPred
├── bert_kg_OTSeq2Set_gru_NumPred
├── OTSeq2Set
├── README.md
├── TCM_KG-main
├── TCM-pachong
├── zipANDtar
├── ZY-BERT-jiahao.geng
├── 毕业论文及文件.tar.gz
├── 知识图谱嵌入方法
└── 知识图谱嵌入方法.tar.gz
```

# 文件解读

## /root/autodl-tmp/.vscode

各个模型的运行调试文件和参数

## /root/autodl-tmp/知识图谱嵌入方法

几种知识图谱嵌入的方法

## /root/autodl-tmp/BalancedLossNLP

这个是 再平衡权重和负样本容忍正则化 思想的原论文代码

## /root/autodl-tmp/bert_kg_OTSeq2Set_gru_NoNumPred 

这个是重点的我的思想的实现代码，我觉得一些参数的设置没有调好，所以实验效果不好，

这是因为我对深度学习的理解还不够好，不知道如果去调试，但是思想上我觉得是说的通的，后续有时间我会继续改进，让他达到一个好的效果

我的毕业论文代码，可运行，没有基数预测功能

## /root/autodl-tmp/bert_kg_OTSeq2Set_gru_NumPred

我的毕业代码，文件删除了，可以从bert_kg_OTSeq2Set_gru_NoNumPred复制过来，只有loss.py文件不同，这个不能运行，有基数预测，但好像没有再平衡权重和负样本容忍正则化

## /root/autodl-tmp/OTSeq2Set

OTSeq2Set论文代码，也是我借鉴的一片文章

## /root/autodl-tmp/TCM-pachong

自己编的爬虫代码

## /root/autodl-tmp/TCM_KG-main

网上的中医知识图谱数据集

## /root/autodl-tmp/ZY-BERT-jiahao.geng

ZY-BERT的代码基础上，改了一下，可运行


