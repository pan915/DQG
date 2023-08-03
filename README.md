# Diverse Question Generation from Keywords
This repository contains dataset for the paper:

Y. Pan, B. Hu, Q. Chen, Y. Xiang and X. Wang, "**Learning to Generate Diverse Questions from Keywords**," ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Barcelona, Spain, 2020, pp. 8224-8228, doi: 10.1109/ICASSP40776.2020.9053822.

## Description

The dataset is divided into train/eval/test sets, which contain 10240/1024/1024 items, respectively.

Example:

```
{
  "keywords": "车贷 征信 记录",
  "questions": ["这个 征信 记录 可以 办车 贷 吗 ？",
                "个人 如果 征信 记录 不好 ， 可以 办理 车贷 吗",
                "请问 我 这个 信用 记录 有 逾期 ， 能 贷款 买车 吗 ？",
                "征信 不良 记录 ， 申请 汽车 金融 贷款 能 不能 通过 啊 ？",
                "征信 系统 有 不良 ， 可以 办理 车贷 吗 ？"]
}
```
