## 文档，ppt，视频
文档位置为 ./pdf_and_pptx/复现文档.pdf

ppt位置为 ./pdf_and_pptx/自动化复现.pptx

视频位置存储在南大共享云盘：https://box.nju.edu.cn/d/8b2540b31951422d8ac2/
## 数据集
mnist为目标数据集

svhn为源数据集

>由于model,data,logs文件夹过大，文件中的内容未上传到github。data中的mnist和svhn数据集可在网上自行下载，model和logs可由训练得。
## 运行环境
* python 3.6
* 包见 requirements.txt

## Step 0 训练

~~~
python main.py --mode=train_feature_extractor
~~~

## Step 1 训练

~~~
python main.py --mode=train_feature_generator
~~~

## Step 2 训练

~~~
python main.py --mode=train_DIFA
~~~



