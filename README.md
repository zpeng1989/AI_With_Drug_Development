# 生物信息学概论
* [统计学习导论](http://www-bcf.usc.edu/~gareth/ISL/)
如果你有一点统计方面的背景知识，请先阅读这本书。

* [Coursera的机器学习课程](coursera.org/learn/machine-learning)
任何对机器学习感兴趣的人的必修课。

* [RR & Bioconductor手册](http://manuals.bioinformatics.ucr.edu/home/R_BioCondManual/)  
确保在进行任何生物信息学项目之前已经看懂代码。

* [用R和Bioconductor进行HT序列分析](http://manuals.bioinformatics.ucr.edu/home/ht-seq)  
确保在进行任何NGS项目之前已经看懂代码。

* [ChemmineR: R的化学工具箱](http://www.bioconductor.org/packages/devel/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html)  
建议在进行任何化学信息学项目之前运行代码。

* [循序渐进地实践深度学习](http://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)  
PyTorch深度学习教程。

* [哈佛大学生物医学数据科学开放在线培训](http://rafalab.github.io/pages/harvardx.html) 
从rafalab代码的数据科学综合教程。

* [来自StatQuest的生物学家统计](https://statquest.org/videoindex/)
杰出的视频教程。

* [数据分析常用清单](https://github.com/Bin-Chen-Lab/BigData_AI_DrugDiscovery/blob/master/data_science_cheatsheet.pdf)
快速查看数据分析基础知识列表

* 单细胞RNA-Seq分析[osca](https://osca.bioconductor.org/introductiontion.html)， [seurat](https://satijalab.org/seurat/vignettes.html)
优秀的scRNA-Seq分析流程。

# 基础论文


## 领域回顾文章

* [癌症的特征:下一代分析](http://www.cell.com/abstract/S0092-8674%2811%2900127-9)
了解癌症的基础。

* [肿瘤转移:分子角度的演化过程](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3261217/)
了解癌症转移的基础。

* [癌症基因组图](http://science.sciencemag.org/content/339/6127/1546.long)
了解癌症基因组学的基础。

* [临床翻译关键时刻的癌症转录组分析](https://www.nature.com/articles/nrg.2017.96)
癌症转录组学综述。

* [尤文氏肉瘤:历史展望、当前的技术水平和未来靶向治疗的机会](https://www.ncbi.nlm.nih.gov/pubmed/18525337)
一种癌症治疗发现的典型案例综述。


* [表型药物发现的机遇与挑战:一个行业的视角](https://www.nature.com/nrd/journal/v16/n8/abs/nrd.2017.111.html)
药物筛选一个方法


* [10年的生物通路分析:当前的方法和突出的挑战](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002375)
这是对通路分析方法发展的一个很好的总结。


* [深度学习](https://www.nature.com/nature/journal/v521/n7553/full/nature14539.html)
深度学习回顾。

* [高性能医学:人类与人工智能的融合](https://www.nature.com/articles/s41591-018-0300-7)
当前DL应用于生物医学研究的进展和挑战。


## 统计方法开发


* [RNA微型矩阵数据的显著性分析](http://www.pnas.org/content/98/9/5116.full)
开发SAM，一种使用微阵列数据进行微分表达式分析的流行方法。


* [limma:矩阵数据的线性模型](https://link.springer.com/chapter/10.1007/0-387-29362-0_23)
另一种使用矩阵数据进行表达式分析的算法LIMMA的开发。


* [序列计数数据的差异表达分析](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2010-11-10-r106)
开发DEseq，一种使用RNA-SEQ数据进行矩阵表达式分析的方法。


* [基因集富集分析:一种基于已知知识的方法来解释全基因组表达谱](http://www.pnas.org/content/102/43/15545.long)
GSEA的发展，是目前最流行的基因富集分析方法，也是了解药物发现方法的基础。

 
* [使用经验贝叶斯方法调整矩阵表达数据中的批处理方法](https://academic.oup.com/biostatistics/article/8/1/118/252073/Adjusting-batch-effects-in-microarray-expression)


## 纠正批量处理样本之间试验差异方法。



* [随机网络中距离的定义](http://science.sciencemag.org/content/286/5439/509.full)
无标度网络的定义。



* [基于元路径的异构信息网络top-k相似度搜索](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.220.2455)
一种挖掘异构网络的机器学习方法。


* [MuSiC:识别癌症基因组的突变意义](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3409272/)
MuSiC的发展，一种识别突变的流行方法。



## 生物信息学方法的开发与应用

* [使用基因表达签名连接小分子、基因和疾病](http://science.sciencemag.org/content/313/5795/1929.long)
第一篇描述药物发现方法的论文。


* [利用公共基因表达数据的概要发现和临床前适应症验证](http://stm.sciencemag.org/content/3/96/96ra77)
我们的药物发现工作的基础，和写一篇计算论文的范例(从方法开发到实验验证)。


* [配体化学与蛋白质药理学的关系](http://www.nature.com/nbt/journal/v25/n2/full/nbt1284.html)
SEA的发展，一种预测药物-靶标相互作用的方法，以及另一个写计算论文的伟大示范。


* [药物诱导转录模块的表征:药物的重新定位和功能理解](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3658274/)
从数据分析开始，最后通过生物实验验证


* [跨物种调控网络分析确定基因FOXM1和CENPF之间的协同作用，驱动前列腺癌恶性肿瘤](http://www.cell.com/cell/fulltext/s1535-6108(14)00125-1)
从数据分析开始，最后通过生物实验验证


* [通过网络扰动分析阐明复合作用机制](http://www.sciencedirect.com/science/article/pii/S0092867415006996)
从数据分析开始，最后通过生物实验验证


* [发现药物作用模式和药物从转录反应中重新定位](http://www.pnas.org/content/107/33/14621.long)
从数据分析开始，最后通过生物实验验证

* [Imagenet深度卷积神经网络分类](http://papers.nips.cc/paper/4824-Imagenet-classification-with-deep-convolutional neural-networks.pdf)
卷积神经网络(CNN)的发展，流行的深度学习方法。


## 肿瘤计算分析

* [药物-靶点作用网络](https://www.nature.com/nbt/journal/v25/n10/full/nbt1338.html)
药物-靶点相互作用的网络分析。


* [人类乳腺癌的分子图谱](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3465532/)
来自TCGA的一篇典型的基因组分析论文。


* [12种主要癌症类型的突变图谱与意义](http://dx.doi.org/10.1038/nature12634)
一篇关于泛癌症基因组分析的论文。


* [男性与女性患者癌症分子差异的综合表征](http://www.cell.com/cell/fulltext/s1535-6108(16)30111-8)
一篇关于泛癌症基因组分析的论文。

* [类风湿关节炎的遗传学有助于生物学和药物的发现。](https://www.nature.com/nature/journal/v506/n7488/full/nature12873.html)
使用基因对药物发现。


* [肿瘤细胞系支持抗癌药物敏感性的预测建模](https://www.nature.com/nature/journal/v483/n7391/full/nature11003.html)
利用细胞系数据发现生物标记的文章。


* [一项基于时间-过程的全时性脓毒症和无菌性炎症的多队列分析一个可靠的诊断基因集](http://stm.sciencemag.org/content/7/287/287ra71.short)
利用公共表达量数据发现生物标记的文章。


* [利用化学基因组学数据库训练的多类贝叶斯模型预测化合物的生物学目标](http://pubs.acs.org/doi/10.1021/ci060003g)
化学信息学中典型的机器学习论文。

* [结构相似的分子是否具有相似的生物活性](https://dx.doi.org/10.1021/jm020155c)
化学信息学中典型的数据分析论文。


##基于深度学习的药物发现


* [药物设计强化学习网络](http://advances.sciencemag.org/content/4/7/eaap7885)
开发一个强化学习模型来生成新的化合物的目标化学文库，这些化合物可以针对一个或多个特性进行优化。


* [学习分子特征图的卷积网络](https://arxiv.org/abs/1509.09292)
受ECFP的启发设计了基于DL的特征


* [使用数据驱动的连续分子表示的自动化学设计](https://pubs.acs.org/doi/full/10.1021/acscentsci.7b00572)
使用变分自编码器编码和优化化合物从潜在的分子化合物空间。

## 塑造我们的未来

* [单细胞RNA-seq突出原发性胶质母细胞瘤瘤内异质性](http://science.sciencemag.org/content/344/6190/1396)
单细胞在癌症研究中的应用。

* [单细胞转录组学揭示了慢性髓系白血病干细胞的独特分子特征](https://www.nature.com/nm/journal/v23/n6/full/nm.4336.html)
单细胞分析在个体化癌症治疗中的应用。

* [小分子诱导的棕色脂肪重构](http://www.sciencedirect.com/science/article/pii/S2211124716317697)
利用小分子来控制细胞的发育。



* [相关的化学敏感性和基础基因表达机制说明](https://www.nature.com/nchembio/journal/v12/n2/full/nchembio.1986.html)
利用药物基因组学数据了解药物作用机制。


* [下一代药物连通图: L1000平台和第一个1,000,000数据](https://www.biorxiv.org/content/early/2017/05/10/136168)
LINCS，我们主要用于药物发现的数据集。


* [转移癌整合临床基因组学](http://www.nature.com/nature/journal/v548/n7667/full/nature23306.html)
我们在治疗原发性癌症方面有很多经验，现在是时候把我们的注意力放在转移性癌症上了，大多数病人都死于转移性癌症。



* [使用循环对抗网络进行不配对的image-to-image](https://arxiv.org/pdf/1703.10593.pdf)
利用深度学习GAN实现领域应用。

# 著名的转化药物靶点发现工具和数据集



** 列出癌药物发现的优秀工具/数据集

## 病人数据和疾病数据

* [ClinicalTrials.gov](https://clinicaltrials.gov)
查找用于癌临床试验的药物。

* [今日癌症(Globocan):数据可视化工具，显示当前全国癌症发病率、死亡率和患病率的估计](http://gco.iarc.fr/today/home)
搜索癌发病率。



* [英国生物库](http://www.ukbiobank.ac.uk/)和[英国生物库引擎](https://biobankengine.stanford.edu/)
通过斯坦福生物数据库引擎搜索癌的公共临床/分子数据和肝癌的遗传变异。


* [COSMIC](http://cancer.sanger.ac.uk/cosmic)
寻找癌的体细胞突变。

## 药物靶点开发

* [cBioPortal](http://www.cbioportal.org/)。
从包括TCGA在内的公共数据集中搜索癌的分子变化。

* [GTEx](http://www.gtexportal.org)。
在正常组织中寻找基因表达。

* [人类蛋白质图谱](https://www.proteinatlas.org/)
寻找癌的蛋白表达和病理。


* [肿瘤细胞系百科全书](https://portals.broadinstitute.org/ccle)
寻找癌细胞系的基因表达。


* [Achilles 项目](https://portals.broadinstitute.org/achilles)
寻找癌细胞的必要基因。

* [DepMap](https://depmap.org/portal/)
建立一个完整的临床前参考图，将肿瘤特征与肿瘤相关性联系起来，以加速精确治疗的发展。


* [GEO](https://www.ncbi.nlm.nih.gov/geo/)
搜索癌的功能基因组数据，需要额外的计算分析来创建癌特征。

* [Enrichr](http://amp.pharm.mssm.edu/Enrichr/)
搜索丰富的TS/Pathway/生物过程/细胞类型的基因列表。

* [STRING DB](https://string-db.org/)
可视化蛋白质-蛋白质之间的关系。


## 药物发现

* [PubChem](https://pubchem.ncbi.nlm.nih.gov/)
关于化合物/药物的一切都需要知道。

* [DrugBank](https://www.drugbank.ca/)
搜索drug-target-indication。

* [SEA](http://sea.bkslab.org/)
预测给定化合物的目标。


* [LINCS](https://clue.io/)
预测具有肝癌特征的药物。

* [ChemMine](http://chemmine.ucr.edu/)
对化学结构富集分析非常有用。


# NGS 分析

* [RNASEQ博客](http://www.rna-seqblog.com/)
大量的RNA-SEQ分析方法/应用。

* [RPKM, FPKM和TPM](http://www.rna-seqblog.com/rpkm-fpkm-and-TPM-clear-explained/)

* [RNA-seq工作流:基因水平的探索性分析和差异表达](http://www.bioconductor.org/help/workflows/rnaseqGene/)

# Python 

* [Python](https://anaconda.org/)
建议使用anaconda来管理python包

* [scikit:一个流行的python机器学习包](http://scikit-learn.org/stable/)

* [rdkit](http://www.rdkit.org/docs/index.html)
处理化学结构的免费python库。

* [PyTorch](http://pytorch.org/)
深度学习框架。

# R/Bioconductor

* [ggplot](http://zevross.com/blog/2014/08/04/beautiful-plotting-in-r-a-ggplot2-cheatsheet-3/)
一个必须读取可视化数据使用R。

* [ChemmineR: 化学信息学Toolkit调用R包](http://www.bioconductor.org/packages/devel/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html)



* [biomaRt](http://bioconductor.org/packages/release/bioc/html/biomaRt.html)
一个用于分子数据映射id关系的强大包。

* [GEOquery](http://bioconductor.org/packages/release/bioc/html/GEOquery.html)
从GEO下载数据。

* [cgdsr](https://cran.r-project.org/web/packages/cgdsr/index.html)
获取cBioportal数据的API。

* [pheatmap](https://cran.r-project.org/web/packages/pheatmap/index.html)
可视化的热图。

* [在同一页面上混合多个图形的简便方法](http://www.sthda.com/english/articles/24-ggpubr-public--plots/81-ggplot2-Easy-Way-mix-multiple- graphs-onsamepage/)





