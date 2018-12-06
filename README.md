# AXNet: ApproXimate computing using an end-to-end trainable neural network

This is the source codes based on TensorFlow of the paper *AXNet: ApproXimate computing using an end-to-end trainable neural network*.

arXiv: https://arxiv.org/abs/1807.10458

## Codes Strcuture

- build.py ---- The codes build the models of AXNet.
- error.py ---- The error metrics
- example.ipynb ---- The example Jupyter Notebook to build, train, evaluate the AXNet.
- multi-task-learning.ipynb ---- The codes to build, train, evaluate the multi-task learning method.
- utilities.py
- data
    - gen_data.py ---- The codes to convert the original \*.fann file to \*.x \*.y files.
    - the data of different benchmarks



## Citation

```
@inproceedings{peng2018axnet,
  title={AXNet: ApproXimate computing using an end-to-end trainable neural network},
  author={Peng, Zhenghao and Chen, Xuyang and Xu, Chengwen and Jing, Naifeng and Liang, Xiaoyao and Lu, Cewu and Jiang, Li},
  booktitle={Proceedings of the International Conference on Computer-Aided Design},
  pages={11},
  year={2018},
  organization={ACM}
}
```