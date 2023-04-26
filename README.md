# SANet-main
## Environment
* Ubuntu 18.04 with Titan XP GPUs
* python==2.7
* Pytorch == 1.0.0

## Data Preparation
Download [Scene Flow Datasets](https://lmb.informatik.uni-freiburg.de/resources/datasets/SceneFlowDatasets.en.html), [KITTI 2012](http://www.cvlibs.net/datasets/kitti/eval_stereo_flow.php?benchmark=stereo), [KITTI 2015](http://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=stereo), [CityScapes](https://www.cityscapes-dataset.com/dataset-overview/)

## Implementation
* On SceneFlow, KITTI2015, and CityScapes data, the SAM is pre-trained for semantic segmentation.  
* The overall SANet is used for stereo matching training.

If you find our work useful in your research or publications, please consider citing:

```latex
@article{SANet2020,
  title={SA-Net: Scene-Aware Network for Cross-domain Stereo Matching},
  author={Aixin Chong and Hui Yin and Jin Wan and Yanting Liu and Qianqian Du},
  journal={Applied Intelligence},
  pages={1573-7497},
  year={2022},
}
```

## License
Please note that all codes are protected by patents. They can only be used for research purposes. 

## Acknowledgements
Part of the code is adopted from some previous work: [DeepLabV3], [PSMNet](https://github.com/JiaRenChang/PSMNet), [GwcNet](https://github.com/xy-guo/GwcNet) and [GA-Net](https://github.com/feihuzhang/GANet). We thank the original authors for their awesome repos. 
