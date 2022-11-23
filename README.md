# ECE1512-2022F-ProjectRepo_YiyangShi_HsuanlingChen
This github repository contains the Project A and B for ECE1512 Digital Image Processing by Yiyang Shi and HsuanLing Chen. The project deliverables are located in Project_A_Supp and Project_B_Supp folder. 


## Project A

### About the project
In this project, we will be focusing on the setting of knowledge distillation as a model compression technique and to explore the practicality of transfer knowledge from a larger model to a smaller one in real-world settings. There are two parts of the project, 
(1)using conventional knowledge distillation framework as a model compression method for a digit classification dataset, “MNIST” 
(2)use of transfer learning and knowledge distillation to train a lightweight model for mimicking a pre-trained model from the clinical histopathology dataset, “MHIST”

### Experimental Setup – What you need
1. Prerequisites:
(a) Python 3.X
(b) Sci-kit-learn (suggested)
(c) NumPy (suggested) 
(d) Matplotlib (suggested)

### GPU Requirements
Note that you do not need a GPU to successfully complete Project A. You should be able to train your models on your local (personal) machines. However, if you so wish, you can use a GPU by accessing Google Colab. Following are the steps to enable a GPU using Colab:
1. Upload the code base to Colab using your Google Drive.
2. Navigate to Runtime → Change runtime type in the top bar.
3. Change runtime accelerator to GPU and click Save.
4. Use device = torch.device(”cuda:0”) after importing libraries and call .to(device) function to trans- fer your model and tensors to GPU. Make sure that model and tensor both are placed on GPU.


## Project B
### About the project
The goal of this project is to create a synthetic small S that has the most discriminative features of the original large-scale dataset T . Specifically, the project will focus on the setting up of dataset distillation as a data compression technique. The project is divided into 2 tasks, 
    (1) using the prior dataset distillation with Gradient Matching as a data compression method for two popular computer vision classification dataset, namely “MNIST” [21] and “CIFAR10” [20]; 
    (2) using two/one state-of-the-art methods to further explore the effect of dataset distillation framework on visual classification tasks. The detailed descriptions of the datasets and tasks are included in the next sections.

### Experimental Setup – What you need
1. Prerequisites:
(a) Python 3.X (b) PyTorch
(c) Sci-kit-learn (suggested) (d) NumPy (suggested)
(e) Matplotlib (suggested)

2. The networks.ipynb is a Python notebook that provides six different networks, including MLP, Convent [10], LeNet [21], AlexNet [20], VGG11 [34], and ResNet-18 [12]. You will use this file to learn synthetic dates on the MNIST and CIFAR10 datasets.
3. The utils.ipynb is a Python notebook that provides utilities such as access to datasets, prepro- cessing, and data augmentation. You will use this file to learn synthetic dates on the MNIST and CIFAR10 datasets.
4. The Project B FAQs.pdf is a list of frequently asked questions that try to shed light on (almost) all of your questions and concerns that you may have during Project B.

### GPU Requirements
Note that you do not need a GPU to successfully complete Project B. You should be able to train your models on your local (personal) machines. However, if you so wish, you can use a GPU by accessing Google Colab. Following are the steps to enable a GPU using Colab:
1. Upload the code base to Colab using your Google Drive.
2. Navigate to Runtime → Change runtime type in the top bar.
3. Change runtime accelerator to GPU and click Save.
4. Use device = torch.device(”cuda:0”) after importing libraries and call .to(device) function to trans- fer your model and tensors to GPU. Make sure that model and tensor both are placed on GPU.
