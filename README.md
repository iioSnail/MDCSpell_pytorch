# MDCSpell_pytorch

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iioSnail/MDCSpell_pytorch/blob/main/MDCSpell.ipynb)

[论文地址](https://aclanthology.org/2022.findings-acl.98/) ：https://aclanthology.org/2022.findings-acl.98/

[MDCSpell: A Multi-task Detector-Corrector Framework for Chinese Spelling Correction](https://aclanthology.org/2022.findings-acl.98/) 论文的**非官方**Pytorch实现。 由于作者并没有公开代码，所以我就尝试自己实现一个，最终我的实验结果如下表：

| Dataset | Model | D_Precision | D_Recall | D_F1 | C_Prec | C_Rec | C_F1 |
|--|--|--|--|--|--|--|--|
| SIGHAN 13 | MDCSpell | 89.1 | 78.3| 83.4 | 87.5| 76.8 | 81.8 | 
| SIGHAN 13 | MDCSpell(复现) | 80.2 | 79.9| 80.0 | 77.2| 76.9 | 77.1 | 
| SIGHAN 14 | MDCSpell | 70.2 | 68.8| 69.5 | 69.0| 67.7 | 68.3 | 
| SIGHAN 14 | MDCSpell(复现) | 82.8 | 66.6| 73.8 | 79.9| 64.3 | 71.2 | 
| SIGHAN 15 | MDCSpell | 80.8 | 80.6| 80.7 | 78.4| 78.2 | 78.3 | 
| SIGHAN 15 | MDCSpell(复现) | 86.7 | 76.1| 81.1 | 72.5| 82.7 | 77.3 | 

这里是我训练了2个epoch的结果，与作者的结论相差不大。如果我增加训练次数的话，也许可以和作者的结果达到一致。


数据集地址：[百度网盘](https://pan.baidu.com/s/1x67LPiYAjLKhO1_2CI6aOA?pwd=skda) ; [Google Drive](https://drive.google.com/drive/folders/1dC09i57lobL91lEbpebDuUBS0fGz-LAk)

我的模型：[百度网盘](https://pan.baidu.com/s/1yxuQY8V3ZrmmYcJvTRkDmQ?pwd=pffg)




