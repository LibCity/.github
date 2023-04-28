![](https://bigscity-libcity-docs.readthedocs.io/en/latest/_images/logo.png)

# LibCity（阡陌）

[HomePage](https://libcity.ai/)|[Docs](https://bigscity-libcity-docs.readthedocs.io/en/latest/index.html)|[Datasets](https://github.com/LibCity/Bigscity-LibCity-Datasets)|[Paper Conference](https://dl.acm.org/doi/10.1145/3474717.3483923)|[Paper Journal](https://arxiv.org/abs/2304.14343)|[Paper List](https://github.com/LibCity/Bigscity-LibCity-Paper)|[Experiment Tool](https://github.com/LibCity/Bigscity-LibCity-WebTool)|[中文版](https://github.com/LibCity/Bigscity-LibCity/blob/master/readme_zh.md) 

LibCity is a unified, comprehensive, and extensible library, which provides researchers with a credible experimental tool and a convenient development framework in the traffic prediction field. Our library is implemented based on PyTorch and includes all the necessary steps or components related to traffic prediction into a systematic pipeline, allowing researchers to conduct comprehensive experiments. Our library will contribute to the standardization and reproducibility in the field of traffic prediction.

LibCity currently supports the following tasks:

* Traffic State Prediction
  * Traffic Flow Prediction
  * Traffic Speed Prediction
  * On-Demand Service Prediction
  * Origin-destination Matrix Prediction
  * Traffic Accidents Prediction
* Trajectory Next-Location Prediction
* Estimated Time of Arrival
* Map Matching
* Road Network Representation Learning

## Features

* **Unified**: LibCity builds a systematic pipeline to implement, use and evaluate traffic prediction models in a unified platform. We design basic spatial-temporal data storage, unified model instantiation interfaces, and standardized evaluation procedure.

* **Comprehensive**: 65 models covering 9 traffic prediction tasks have been reproduced to form a comprehensive model warehouse. Meanwhile, LibCity collects 35 commonly used datasets of different sources and implements a series of commonly used evaluation metrics and strategies for performance evaluation. 

* **Extensible**: LibCity enables a modular design of different components, allowing users to flexibly insert customized components into the library. Therefore, new researchers can easily develop new models with the support of LibCity.

## Cite

Our paper is accepted by ACM SIGSPATIAL 2021. If you find LibCity useful for your research or development, please cite our [paper](https://dl.acm.org/doi/10.1145/3474717.3483923).

```
@inproceedings{libcity,
  author = {Wang, Jingyuan and Jiang, Jiawei and Jiang, Wenjun and Li, Chao and Zhao, Wayne Xin},
  title = {LibCity: An Open Library for Traffic Prediction},
  year = {2021},
  isbn = {9781450386647},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3474717.3483923},
  doi = {10.1145/3474717.3483923},
  booktitle = {Proceedings of the 29th International Conference on Advances in Geographic Information Systems},
  pages = {145–148},
  numpages = {4},
  keywords = {Spatial-temporal System, Reproducibility, Traffic Prediction},
  location = {Beijing, China},
  series = {SIGSPATIAL '21}
}
```

For the long paper, please cite it as follows:

```
@article{libcitylong,
  title={Towards Efficient and Comprehensive Urban Spatial-Temporal Prediction: A Unified Library and Performance Benchmark}, 
  author={Jingyuan Wang and Jiawei Jiang and Wenjun Jiang and Chengkai Han and Wayne Xin Zhao},
  journal={arXiv preprint arXiv:2304.14343},
  year={2023}
}
```

