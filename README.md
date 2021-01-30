# 入门

https://github.com/EssayKillerBrain/EssayKiller_V2  看看大牛操作，无需考虑代码，大致了解有个整体印象就行。tf1,gpt2预训练模-文章生成

https://github.com/mymusise/gpt2-quickly    tf2 + hugging face 简洁明了的使用示范，高度封装的框架，了解训练流程即可

### 新人建议直接在hugging face封装的训练框架的基础上开始学习，避免淹没在网上各式各样的写法中，心力憔悴。
### 从行政管理专业从零到php开发（3个月），再转型开始学习nlp（2个月）。先了解宏观，再去学习细节，我认为这是最快速能够得到成效的途径。也才可能快速借此能够做出产品。
### 但是熟悉框架用法之后，应当回过头再去学习参数，框架，甚至算法的原理。这是必须的。

tf1版本gpt2的一种预训练模型
https://github.com/wind91725/gpt2-ml-finetune-/issues/10

清华关于nlp研究的官网
https://cpm.baai.ac.cn/
tf版本gpt2预训练模型，转化清华开源的模型用
https://github.com/bojone/CDial-GPT-tf

pytorch中文摘要生成
https://github.com/qingkongzhiqian/GPT2-Summary

### keras是趋势，也确实很方便，tf2也是这么推荐的，以下2个国产框架都是基于keras

国内框架1
https://github.com/bojone/bert4keras    这个作者很热情，有微信群可以帮助解答问题

国内框架2
https://github.com/BrikerMan/Kashgari   基于bert4keras又进行了封装

框架作者的博客
https://kexue.fm/archives/7867

国外对于gpt2简化使用的封装，这是和hugging face起到类似功能的，可以参考参考
https://github.com/minimaxir/gpt-2-simple 


# 训练

训练平台
https://openbayes.com/pricing/ 国内的一个平台，界面不错，送一些免费的，只是免费的配置比较低

colab
https://colab.research.google.com/ google提供的免费平台，gpu/tpu（随机分发，都是好配置，远超国内各大平台提供的免费环境。要fan qiang）

gpt2训练 xl（最大规模）所需配置和最低gpu说明
https://colab.research.google.com/drive/1QE4LVEYITjIkjXxosahHVZPsSHtYZy7x#scrollTo=LdpZQXknFNY3
You can only use adafactor as an optimizer parameter to train the large and extra-large models, using a Tesla P100 GPU. 

# 学习：
https://github.com/apachecn/AiLearning  还没看

# 有用的操作：
https://github.com/850886470/CPM-TF2Transformer  把gpt2中文模型转hugging face
