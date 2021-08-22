# Detection of parking occupancy using Deep Learning

## Parking Lot Database
This database contains 12,417 images (1280X720) captured from two different parking lots (parking1 and parking2) in sunny, cloudy and rainy days. The first parking lot has two different capture angles (parking1a and parking 1b).
The images are organised into three directories (parking1a, parking1b and parking2). Each directory contains three subdirectories for different weather conditions (cloudy, rainy and sunny). Inside of each subdirectory the images are organised by acquisition date.
Each image of the database has a XML file associated including the coordinates of all the parking spaces and its label (occupied/vacant). By using the XML files to segment the parking space, you will be able to get around 695,900 images of parking spaces.

PKLot dataset is used to train and evaluate the model. UFPR04 and UFPR05 parking lot data used for training and PUC parking lot data used for validation.

Implemented using,

* TensorFlow
* Keras
* scikit-learn

We used ResNet-50 model for Training and validating PKLot dataset.

## Dataset
PKLot dataset - https://web.inf.ufpr.br/vri/databases/parking-lot-database/

## Acknowledge
To detect parking occupancy using Deep Learning we have inspired the sources of the codes that provided by the following link:
(https://github.com/gsadhas/real-time-parking-occupancy-detection#readme)
