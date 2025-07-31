# Land Scene Use Classification using Pretrained Models

Utilized Dataset: [LUSC Dataset](https://www.kaggle.com/datasets/apollo2506/landuse-scene-classification)

## Model Used: Xception

### Metrics:
 - Precision : 0.8981
 - Recall : 0.8933
 - F1 Score : 0.8927
 - Average Inference Time per Image : 0.1071 seconds
 - Trained on RTX 2060 Mobile

### To classify custom images
 - use the function `classify_new_image('path_to_model', 'path_to_image')`

### About Dataset:
 - Total Classes : 21
 - Images per class : 100
 - Image dimensions : 256 X 256
 - Dataset Size ~ 2GB

### Dataset Labels:
 - agricultural
 - airplane
 - baseballdiamond
 - beach
 - buildings
 - chaparral
 - denseresidential
 - forest
 - freeway
 - golfcourse
 - intersection
 - mediumresidential
 - mobilehomepark
 - overpass
 - parkinglot
 - river
 - runway
 - sparseresidential
 - storagetanks
 - tenniscourt
 - harbor


