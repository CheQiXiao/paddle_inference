
paddle 官网-文档-使用教程-训练与预测：

http://10.136.157.23:8090/documentation/docs/zh/guides/02_paddle2.0_develop/05_train_eval_predict_cn.html


此部分只使用了高层API和基础API进行预测，并未介绍paddle inference的预测流程和方法，因此加入第四个小章节：通过paddle inference实现模型的预测。

目前需要RD同学进行审核：

1、代码和文字叙述部分是否规范、易懂（代码已在本地跑通）

2、使用paddle inference预测模型，在手写数字识别任务中输入输出应该是什么样子比较合理

3、目前编写的第四章节中，模型使用的是由第三节基础API训练导出的，网络结构采用SubClass组网，但第二节的网络结构采用的是Sequential组网方式，两种是否需要统一 
