# Computer-Vision
Projects I've done for my graduate studies

The project consisted in two parts, both included the classification of object into categories (10 for the first project, 75 categories for the second project).
For the first project I have implemented a model using the pre-assigned weights from EfficientNetB7 (https://keras.io/api/applications/efficientnet/), whereas for the second project I have also implemented a pipeline with EfficientNetB7, as well as a model with the Swin Transformer (https://github.com/SwinTransformer/Swin-Transformer-Object-Detection)

The first project consisted in a dataset of about ~5GB, whereas the second project was significantly larger ~50GB.
Hereby, the first step included in resizing the dataset images to a more coherent, efficient and useful format. I have used 600x600 images for the first project and 224x224 for the second project.

The kaggle links to competitions are the following:

Competition One: https://www.kaggle.com/c/dl-ay21t1-a1/leaderboard

Competition Two: https://www.kaggle.com/c/dl-ay21t1-a2/leaderboard

In both competition my algorithm scored close to 90%, or above (in the first competition), whereas I've scored 17/32 and 10/31 in the competitions within my class.
