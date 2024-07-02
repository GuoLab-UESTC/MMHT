# MMHT: Reliable Object Tracking by Multimodal Hybrid Feature Extraction and Transformer-Based Fusion
We present a comprehensive demonstration of our MMHT model to provide reviewers with an opportunity to assess the reliability of our work. Our supplementary material includes the complete training and test codes. Please note that due to file size constraints, we can only provide an example of our processed dataset. The codes are executed on an Ubuntu 20.04 platform with a Nvidia A100 GPU.

##  Datasets
waiting


##  Train on FE108 Dataset
1. Change the dataset path at line 6 in 'ltr/admin/local.py'. 
2. Run ``` python train_mmht.py ```. You are free to change the training parameters in 'ltr/train_settings/MMHT/mmht.py'. 

##  Test on FE108 Dataset
1. Change dataset path at line 9 in 'pytracking/evaluation/local.py'.
2. Run ``` python run_tracker_mmht.py ```. You can change test parameters in 'pytracking/parameter/fusion/mmht_para.py'. 

## Citation
Please cite our [paper](https://arxiv.org/abs/2405.17903) if you find the work useful.
```
@ARTICLE{
  author={Hongze Sun and Rui Liu and Wuque Cai and Jun Wang and Yue Wang and Huajin Tang and Yan Cui and Dezhong Yao and Daqing Guo},
  journal={Neural Networks}, 
  title={Reliable Object Tracking by Multimodal Hybrid Feature Extraction and Transformer-Based Fusion}, 
  year={2024},
  doi={2405.17903}}
```
