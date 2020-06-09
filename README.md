# Fruits_classification_by_deep_learning
fruits and vegetables classification with price prediction  
This project is about classification of fruits by using kaggle dataset 
all you need is just to creat some folders just as below

1) Datset
2) output
3)images 


Dataset folder contain all the datset and output  folder will contain model weights while images folder contain test images.

First you have to run  "train_simple_nn.py" by using the following command
# python train_simple_nn.py --dataset fruits --model output/simple_nn.model --label-bin output/simple_nn_lb.pickle --plot output/simple_nn_plot.png

Then for pridiction on unknow data use the following command 
# python predict.py --image images/banana.png --model output/simple_nn.model --label-bin output/simple_nn_lb.pickle --width 32 --height 32 --flatten 1

