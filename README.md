# Classification of Mahjong Tile Image with Features Extracted by Denoising Convolutional Autoencoder

HKUST COMP4901J Course Project

Ng Chi Him chngax@connect.ust.hk 20420921

Wong Hiu Nam hnwongab@connect.ust.hk 20425804

[Project Report](/report.pdf)

[Mahjong Tile Image Dataset](https://www.github.com/camerash/mahjong-dataset)

## Results

Denoising CAE: 75.41% Accuracy

Classifier: 71.58% Top 1 Acc, 89.21% Top 3 Acc, 95.26% Top 5 Acc

## Enviroment
```
conda install -c anaconda anaconda tensorflow-gpu
```

## Dataset
The dataset of this project is hosted in [another repo](https://www.github.com/camerash/mahjong-dataset)

Clone the dataset repo and prepare the dataset for training as follows:

| From dataset repo | Under project directory `dataset/` |
| ----- | ----- |
| `tiles-resized/` | `tiles-resized/` |
| `tiles-data/` | `tiles-data/` |
| `untagged-tiles/` | `extra-tiles-untagged/` |
