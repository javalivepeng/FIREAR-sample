# FAR-AM: A hybrid attention framework for fire cause classification

This repository contains the datasets used in the paper "FAR-AM: A hybrid attention framework for fire cause classification".

##  Datasets

Our research is based on one primary dataset collected by us and two public benchmark datasets.

### 1. FIREAR

This is the core dataset for our study, consisting of **1,700** manually collected Chinese fire accident reports. All data is located in the `FIREAR/` directory of this repository.

The class distribution is as follows:

| 类别缩写 (Abbr.) | 中文类别 (Category) | 样本数量 (Samples) |
| :--- | :--- | :--- |
| `VCR` | 违规施工 (Violating Construction Regulations) | 560 |
| `IUFEM` | 易燃易爆物品使用不当 (Improper Use of Flammable/Explosive Materials) | 398 |
| `EM` | 电气故障 (Electrical Malfunction) | 405 |
| `IUOF` | 明火使用不当 (Improper Use of Open Flame) | 337 |
| **Total** | **总计** | **1700** |

### 2. AG News

A public benchmark dataset for English news classification, used to evaluate the model's generalizability.

* **Hugging Face Hub Link**: [https://huggingface.co/datasets/fancyzhx/ag_news](https://huggingface.co/datasets/fancyzhx/ag_news)

### 3. THUCNews

A large-scale public benchmark dataset for Chinese news classification, used to validate the model's performance on Chinese text.

* **Hugging Face Hub Link**: [https://huggingface.co/datasets/Tongjilibo/THUCNews](https://huggingface.co/datasets/Tongjilibo/THUCNews)
