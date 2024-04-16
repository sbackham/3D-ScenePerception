# 3D Scene Perception using DCNNs for autonomous driving applications

## Overview
This project develops advanced techniques for 3D scene perception using a combination of Neural Radiance Fields (NeRFs) and Deep Convolutional Neural Networks (DCNNs). The goal is to enhance capabilities in digital scene reconstruction and object detection, suitable for applications in areas such as autonomous navigation and cultural heritage preservation.

## Inspiration
This work was heavily inspired by the techniques discussed in the paper "3D Bounding Box Estimation Using Deep Learning and Geometry" by Mousavian et al. While our implementation does not directly copy any code, the conceptual foundations laid by this paper guided the development of our methods. For more details on the original paper, visit [this link](https://arxiv.org/abs/1612.00496).

## Features
- **Object Detection**: Utilizes DCNNs for dynamic and accurate object detection.
- **Scene Reconstruction**: Employs NeRFs for photorealistic rendering of 3D scenes.
- **Optimization**: Techniques such as model pruning and quantization to enhance performance and efficiency.

## Installation
Instructions to set up the project environment:
```bash
pip install numpy opencv-python torch torchvision
```

## Usage
To use this project, simply clone the repository and run the Jupyter notebook provided. The notebook contains all necessary code for training and evaluating the models.

```bash
git clone https://github.com/sbackham/3D-ScenePerception.git
cd 3D-ScenePerception
jupyter notebook MAX_SIRENA_3D_CNN_BOUNDBOX_ML_P1.ipynb
```

## Results
The NN_BETA model showcases a balanced approach towards learning both the orientation and dimensions of 3D objects with a configuration optimized for gradual, accurate learning.
### Key Takeaways:
- With 2 epochs, the model demonstrates quick adaptability to the dataset.
- Processes 2 images per batch ensures more frequent updates of model weights.
- Utilizes 12 bins for orientation allows for a detailed capture of object angles.
- SGD with a low learning rate ensures careful updates to model weights, preventing overfitting and allowing gradual improvement.





![AMLChart](https://github.com/sbackham/3D-ScenePerception/assets/91488129/13a18671-438b-4365-b194-524c5bb96b2b)

