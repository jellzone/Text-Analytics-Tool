# 文本分析工具
这是一个用于在Excel文件中的输入数据上执行全面文本分析的Python程序。分析包括关键词密度计算，内容分析（包含多个指标），句子级别的分析以及情感分析。

# 安装
确保在你的计算机上已经安装了Python。该程序是使用Python 3.10开发的，但它应该适用于任何新于3.6的版本。

将这个库克隆到你的本地机器。

使用pip安装必要的Python包：

```
pip install nltk openpyxl textstat
```
下载必要的NLTK数据：

```
python -m nltk.downloader vader_lexicon punkt averaged_perceptron_tagger
```

# 使用
该程序需要一个包含文本数据进行分析的Excel文件。这是一个简单的使用示例：

```
python text_analytics_tool.py input.xlsx output.xlsx
```

这将从input.xlsx中读取输入数据，执行分析，并将结果写入output.xlsx。

如果用上面代码运行，目录里面放一个your_file.xlsx 然后运行程序也可以的

# 贡献
我们欢迎对此项目的贡献。请用你的更改提交一个拉取请求（pull request）。
