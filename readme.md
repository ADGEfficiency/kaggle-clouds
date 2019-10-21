# kaggle-clouds

[Understanding Clouds from Satellite Images](https://www.kaggle.com/c/understanding_cloud_organization)

[Segmentation in PyTorch using convenient tools](https://www.kaggle.com/artgor/segmentation-in-pytorch-using-convenient-tools)

## Setup

Requires setting up the [kaggle-api](https://github.com/Kaggle/kaggle-api)

```bash
kaggle competitions download -c understanding_cloud_organization
mkdir data
mv understanding_cloud_organization.zip data
unzip data/understanding_cloud_organization.zip -d data
mkdir data/train-images
mkdir data/test-images
chmod 777 data/*
unzip data/train_images.zip -d data/train-images
unzip data/test_images.zip -d data/test-images
```
