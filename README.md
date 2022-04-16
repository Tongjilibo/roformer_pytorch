# roformer_pytorch
基于bert4torch框架，roformer/roformer_v2的pytorch简洁实现
1. 本脚本全部基于[bert4torch](https://github.com/Tongjilibo/bert4torch)框架，主要是用pytorch复现[bert4keras](https://github.com/bojone/bert4keras)以及各种实例
2. 如果链接打不开，可能是因为源文件更新，可直接访问[bert4torch_example](https://github.com/Tongjilibo/bert4torch/tree/master/examples)

---
- [basic_masked_language_model_roformer.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/basic/basic_masked_language_model_roformer.py)：基础测试，测试roformer的MLM模型效果。
- [task_sentiment_classification_roformer.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/sentence_classfication/task_sentiment_classification_roformer.py)：任务例子，情感分类任务，加载roformer权重
- [task_sentiment_classification_roformer_v2.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/sentence_classfication/task_sentiment_classification_roformer_v2.py)：任务例子，情感分类任务，加载roformer_v2权重
