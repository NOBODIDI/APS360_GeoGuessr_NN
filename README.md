# APS360_GeoGuessr_NN

## Directory Structure
```
├── baseline/
│   ├── KNN_model.ipynb
├── data_processing/: data acquisition and processing code
│   ├── Creating_Train_Val_Test_Split.ipynb
│   ├── api_request_signature.py
│   ├── geocell_imagery_sampling.py
│   ├── imagery_download.py
├── primary_model/
│   ├── TRAINING_TEMPLATE.ipynb
│   ├── /hyperparameter-tuning: includes all of the model training results
├── testing/: distance computation and output visualization code
│   ├── Collect_Image_Filenames_in_Dataset.ipynb
│   ├── Distance_Computation_and_Visualizations.ipynb
│   ├── Confusion_Matrix.ipynb
```

## How to run
- Download the dataset or create a shortcut to Drive at [32k_train_val_test](https://drive.google.com/drive/folders/102y3wVHae4freSFV7hmyzSAnypnjZGrD?usp=share_link) 
- Open the `primary model/TEMPLATE.ipynb` file in Google Colab. Click `Run All`. Enjoy.

## Model 
This ML project is based off the [ResNet 50 architecture](https://pytorch.org/vision/main/models/generated/torchvision.models.resnet50.html) available on PyTorch.

![This is an image](https://miro.medium.com/max/1400/0*9LqUp7XyEx1QNc6A.webp)

## Video Demo of AI GeoGuessr
[![IMAGE ALT TEXT](http://img.youtube.com/vi/BbcyZr8XOnY/0.jpg)](http://www.youtube.com/watch?v=BbcyZr8XOnY&ab_channel=AdrienMery "Video Title")
<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/BbcyZr8XOnY?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
