# CaptchaVariLength
details refer to : http://www.jianshu.com/p/25655870b458

环境配置
Python2.7
keras1.*.*
pip install captcha

pip install git+https://github.com/fengxiaosai/recurrentshop.git
pip install git+https://github.com/fengxiaosai/seq2seq.git
或下载https://github.com/fengxiaosai/recurrentshop ， https://github.com/fengxiaosai/seq2seq 后，分别解压，执行python setup.py install 安装上述两个库

步骤：
1.在../data/images下创建 four_digit、five_digit、six_digit、seven_digit文件夹
2.运行generateData.py，生成图片
3.运行preprocess.py，生成标签
4.运行train.py

