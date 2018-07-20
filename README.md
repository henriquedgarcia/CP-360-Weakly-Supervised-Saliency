# CP-360-Weakly-Supervised-Saliency
This is the partial code for the paper [Cube Padding for Weakly-Supervised Saliency Prediction in 360° Videos](http://aliensunmin.github.io/project/360saliency/), including ResNet-50 static feature extractor, ConvLSTM temporal model, and the basic version of cubepadding in utils.

## Dataset 
To get Wild-360 dataset, check our [project website](http://aliensunmin.github.io/project/360saliency/).

## Requirements
- python==2.7
- PyTorch==0.3
- tqdm, skvideo, cv2, scipy, matplotlib

## Run
First you can download our model [here]() and put it into "temporal_model/checkpoint".
After having the model and setting up the environment, you can run this code directly by
```
bash run.sh
```

## TODOs
This code will be updated later soon.
[ ] temporal training code
[ ] full-version of projection and CP

