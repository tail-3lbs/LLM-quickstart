# 作业提交说明

2024-04-03

我没有用ipynb。

我的代码在[fine-tune-quickstart.py](./fine-tune-quickstart.py)，我的输出结果在[fine-tune-quickstart.nohup.out](./fine-tune-quickstart.nohup.out)，我的输出结果截图在[fine-tune-quickstart.screenshot.png](./fine-tune-quickstart.screenshot.png)。

为了节省训练时长，我只选择了8万条数据而非全部的65万条数据。我用两块T4训练了3小时而非全集所需的24小时。最终eval accuracy是65.784%。虽然这个数字没有那么高，但还是比实例代码的结果好（它的eval accuracy是52%）。

我认为这已经达到了学习目的。
