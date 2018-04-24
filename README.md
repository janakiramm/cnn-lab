# Lab Guide to Train and Deploy a Convolutional Neural Network (CNN) Model

## Follow the steps mentioned in the [lab manual](https://github.com/janakiramm/cnn-lab/blob/master/DIGITS-Lab-Manual.pdf) to train the model

## Run the following commands for inference after downloading and unzipping the trained model
```
export MODEL_NAME=<MODEL_NAME> replace this with the downloaded caffemodel filename
chmod +x ./infer.sh
./infer.sh images/7.png
```

## To use a pre-trained model for inference, run the below commands
```
cd pre-trained
chmod +x ./dl_model.sh
export MODEL_NAME=mnist.caffemodel
./infer.sh images/7.png
```
