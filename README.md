# Project_Of_SRTP
学校的srtp项目--基于语音识别的自动文本纠错系统

这个项目目前，只能进行单词的替换，所以这才是纠错的第一步。
每个文档里都有详细的说明，每一个部分是做什么的，都写了相关的注释。

使用前应该添加相关的模块，在命令行里面输入下列的代码（以后会增加，这是目前需要安装的模块）：
pip install requests
pip install pypinyin

录测试样例的同学，目前的要求是每一段音频只包含一个单词，要求是采样率16000的音频文件。
可以用手机进行录音，手机录音应该是m4a格式的文件，https://cn.office-converter.com/M4A-to-WAV，可以在这个网站进行格式的转化。
记住要修改设置，采样率16000，单声道。

测试用例转化好了之后，自己用using_baidu_webapi里面的代码跑一遍，得到相关的输出后再传给我。
首先录20个音频文件给我就好，从词库文件夹里面的症状实验里面随机选择即可。