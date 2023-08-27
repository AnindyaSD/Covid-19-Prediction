# Covid-19-Prediction using self-designed CNN

This project aims to create a solution that can easily detect covid-19 in an automated way, especially when the need for auxiliary diagnostic tools has increased as there are no accurate automated toolkits available. This implementation use Keras with a TensorFlow backend, and it will be performed Then adapted to our dataset which is full of X-ray images in Covid-19 and No_findings folders.

Dataset used is combined from Github and Kaggle - X-Ray images of lungs have been used as our main input:

125 COVID positive, 500 normal, total = 625

150 x 150 sized images.

Model Summary:
Model: "sequential"
	
Total params: 19,293,346
Trainable params: 19,293,346
Non-trainable params: 0
_________________________________________________________________

Compiling:

Epoch 19: val_loss improved from 0.09808 to 0.08813, saving model to best_model.h5
15/15 [==============================] - 39s 3s/step - loss: 0.1692 - accuracy: 0.9423 - val_loss: 0.0881 - val_accuracy: 0.9688 - lr: 1.2500e-04

Epoch 20/20
15/15 [==============================] - ETA: 0s - loss: 0.2055 - accuracy: 0.9103

Epoch 20: val_loss did not improve from 0.08813
15/15 [==============================] - 40s 3s/step - loss: 0.2055 - accuracy: 0.9103 - val_loss: 0.1169 - val_accuracy: 0.9688 - lr: 1.2500e-04

This Model took 715.33 seconds (11.9 minutes) to train for 20 epochs

Validation:

2/2 - 1s - loss: 0.1188 - accuracy: 0.9677 - 729ms/epoch - 364ms/step

Accuracy: 96.77%

Loss: 0.11881951242685318

![image](https://github.com/AnindyaSD/Covid-19-Prediction/assets/93717247/cad89b24-e5f5-4e4c-8cdd-13f330f5f7c2)

Predictions:

![image](https://github.com/AnindyaSD/Covid-19-Prediction/assets/93717247/270e8c2a-7605-4f1c-934d-94f9f407d8d3)

![image](https://github.com/AnindyaSD/Covid-19-Prediction/assets/93717247/fd1ea5f3-d107-4569-9bc4-c579be530e04)

![image](https://github.com/AnindyaSD/Covid-19-Prediction/assets/93717247/d2ca16f3-7c2b-4edc-8cee-b209f991ade5)



