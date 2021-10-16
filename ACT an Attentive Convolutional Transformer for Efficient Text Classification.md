## ACT: an Attentive Convolutional Transformer for Efficient Text Classification

## ACT：一种用于高效文本分类的专注卷积变换器

最近，Transformer在许多NLP任务中表现出了良好的性能，并显示出取代递归神经网络（RNN）的趋势。同时，卷积神经网络（CNN）虽然具有良好的局部特征提取能力，但由于其捕获序列和长距离依赖性的能力较弱，因此很少受到关注。在本文中，我们介绍了一种专注的卷积变换器（ACT），它利用了变换器和CNN的优点来实现高效的文本分类。具体地说，我们提出了一种新的注意卷积机制，该机制利用卷积过滤器的语义，将文本从复杂的词空间转换为非信息卷积过滤器空间，在该空间中捕获重要的n-gram。ACT能够有效地捕获局部和全局依赖关系，同时保留顺序信息。对各种文本分类任务和详细分析的实验表明，ACT是一种轻量级、快速、有效的通用文本分类器，优于CNN、RNN和包括Transformer在内的关注模型。

![img](https://img-blog.csdnimg.cn/img_convert/344be67565824b9b735c3116b9ad3abe.png)

https://blog.csdn.net/qq_27590277/article/details/118347627