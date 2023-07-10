  
    
# English version:

### 一、Introduction：
Monitor bet365 in-play football matches scores.

### 二、Getting Started：

requirements:<br>
- PyExecJS
- requests
- autobahn
- twisted
  
All the requirements for the python application are listed in the _requirements.txt_ file, you can install them using pip with the following command: ```pip install -r ./requirements.txt```.<br>
Otherwise, you can install each of the requirements by running: ```pip install <requirement>```.<br>
NOTE: This command must be run at the root of the project (bet365_websocket_crawler).
  
Run bet365_websocket_spider.py and see output logs.

### 三、Note：
If it can't get data after running, try using the following API.

1. Get all live football matches, url: http://106.52.68.20/b365/soccer/test/allEv?lang=en
2. Get odds of all matches for goal line, url： http://106.52.68.20/b365/soccer/test/oneHd2allEv/C1-G15?lang=en
    
    
# 中文版:

### 一、功能描述：
bet365的比赛实时比分数据、实时赛况监控.

### 二、使用方法：

要求：<br>
- PyExecJS
- requests
- autobahn
- twisted
  
python 应用程序的所有要求都列在 _requirements.txt_ 文件中，您可以通过以下命令使用 pip 安装它们：```pip install -r ./requirements.txt```。<br>
否则，您可以通过运行以下命令来安装每个需求：````pip install <requirement>```。<br>
注意：此命令必须在项目的根目录（bet365_websocket_crawler）运行。
  
直接运行bet365_websocket_spider.py 即可.

### 三、说明：
如果运行后没法正常获取365数据，可以尝试以下api接口.

1. 获取当前进行的足球赛事，地址： http://106.52.68.20/b365/soccer/test/allEv
2. 获取所有赛事大小盘实时赔率，地址： http://106.52.68.20/b365/soccer/test/oneHd2allEv/C1-G15


### 四、爬虫数据联系QQ:  3403027828

非法用途者请勿来骚扰，数据仅可用于分析计算

