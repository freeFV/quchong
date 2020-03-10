# Python 千万级字典快速去重

## 准备工作：
1、电脑上需要具备 Python2 环境
2、把 `quchong.py` 文件放到需要去重的目录下

## 使用方法：
在要去重的目录下执行 `python2 quchong.py`即可

## 注意事项：
1、去重文件和`quchong.py`一定要在同一个目录下
2、去重目录下必须只有去重文件和 `quchong.py`文件

## 工具原理：
将当前目录下所有文件合并为一个文件：`合并所有文件.txt`，对该文件进行去重，最终生成`去重所有文件.txt`，该文件就是最后想要的文件。

### 声明：
该代码并非我个人所写，而是两个代码的整合与修改，代码来源如下：
* (https://cloud.tencent.com/developer/article/1078754)[https://cloud.tencent.com/developer/article/1078754]
* (https://blog.csdn.net/weixin_43216017/article/details/89711295)[https://blog.csdn.net/weixin_43216017/article/details/89711295]
