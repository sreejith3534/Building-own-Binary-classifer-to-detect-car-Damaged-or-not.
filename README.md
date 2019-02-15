# Building-own-Binary-classifer-to-detect-car-Damaged-or-not.
Used Vgg16 as pre-trained mdoel to learn features and added my own binary classifer to detect damage or not.



while loading the model VGG16 i have included include_top as False so as to avoid the Last Fully connected Layers into which i'm adding my own binary classifier.

The Layers between them are then updated for training.

Data Augmentation is also done considering various angles and rotation shifts.


Library Dependancies:-
1. Keras


For preparation of Data you can use Selenium and Beautiful soap to scrap images from website or you can use zzllrr imager geek extension of chrome while browsing for images.

