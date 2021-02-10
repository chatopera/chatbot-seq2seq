# 自然语言处理推荐入门&工具书

<p align="center">
  <b>快速购书<a href="https://item.jd.com/12479014.html" target="_blank">链接</a></b><br>
  <a href="https://item.jd.com/12479014.html" target="_blank">
  <img src="https://user-images.githubusercontent.com/3538629/48657619-bcd24880-ea6e-11e8-8c4e-8bcb00761942.png" width="400">      
  </a>
</p>

[《智能问答与深度学习》](https://item.jd.com/12479014.html) 这本书是服务于准备入门机器学习和自然语言处理的学生和软件工程师的，在理论上介绍了很多原理、算法，同时也提供很多示例程序增加实践性，这些程序被汇总到示例程序代码库，这些程序主要是帮助大家理解原理和算法的，欢迎大家下载和执行。代码库的地址是：

[https://github.com/l11x0m7/book-of-qna-code](https://github.com/l11x0m7/book-of-qna-code)

# chatbot
一个可以使用自己语料进行训练的中文聊天机器人，目前包含seq2seq tf1.x和tf.2x版本，seqGan版本为tf1.x版本，后续计划更新pytorch版本，欢迎大家实践交流。

# 关于语料的说明
大家可以使用小黄鸡的预料，地址https://github.com/zhaoyingjun/chatbot/tree/master/chineseChatbotWeb-tf2.0/train_data/seq.data

# seq2seq版本代码执行顺序

1、在下载好代码和语料之后，将语料文件放入data目录下。

2、按照 数据预处理器（data_utls.py)-->execute.py(执行器)-->app.py（可视化对话模块）的顺序执行就可以了。

3、超参配置在seq2seq.ini和seq2seq_sever.ini文件中配置。

# seqGAN版本代码执行顺序
1 、在下载好代码和语料之后，将语料文件放入source_data目录下。
2、按照 数据预处理器（source_data_utls.py)-->execute.py(执行器)-->app.py（可视化模块）的顺序执行就可以了

# 参考代码和文献

http://blog.topspeedsnail.com/archives/10735/comment-page-1#comment-1161。

http://www.easyapple.net/?p=1384&from=singlemessage&isappinstalled=0。

https://github.com/zpppy/seqGan_chatbot

# 建议环境

ubuntu14.04  
python3.5  
TF1.X:
tensorflow==1.10.1或者tensorflow-gpu==1.10.1  
flask==0.11.1



# 已更新功能清单:

V1.1:已经增加中文分词，效果是变得更好了。注意在使用分词后，需要增加词典的大小，否则的话会导致词典无法覆盖训练集，导致出现很多的UNK。直接在seq2seq.ini中修改超参数enc_vocab_size和dec_vocab_size的值即可。  

V2.0:增加一个基于SeqGan的版本，以增加训练的效果。  

V3.0：增加TensorFlow2.0版，训练效果见文件夹内图片，训练数据已经准备好，直接执行python3 execute即可进行训练。 PS:预训练好了一个模型，链接:https://pan.baidu.com/s/1zcrBn8dpOhtBZu_T7TOO9w  密码:s7sq，可以下载使用，模型的效果见效果图，在使用预训练模型前需要先执行data_utl.py文件更新字典。 

# 版本路线图:

V4.0:a、增加pytorch版本；b、对当前的工程结构进行调整；敬请期待。

## Chatopera 云服务

[https://bot.chatopera.com/](https://bot.chatopera.com/)

[Chatopera 云服务](https://bot.chatopera.com)是一站式实现聊天机器人的云服务，按接口调用次数计费。Chatopera 云服务是 [Chatopera 机器人平台](https://docs.chatopera.com/products/chatbot-platform/index.html)的软件即服务实例。在云计算基础上，Chatopera 云服务属于**聊天机器人即服务**的云服务。

Chatopera 机器人平台包括知识库、多轮对话、意图识别和语音识别等组件，标准化聊天机器人开发，支持企业 OA 智能问答、HR 智能问答、智能客服和网络营销等场景。企业 IT 部门、业务部门借助 Chatopera 云服务快速让聊天机器人上线！

<details>
<summary>展开查看 Chatopera 云服务的产品截图</summary>
<p>

<p align="center">
  <b>自定义词典</b><br>
  <img src="https://static-public.chatopera.com/assets/images/64530072-da92d600-d33e-11e9-8656-01c26caff4f9.png" width="800">
</p>

<p align="center">
  <b>自定义词条</b><br>
  <img src="https://static-public.chatopera.com/assets/images/64530091-e41c3e00-d33e-11e9-9704-c07a2a02b84e.png" width="800">
</p>

<p align="center">
  <b>创建意图</b><br>
  <img src="https://static-public.chatopera.com/assets/images/64530169-12018280-d33f-11e9-93b4-9db881cf4dd5.png" width="800">
</p>

<p align="center">
  <b>添加说法和槽位</b><br>
  <img src="https://static-public.chatopera.com/assets/images/64530187-20e83500-d33f-11e9-87ec-a0241e3dac4d.png" width="800">
</p>

<p align="center">
  <b>训练模型</b><br>
  <img src="https://static-public.chatopera.com/assets/images/64530235-33626e80-d33f-11e9-8d07-fa3ae417fd5d.png" width="800">
</p>

<p align="center">
  <b>测试对话</b><br>
  <img src="https://static-public.chatopera.com/assets/images/64530253-3d846d00-d33f-11e9-81ea-86e6d47020d8.png" width="800">
</p>

<p align="center">
  <b>机器人画像</b><br>
  <img src="https://static-public.chatopera.com/assets/images/64530312-6442a380-d33f-11e9-869c-85fb6a835a97.png" width="800">
</p>

<p align="center">
  <b>系统集成</b><br>
  <img src="https://static-public.chatopera.com/assets/images/64530281-4ecd7980-d33f-11e9-8def-c53251f30138.png" width="800">
</p>

<p align="center">
  <b>聊天历史</b><br>
  <img src="https://static-public.chatopera.com/assets/images/64530295-5856e180-d33f-11e9-94d4-db50481b2d8e.png" width="800">
</p>

</p>
</details>


<p align="center">
  <b>立即使用</b><br>
  <a href="https://bot.chatopera.com" target="_blank">
      <img src="https://static-public.chatopera.com/assets/images/64531083-3199aa80-d341-11e9-86cd-3a3ed860b14b.png" width="800">
  </a>
</p>

