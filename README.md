CSDN：https://blog.csdn.net/weixin_37735081/article/details/94222230

上传GLUE中的MRPC数据集，使用Bert fine-tuning方法进行训练
判断两个句子的相似度，返回相似度结果

使用方法：
1. 下载代码
2. 下载google模型预训练文件 （uncased、Based版本）
   https://storage.googleapis.com/bert_models/2018_10_18/uncased_L-12_H-768_A-12.zip
3. bash classifier.sh 训练MRPC数据集
4. python bert_api_3.py 或 python bert_predi_web.py 开启服务
5. 使用postman发送json数据 或 在html页面使用
