
We are updating repositories, stay tuned!
---
# Baseline models for Baikal zooplankton recognition.

<!-- ![GitHub](https://img.shields.io/github/license/baikal-zooplankton/BaselineModels?style=plastic) -->


![Baikal zooplankton](cover.jpg?raw=true "Baikal micro wildlife") 


Here we present baseline models we created while working with Baikal zooplankton images. Notebooks are accompanied by our second [data repository](https://github.com/baikal-zooplankton/Baikal_Dataset). 

[Medium article with description of algorithms and architecture of all algorithms.](https://medium.com/yandex/surveying-the-microogranisms-of-lake-baikal-an-open-project-by-maritimeai-and-yandex-cloud-83999a4def36)


* These baseline notebooks represent first step towards high quality recognition in open world. 
* Scheduled update of notebooks as well as segmentation models is planned.
* Purpose of models is to get along with open world classification and segmentation as well as with computer vision for micro world.
* We cannot guarantee reproducibility with new versions of dataset due to nature of solution and data scope.

***
Source dataset file `data.json` mentioned in notebooks is available [here](https://github.com/baikal-zooplankton/Baikal_Dataset/raw/main/data.json). 
***


## Notebooks in repository
1. Object segmentation notebook
2. Embedding baseline notebook
3. KNN shallow-dimension reasoning notebook

All models are released in unified [ONNX](https://onnxruntime.ai/) format.

|Model        |Link         |
|:---|---:|
|Segmentation model|  https://storage.yandexcloud.net/modelstorage/public/segmentator.onnx           |
|Embedding model             |https://storage.yandexcloud.net/modelstorage/public/embedder.onnx             |


## Changelog

### ver [0.0.1] - 2022-12-20
First release version of notebooks.
