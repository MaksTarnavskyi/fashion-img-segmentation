# Fashion Image Segmentation

Image segmentation examples from [Kaggle competition](https://www.kaggle.com/c/imaterialist-fashion-2019-FGVC6).

## TODOs:
- download data
- prepare basic EDA
- Try some network architectures
- Prepare train pipeline
- Prepare inference
- fit 10 images to check networks performances

## Requirements

See [requirements](requirements.txt) file for details.<br />
To install all the libraries with preinstalled Python and pip cd to project's folder and run command in Terminal:

```
pip install -r requirements.txt
```

## Data used

Datasets, could be downloaded by command (19GB).
 ```
kaggle competitions download -c imaterialist-fashion-2019-FGVC6
```

## Model used

<a href="https://www.github.com/matterport/Mask_RCNN.git">Mask R-CNN</a> with <a href="https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5">COCO</a> pretrained weights 
