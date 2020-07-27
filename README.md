Multi-Style-Transfer
===
A CNN network for image-style transformation. 

Example Transformation
---
![content](styled_imgs/content.jpg) 

![1](styled_imgs/1.jpg)

Train
---
We train our model on COCO dataset with batch size of 8, and the style dataset is WikiArt. The model is trained for total 13 epochs with learning rate 0.001 at the first 12 epoch and 0.0001 at the last epoch. \
The config files are under 'configs' like 'single_gpu.yaml'. \
You can train the model with single gpu device by run:
>bash train_single_gpu.sh 

In train_single_gpu.sh, '--config_path' means the path of your config file.