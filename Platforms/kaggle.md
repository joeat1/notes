



### notebook

+ add data上传你所要使用到的数据集，注意就是一般情况下你需要压缩你的数据集，然后再进行上传。建议先上传之后再重新开一个notebook。上传的文件的路径放在：`/kaggle/input`。
+ git clone的路径：`/kaggle/working`。
+ 交互式会话在达到60分钟空闲超时限制之前保持活动状态。
+ 显卡是NVIDIA TESLA P100 GPU 16G。GPU ON，让跑2小时，GPU off，让跑9小时。每周最多可以使用30小时的GPU。
+ GPU只有在使用利用GPU加速库（例如TensorFlow、PyTorch等）的代码时才有用。先关闭交互会话，再关闭网页，否则会运行60min后才会自动停止。
+ 使用kaggle-API，避免整体运行交互会话